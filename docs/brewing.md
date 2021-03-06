Depending on the Recipe, some Steps may not be needed, the following instruction describes the common procedure of brewing.

### Fermenting

Step one consists of Fermenting the fresh Ingredients.

1. Place Cauldron over a Fire or other heat source
2. Fill it with water
3. Add Ingredients with a rightclick
4. Wait a few minutes while they ferment
5. Fill in glass bottles

![](http://i.imgur.com/1Dcln19.png)

Use a clock on a cauldron, if you want to know the time the ingredients have been fermenting.

### Distilling
Some Recipes don't need distilling.
1. Put the bottle with ferment into the brewing stand
2. Put glowstone dust as filter on top into the brewing stand (The filter will not be consumed)

![](http://i.imgur.com/RJKV9Xs.png)

### Aging

A barrel is needed for aging. 

**Minecraft Barrel** | _6 Slots_

Starting in 1.14 the [Minecraft-Barrel](https://minecraft.gamepedia.com/Barrel) can be used for aging of a few brews.
Simply craft and place the barrel and put the brews inside.

![](https://gamepedia.cursecdn.com/minecraft_de_gamepedia/thumb/3/33/Fass.png/150px-Fass.png?version=ed8bc982279530ea46dac7b932ec1b86)

You can also build bigger barrels. They can be built in two ways:

**Small barrel** | _9 Slots_

Use 8 wooden stairs to build a barrel shape.

Place a Sign on the lower right side and write "Barrel" in the upper Line:

![](https://imgur.com/Mspl5n6.png) ![](https://imgur.com/BkNsi54.png)

![](http://i.imgur.com/uIpCfxA.png)

Message "Barrel created" should appear.


**Big barrel** | _27 Slots_

Use 5 Fences, 16 Wooden stairs, and 18 wood planks to build a barrel shape.
Attach a Spigot (Fence) and a Sign that has "Barrel" written on it:

![](https://imgur.com/FOr7lN5.png) ![](https://imgur.com/k3h4qj0.png)

Message "Barrel created" should appear  
**You may remove the Sign from the Big Barrel after creating it.**

------


Open the Barrel by clicking on it.

* Put the Bottles into the Barrels for aging.  
* For every Minecraft Day, the brews will age a year.  
* Depending on the Recipe, the Type of wood used for building the barrel may alter the quality of the aged Brew.
* The Minecraft-barrel is always of wood type oak.


### Locking the Barrel

<details>
  
  The Barrels can be locked and Protected by a variety of Plugins. 

  To Lock your Barrel you can use:
  * [LWC Extended](https://www.spigotmc.org/resources/lwc-extended.69551/)  
    Just use /cprivate on the sign of the Barrel
  * [BlockLocker](https://www.spigotmc.org/resources/blocklocker.3268/)  
    When creating the Barrel, write `[private]` on the first line and `Barrel` on the last line of the sign


  Supported Plugins for region Protection are:
  * WorldGuard
  * GriefPrevention
  * Towny
  * GMInventories
  * Landlord
  * ProtectionStones
  * ClaimChunk
  * Residence
  * And many others. For "Residence" and if your plugin doensn't work with Brewery, enable `useVirtualChestPerms: true` in the config
  
  For scripts, or to implement support for Barrels, the [BarrelAccessEvent](https://github.com/DieReicheErethons/Brewery/blob/master/src/com/dre/brewery/api/events/barrel/BarrelAccessEvent.java) from Brewery can be used.

</details>


### Drinking

The Amount of Alcohol inside the Brew will be applied to the player when drinking. Depending on the quality of it, that may have different effects.

* The Player may not be able to walk normally anymore, he will weave, making it almost impossible to walk straight
* Effects like Blindness, Confusion, Poison etc. occur
* The Chat will be altered depending on drunkeness, many things players write may be incomprehensible, sometimes it seems senseless
* Is the Alcohol particularly strong, it may have poisonous effects
* After drinking a lot, there is a chance of vomiting
* When logging off, the player may have difficulties reaching his character, thus some loggins shortly after may be denied
* After Overdrinking the player may faint (Disconnecting)

### Brew Sealing - for shop plugins

You can just give your created Brews to other Players and they might even put them back into a Barrel to keep ageing them.
But most Shop-Plugins require sold items to be exactly equal and this is where sealing comes in. Imagine it like putting a seal on the bottle.

* To sell Brews using Shop-Plugins, you will need to seal them using the Brew Sealing Table.
* It is crafted with 2 Bottles over 4 Planks
* Putting a Brew into the Sealing table will equalise it, making it equal to other Brews that have been brewed similarly.
* Sealed Brews cannot be aged or modified any further and they don't show their details anymore 

![Brew Sealing Table recipe](https://zebradrive.de/index.php/s/aJXpWPjZAWnAvVE/download)  
_Only available on 1.14 and up. Use /brew seal on 1.13._

### Getting Sober

After drinking it takes a while until the alcohol is completely gone. During that time the alcohol level is steadily decreasing. Also it can be decreased through consuming of items defined in the config.

* When logging off extremely drunk, it may happen that, if the player logs back in after a while, they may find themselves at an completely unknown Place in the middle of nowhere having no idea how he got there.
* But if they log back in after some hours or next morning, they will find themselves at /home, again without any memories.
* Also if the Alcohol was not of best quality, the player may face some bad type of hangover (slowness and hunger).

Some recipes are more difficult to master, others rather easy. Thats also why some of the recipes here are kept a bit more vague.  

***


| Recipe       | Ingredients                | Boiling Time | Distilling | Ageing/Wood | Alc | Effects |
|-------------|-------------|-----|-----|-----|-----|---|
| Beer         | 6 Wheat                    | 8 Minutes       | No  | 3 Years<br>Any         | I    |    |
| Wheatbeer    | 3 Wheat                    | 8 Minutes       | No  | 2 Years<br>Birch       | I    |    |
| Darkbeer     | 6 Wheat                    | 8 Minutes       | No  | 3 times Beer<br>Dark Oak | I'   |    |
| Red Wine     | 5 Sweet Berries            | 5 Minutes       | No  | Very Long<br>Any       | I'   |    |
| Mead         | 6 Sugar Cane               | 3 Minutes       | No  | 4 Years<br>Oak         | I'   |    |
| Apple Mead   | 6 Sugar Cane<br>Apple      | Similar to Mead | No  | 4 Years<br>Oak         | II   | +  |
| Apple Cider  | Lots of Apple              | 7/8 Minutes     | No  | 3 Years<br>Any         | I'   |    |
| Apple Liquor | Lots of Apple              | Long            | Yes | 6 Years<br>Acacia      | II'  |    |
| Whiskey      | Wheat                      | 1 min. per Wheat | Yes | Very Long<br>darker   | III' |    |
| Rum          | Lots of Sugar Cane         | Short           | Yes | Long<br>Oak            | IIII | +  |
| Vodka        | A Sixth of a Stack Potatoes | Long           | Yes | No                     | III  | -  |
| Mushroom Vodka | Potatoes, Mushrooms      | Very Long       | Yes | No                     | II' | +- |
| Gin          | 9 Wheat<br>Some blue -flowers<br>Apple | Short | Yes | No                    | III  |    |
| Tequila      | Some Cactus                | Long            | Yes | Long<br>Birch          | III  |    |
| Absinthe     | Lots of Grass              | Short           | Yes | No                   | IIIII' | -  |
| Green Absinthe | Lots of Grass<br>Another Greenish thing | Normal | Yes | No             | IIIIII | +- |
| Potato Soup  | 5 Potatoes<br>Some Grass   | Short           | No  | No                     |      | +  |
| Coffee       | Lots of Cocoa Beans<br>2 Milk Buckets | Short | No | No                     |      | ++ |
| Eggnog      | 5 Eggs<br>A little sugar<br>1 Milk Bucket | Short | No | Short<br>Any          | I'   |    |

