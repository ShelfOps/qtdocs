# qtdocs for qtcraft :)


## Testing Locally 
*P.S: This guide assumes that you have git installed and configured on your system alongside SSH keys*

1. Start by cloning the repository using `git@github.com:qtcratmc/qtdocs.git`
2. If you already have it cloned, do `git pull` to pull all latest changes.

3. **Install mkdocs-material**
```sh
pip install mkdocs-material 
```
4. **Install Dependencies**
```sh
pip install mkdocs-macros-plugin
```

```sh
pip install mkdocs-git-revision-date-localized-plugin
```

5. **Run Local Webserver**
Before you push your changes, preview the site using
```sh
mike serve
```
This will run a local webserver on http://localhost:8080 (accessible to *you only*) 
Use this webserver to check if your changes are correct and then move to the next step.

6. **Pushing your changes**
- Start by adding your files to git by `git add <filename>` (without the < >)
If you want to add all files at once, you can do `git add .`
- Then commit those files with either 
  - `git commit` <- will require you to set a message for each commit
  - `git commit -m "your message here"` <- will commit all changes with a single message, which is specified with `"your message here"`
- Now that it's done, push your changes with `git push`


## Deploying
TODO


