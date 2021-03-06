TO INSTALL MCprep
======

### Click the link below and download the .zip file (re-zip if auto-unzipped into a folder necessary), install into blender.

[![Install MCprep](/visuals/mcprep_download.png)](http://theduckcow.com/dev/blender/mcprep-download/)

*By downloading and installing, you agree to the following [privacy policy](http://theduckcow.com/privacy-policy).* **[Watch this video](https://www.youtube.com/watch?v=i6Ne07-eIyI) on how to install if running into troubles.**


It should remain a zip folder. In blender, go to preferences, then the addons tab, and at the bottom of the window install from file. Select the .zip file. **NOTE:** _Blender may not automatically enable the addon. If the MCprep addon is not already shown in the window after installing, search for it at left and then ensure the check box is enabled._ **Save user preferences** to keep it enabled next time blender opens.

*Again, please download from the link above or the releases page, __not__ by clicking `download zip` button above.*

*The preferences panel should look like this after installing the zip file*
![Install MCprep](/visuals/install.png?raw=true)

**If you like the addon, [please consider donating](http://bit.ly/donate2TheDuckCow) for the continued quality development! [Share this addon](https://twitter.com/intent/tweet?text=Make+easier+Minecraft+renders+using+the+MCprep+addon+bit.ly/MCprep+by+@TheDuckCow) so others can benefit from it!**

Demo Usage
======


*[Mob spawner demo](https://www.youtube.com/watch?v=C3YoZx-seFE)*
 
 [![Mob spawner gif](/visuals/spawner-gif.gif)](https://www.youtube.com/watch?v=C3YoZx-seFE)

*[Pre-release demo, materials & meshswapping demo](https://www.youtube.com/watch?v=Nax7iuCTovk)*
 
 [![Alt text](/visuals/meshswap.demo.gif "Meshswap Preview")](https://www.youtube.com/watch?v=Nax7iuCTovk)

Other video demos:
- [Cycles Materials Upate](https://www.youtube.com/watch?v=MRuPRnfdzfI)
- [Grass field meshswapping](https://www.facebook.com/photo.php?v=737273036339269&l=2318416360725689976)


About MCprep
======

This is a blender python addon to increase workflow for creating Minecraft renders and animations, by automatically setting up better materials, importing library models and groups, and setting up proxy characters for animation and default animations for regular features like grass and leaves on imported 3D Minecraft worlds. This addon assumes you have already imported the Minecraft world. While the script should work for any world importer, it has been tested and developed based on the jmc2obj Minecraft world to obj file converted. The addon now also comes with built-in rigs, including characters and mobs, and allows you to quickly place them into your worlds.

This addon is made to work with an asset library directory, from which models and groups are linked or imported from. This library blend file is included, but does not have all types of blocks generated yet. This will be improved in the future.

This addon is compatible officially down to 2.72 official builds, up to blender 2.78+. Not all features are available in all versions, try to use the latest available blender. *Run into any problems? [Submit bugs/issues here](https://github.com/TheDuckCow/MCprep/issues).*


Feature list
======

| World Imports   |      Description      |
|----------|:-------------:|
| Prep Materials | Improves materials from world imports, and allows one-click switching from cycles & blender internal materials. *Note, this does not* create *materials, only modifies existing ones.* |
| Combine materials/images | Consolidates duplicate materials and images down to the smallest number of unique datablocks. *Note: combine images is only available on blender 2.78+* |
| Improve UI | A shortcut to quickly improve viewport settings for Minecraft sets. Sets textured solid mode & turns off mipmaps |
| Mesh Swap | Allows you to replace simple models from 3D exported worlds with more intricate 3D models |



| Skin Swapper   |      Description      |
|----------|:-------------:|
| Apply [skin] | Applies the currently list-selected skin to the actively selected rigs. |
| Skin from file | Loads in a skin texture from file and applies to the actively selected rigs. *Note: Also gets added to skin list* |
| Skin from username | Downloads a skin based on a play name and applies to the actively selected rigs. *Note: Also gets added to skin list* |
| + sign | Install a custom skin into the list without applying to a rig |

*Note: only 1.8 skin layouts are supported at this time, in the future an auto-conversion feature will likely be implemented*


| Spawner   |      Description      |
|----------|:-------------:|
| Spawn: [rig] | Based on the actively selected rig, from an according spawning rig category, add the mob/character into the scene. These are fully rigged characters. Using the plus sign, you can even install your own rigs (rig must be part of a group). For quicker mapping, you can even set an entire folder and it will auto-create subcategories of rigs based on folders. |
| Spawn: meshswap block | Place a block from the meshswap file into the 3D scene. Currently is limited to only having meshswap groups (e.g. torches and fire) and not objects (e.g. not supporting grass and flowers yet).|


### Spawner mobs included in the current version of MCprep
![included-mobs](/visuals/MCprep_mobs_included.png?raw=true)


CREDIT
======
While this addon is released as open source software, the assets are being released as [Creative Commons Attributions, CC-BY](https://creativecommons.org/licenses/by/3.0/us/). If you use MeshSwap, **please credit the creators** by linking to this page wherever your project may appear: [http://github.com/TheDuckCow/MCprep](https://github.com/TheDuckCow/MCprep)

Block models developed by [Patrick W. Crawford](https://twitter.com/TheDuckCow), [SilverC16](http://youtube.com/user/silverC16), and [Nils Söderman (rymdnisse)](http://youtube.com/rymdnisse).


| Player Rigs   |      Creator      |
|----------|:-------------:|
| Fancy Feet Generic Player (ideal for skinswapping) |  [Patrick W. Crawford](http://www.youtube.com/TheDuckCow) ([Rig link](http://bit.ly/MinecraftRig)) |
| Fancy Feet Steve |  [Patrick W. Crawford](http://www.youtube.com/TheDuckCow) ([Rig link](http://bit.ly/MinecraftRig)) |
| Fancy Feet Alex | Modified by [Jeremy Putnam](http://www.blendswap.com/user/lorddon) (MCprep exclusive) |
| Vilalger | [Patrick W. Crawford](http://www.youtube.com/TheDuckCow) ([Rig link](http://www.blendswap.com/blends/view/73063)) |
| VMcomix Steve (rounded) | [VMcomix](https://www.youtube.com/user/VMComix) ([Rig link](http://vmcomix.blogspot.com/)) |
| Story Mode Rig | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) (No direct link yet) |


| Passive Rigs   |      Creator      |
|----------|:-------------:|
| Bat | [Patrick W. Crawford](http://www.youtube.com/TheDuckCow) (MCprep exclusive) |
| Chicken | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) (No direct link yet) |
| Cow | [Nils Söderman (rymdnisse)](http://youtube.com/rymdnisse) ([Rig link](http://rymdnisse.net/downloads/minecraft-blender-rig.html)) |
| Pig | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) (No direct link yet) |
| Rabbit | [HissingCreeper](https://www.youtube.com/channel/UCHV3_5kFI93fFOl6KbmhkQA) (No direct link yet) |
| Sheep | [HissingCreeper](https://www.youtube.com/channel/UCHV3_5kFI93fFOl6KbmhkQA) (No direct link yet) |
| Squid | [Nils Söderman (rymdnisse)](http://youtube.com/rymdnisse) ([Rig link](http://rymdnisse.net/downloads/minecraft-blender-rig.html)) |


| Hostile Rigs   |      Creator      |
|----------|:-------------:|
| Blaze | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) (No direct link yet) |
| Creeper | [Patrick W. Crawford](http://www.youtube.com/TheDuckCow) (MCprep exclusive) |
| Enderman | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) ([Rig link](http://www.blendswap.com/blends/view/79750)) |
| Endermite | [Nils Söderman (rymdnisse)](http://youtube.com/rymdnisse) ([Rig link](http://rymdnisse.net/downloads/minecraft-blender-rig.html)) |
| Ghast | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) (No direct link yet) |
| Guardian | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) ([Rig link](http://www.blendswap.com/blends/view/79729)) |
| Shulker | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) ([Rig link](http://www.blendswap.com/blends/view/79729)) |
| Silverfish | [Nils Söderman (rymdnisse)](http://youtube.com/rymdnisse) ([Rig link](http://rymdnisse.net/downloads/minecraft-blender-rig.html)) |
| Skeleton | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) ([Rig link, outdated](http://www.blendswap.com/blends/view/79495)) |
| Slime | [Patrick W. Crawford](http://www.youtube.com/TheDuckCow) (MCprep exclusive) |
| Spider | [Nils Söderman (rymdnisse)](http://youtube.com/rymdnisse) ([Rig link](http://rymdnisse.net/downloads/minecraft-blender-rig.html)) |
| Zombie | [HissingCreeper](https://www.youtube.com/channel/UCHV3_5kFI93fFOl6KbmhkQA) (No direct link yet) |


| Friedly/Utility Rigs   |      Creator      |
|----------|:-------------:|
| Horse | [Patrick W. Crawford](http://www.youtube.com/TheDuckCow) ([Rig link](http://www.blendswap.com/blends/view/73064)) |
| Iron Golem | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) ([Rig link](http://www.blendswap.com/blends/view/79455)) |
| Ocelot | [HissingCreeper](https://www.youtube.com/channel/UCHV3_5kFI93fFOl6KbmhkQA) (No direct link yet) |
| Snow Golem | [Nils Söderman (rymdnisse)](http://youtube.com/rymdnisse) ([Rig link](http://rymdnisse.net/downloads/minecraft-blender-rig.html)) |
| Wolf | [Trainguy9512](https://www.youtube.com/channel/UCktn-etC2h25hMTk1tIz7IQ) ([Rig link, outdated](http://www.blendswap.com/blends/view/79628)) |



If you use any of these rigs in your animation, give credit to the according creator or by directly referring back to this readme file which contains all the credits. *Models have been slightly modified to function best and consistently with the MCprep addon.*

Icons generated by [Patrick W. Crawford](https://twitter.com/TheDuckCow), [MomentarilyEpic](https://www.youtube.com/channel/UCQFC0IHz4Jypi7JsWkKQgkA/about) and [HissingCreeper](https://www.youtube.com/channel/UCHV3_5kFI93fFOl6KbmhkQA).

Thank you to all the contributors to this project! It will continue to grow and cover more assets in the near future.



How to use this addon
======


### Setup materials:
- **Purpose:** To automatically setup better, crisp materials for rendering Minecraft, low resolution textures. It works for both Blender internal as well as cycles. It will even selectively turn 'shiny' materials into reflecting materials accordingly as well as 'bright' materials into emitting materials. Currently, the list of these materials is hard-coded in.
- **Step 1:** Export your world to an OBJ or other general 3D formats. I use jmc2obj, but Mineways or other such formats should be fine as well.
- **Step 2:** Import the world into blender (e.g. via file > import > obj, or whatever according format)
- **Step 3:** Select all, or select the objects that have the material you want to fix. Materials can be all separate objects or the same object, it does not matter.
- **Step 4:** Under the MCprep panel, press "Prep Materials".


### Meshswap:
- **Purpose:** To automatically swap in extra assets such as 3D grass, light emitting torches and lamps, and so forth. Note that all the objects to be swapped in are in the blend file part of this download. Also note that swapping is done based on the name of the material. If you are unsure why your object is not swapping in, check the material name matches the counterpart object/material in the meshSwap.blend file. Note it can search for both appendable objects as well as groups, containing particles and so forth. Modifiers on the mesh in the original file will be brought over, so notice for example how the tall grass when replaced will be "pre-simulated" as it has displacement modifiers setup already with animation.
- **Step 0:** By default this is already done for you; set the MeshSwap blend path to the "mcprep_meshSwap.blend" or custom blend file, and make sure the world export has blocks of size 1m (100cm).
- **Step 1:** Select the objects that you wish to be meshSwapped. Swappable objects are determined *automatically* based on the contents of the blend file selected above. If an object is not found or swappable, it will just be skipped - no harm done by "overselecting" (so select all objects to make sure everything that can be swapped gets swapped!)
- **Step 2:** Press Mesh Swap (there will be a small delay, meshswapping large areas such as fields of grass may take awhile).

*Setup your jmc2obj and Mineways worlds in this fashion for best results.*
![Exporter setups](/visuals/exporterSettings.png?raw=true)

*Note jmc2obj is preferred because of how the obj materials are exported, Mineways has more limitations.*

*Note 2: You can now also directly add meshswap blocks into the scene from the shift-A menu or the spawner:meshswap panel.*

To add your own objects to meshswap (or groupswap):
- **Step 1:** Check your imported world object and see the name of the material for the object you want to setup. You might think it is "glass plane", but if the importer names the material "glass_plane", you need to note this name down for step 3.
- **Step 2:** Model you object in the mcprep_meshSwap.blend file, or append it.
- **Step 3:** Rename your object to exactly match the previously noted material name. If you want to have a group swappable, then name the group to match the name above.  
  * So the MATERIAL name found in the 3D imported world should match the OBJECT name of the model in the meshswap file to work  
  * Note if both a group and an object have matching names, the script will prefer the group and meswap that over the object.  
- **Step 4:** Add necessary properties to special blocks as needed. See the meshSwap file included for examples, but the properties to add are:  
  * "variance": Objects with this property when meshswapped will have some x/y variance added. If the property is set to 1, it will also have (only negative) z variance. If it is set to 0, it will only have xy variance. For instance, tall_grass is given a value of 1 so some grass is shorter than others, but flowers are given a value of 0 so they always have the same height but still have some variance in placement.
  * "edgeFloat": objects like vines, ladders, and lillypads which float off the edge of other blocks.  
  * "torchlike": objects that can have rotations like a torch on a wall. Objects with this property will be determined to be either on top of a block or placed on the side of another block according to the mesh.
  * **Note:** there is no UI for adding properties to a group, so if you want to add a property to a group (say a torch which has a pre-animated light and particle system, as the included blend file does) you must go into the python consol and add the property like so:  <code>bpy.data.groups['groupName']['propertyName'] = 1</code>  (the value only matters for the variance property)
  * **Example:** <code>bpy.data.groups['torch']['torchlike'] = 1</code> will add the torchlike property to the torch group, allowing it to have correct rotaitons when meshSwapped in.



### Skin Swapping:
- **Purpose:** To provide quick and easy skin changing on rigs and characters already in your blender scene.
- **Step 1:** Select your rig (or rigs) that you want to change the skin for. It works best if you select all of the objects of your rig (e.g. head, torso, legs etc) but it will work even if you only selected the armature (in that case, results are only visible in rendered view)
- **Step 2:** Select a skin from the skin file list under the tool menu: 3D view > MCprep tab > Skin Swapper Panel > UI List of skins, left click to select/highlight a skin
  - *Don't see the skin you want?* Use the + button to add to the list, or use (download) skin from username below the UIList
- **Step 3:** Press the button that says "Apply [skin name]"
- **Step 4:** You're done! If the user interface appears to not update, be sure to **check rendered view**. Also note the default behavior is to make a *new* material in the event you have other copies or uses of the existing material. You can turn this off in the redo last menu.



### Mob Spawner:
- **Purpose:** To provide quick, one-click importing/linking of quality minecraft mob and player rigs in blender.
- **Step 0:** By default this is already done for you; make sure the mob spawner path is a directory with valid blend files setup for linking (addon preferences > MCprep). When installed, this path will already be setup and valid pointing to the included rigs with this release, as defined in the credits section above. This rigs are place in the addon's local directory provided by blender and will not be placed anywhere else on the user's machine.
- **Step 1:** Either press the "mob spawner" button in the MCprep panel, or go to the shift-a menu: armature > mob spawner > [mob name] to instantly append or link in a rig.
- **Step 2:** Check the redo last menu for additional settings, such as relocation of the rig, library linking, and even changing which rig to spawn. These are the following options:
  - mcmob_type: Change the mob spawned, e.g. from a creeper to a wolf
  - Relocation: Change where the spawned rig appears. 
    - Cursor (default): Place the rig at the cursor's location
    - Origin: Move the rig to the origin
    - Offset root: Move the rig to the origin, but offset the root bone to the cursor's location (note: doesn't work with all rigs correctly right now, will be improved in the future)
  - Library Link mob: If disabled, the group is appended (the groups is not kept so it can be appended multiple times), if enabled, the rig will be linked in and armatures auto-proxied.
    - Be careful! If the blend file moves, the libraries will likely get broken unless a custom rigs folder is used with a local-relative path.
  - Clear pose: clear to pose to rest. If false, the initial pose will be that found in the rig's source blend file. Note: some rigs have animations already setup, clear pose in the future will also automatically clear an action and remove the pre-animated figures.

*Mob Spawner Options*
![Meshswap options](/visuals/spawnOptions.png?raw=true)

To add your own rigs to the Mob Spawner:
- **Step 1:** Make your rig, or download one you want to use!
- **Step 2:** Make sure all elements of the rig, ie all armatures, body parts, and extra objects, are added to a single group inside your rig file. The name of this group is what will appear under the shift-a menu, and typically matches the name of the file if there is just one rig per blend file.
- **Step 3:** Optional but useful, rename the root bone of the rig to one of [MAIN, root, base], used for relocation. Additionally, make the armature for animation named [name].arma where [name] exactly matches the name of the group. This is used for auto-proxying of the armature and relocation methods.
- **Step 4:** Optional, if you have a custom script for the rig, save it as an external file whose name matches the blend file exactly, but with .py instead of .blend, place this in the same folder as the blend file.
- **Step 5:** Either from Blender Preferences > Addon > MCprep preferences panel > "Select/Install Mobs" or from the MCprep tab mob spawner menu "install [name]"" buttons, click to select the blend file and install it!
- **Alternative:** To specify a different, custom folder in a location of your choosing for mob spawning, simply change the "Rig Folder" path in the MCprep spawning tab (saved to blend file), or save a new default in the addon's preferences (becomes the default for all new blend scenes)
- Note: all groups inside installed blend files will appear for mob spawning. A large number of rigs will currently slow down the shift-A menu displaying the spawnable rigs (will be improved in the future). Note that after installing a blend file, you do *not* need to save user preferences to use it in future blender sessions.


*Sometimes you may need to reload a rig cache, click this button if the correct rigs aren't appearing*
![Reload rig cache](/visuals/reloadRigCache.png?raw=true)


### Meshswap block Spawner:
- **Purpose:** To provide quick, one-click importing of meshswap 3D blocks and groups.
- **Step 0:** By default this is already done for you; make sure the meshswap file path is a directory with valid blend files setup for appending (addon preferences > MCprep). When installed, this path will already be setup and valid pointing to the included blocks with this release.
- **Step 1:** Navigate to the spawner panel and select meshswap
- **Step 2:** Highlight the desired block
- **Step 3:** Press meshswap, and see the block placed in the scene
- **Step 4:** Modify redo last settings as needed (also accesible by pressing F6 after spawning). Options include:
  - Meshswap block: You can change here which block you wanted to add
  - Location: Set the location where the block is placed
  - Append layer: layer to append contents of the group to; default is layer 20, setting to 0 will use the currently active layer(s) as the layers for the group
  - Prep materials: run prep materials on the imported objects, particuarly useful if using cycles
  - Snapping dropdown: Snap the placed block to a rounded coordinate. Optional offset by 0.5 as well
  - Make real: Instance the groups so they are made real, thus allowing you to individually modify the objects within the group. Note: this may clear any pre-applied animation.


Known Bugs
======
- SOMETIMES UNDO (control/command z) MAY CRASH AFTER MESHSWAPPING, recommended to save before using to be safe but generally is fine.
- Currently meshwapassumes that the block size is 1x1x1, note that by default Mineways has a block size 0.1x0.1x0.1, please set it to 1m or 100cm on export or use the upscale function.
- Motion blur glitches on wind-swaying elements, e.g. grass: This is a bug with blender, where solidify plus the displacement modifiers and split edges modifiers can create bad motion blur effects. The easy fix is to remove split edges and let the grass be shaded smoothly instead.
- **Both mineways and jmc2obj oddities:**
  - Redstone items like repeaters, dust, and so forth generally don't swap properly, and is a much more difficult problem to solve.
  - Rails: for jmc2obj, all rails should at least be placed in the correct position, but not necessarily rotated correctly.
  - Some materials such as fire are pre-setup with animated image sequences (yay!), but blender cannot pack image sequences into a blend file. If animated textures go missing (e.g. after moving a blend file around), reconnect them back to the according folder/file, such as /textures/fire/fire_0001.png. Note this should not be a problem if the default meshwap path/file is used, provided the addon is not uninstalled.
  - Doors are not meshswapped into the correct location, manual fixing may be required.
- **Mineways specific meshswap oddities:**
  - Mineways, unlike jmc2obj, replaces the face of a solid block with the object attached to it. For example, ladders and redstone dust when meshswapped will leave a hole in the block they were attached to. There is essentially nothing I can do about that.
  - In Mineways, many blocks simply cannot be meshswapped because of the way the exporter will group multiple objects (for example, all the flowers and double tall grass) into one material. For the time being, there is nothing I can do to resolve this.
  - lilypads end up rotated and in block next to where they should be


Future Plans
======
Future deveploment plans are now recorded and updated as milestones and enhancement issues on github.


Additional Help
======

If you have troubles getting this addon to work, please contact me at support@TheDuckCow.com or [on twitter](https://twitter.com/TheDuckCow), and I will do my best to respond promptly to your questions. This addon is still heavily under construction, so check back for updates (you can reference the version number and take last modified). Your feedback helps stabilize the addon and make it work better for everyone else!

Moo-Ack!
