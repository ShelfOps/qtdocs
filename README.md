# qtdocs for qtcraft :)


## Testing Locally

** Install mkdocs-material**
```sh
pip install mkdocs-material 
```
** Install Dependencies**
```sh
pip install mkdocs-macros-plugin
```

```sh
pip install mkdocs-git-revision-date-localized-plugin
```




## Deploying
**Deploy to Github Pages**
```sh
gh-deploy --force
```

## Sample Workflow Pseudocode
```yml
      - run: pip install mkdocs-material 
      - run: pip install mkdocs-macros-plugin
      - run: pip install mkdocs-git-revision-date-localized-plugin
      - run: mkdocs gh-deploy --force
```
