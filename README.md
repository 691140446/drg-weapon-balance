# drg-weapon-balance
A list of public mods to balance the base weapons, gear modifications and overclocks in Deep Rock Galactic.

## Content
Every weapon covered will include the following:

### A .pak balance mod
The mods are ready for use and don’t need a mod loader. To use them, just put the pak files in your ```\Steam\steamapps\common\Deep Rock Galactic\FSD\Content\Paks``` folder.
Only the host need to have the mod installed, it will apply for the clients as well. If the client doesn’t have the mod installed, it will apply, but the value displayed will be the vanilla value instead of the modded values.

### A .md readme file
This file should list any change made for that weapon, its gear modifications and overclocks.
For each property changed, you should list:
* the class name
* the property name
* (optional: the value’s type if it isn’t float)
* its default value
* the modded value
* the value offset (decimal)
* the path of the modded file (Starting by 'FSD' and without the file extension)

### A Packer Zipped folder
This folder will include all uncooked files, this is basically the mod in its pre-packed form. It should contain the modded files and the necessary folders only. The goal of this folder is to save time to tweak value when working on the next version of the balance mod.
