+  Minecraft Modpack Template +

- Overview -
A small template project for minecraft modpacks, meant to make it easier to create modpacks without having to use the curse launcher or external tools/launchers

-manifest.json
this is where you place mod id and file id so launcher can automatically download the mod required by the modpack

* the project id can be found on the sidebar of all mods found in curseforge

* the file id is found in the url of the download 
Example: https://www.curseforge.com/minecraft/mc-mods/the-one-probe/files/2667280
The file id is: 2667280

-/overrides/configs
this is where all the customised mod configs go, 
I recomend using a symbolic link to your minecraft instnace to keep the modpack configs up to day

-/overrides/scripts
this is where craftweaker scripts go, if required, 
I recomended using symbloic link to your minecraft instance to keep your scripts up to date

-/overrides/mods
this folder is used to put mods that are not found on curseforge, just place the jar files in here 

-/docs
I use this folder for any documents for you modpack, perhapes some tutorials if you do not use a quest book, lore, whatever

-modlist.html
a simple html webpage that I use to keep track of mods in my modpack, 
also contains direct download links to the mods in case if cursforge disables modpack downloading for some reason as well as other info
such as version of the mod and any depencitys it might have