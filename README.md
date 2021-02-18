# StardewValley-NPCMapLocations-Addon
globals.json and customlocations.json files need to be fixed in the NPCMapLocations mod folder if you intend on playing with more mods

I installed a bunch of mods and then fixed these files to work with all these other mods and this github repository holds the result


Installation:

    1.replace the globals.json in Mods/NPCMapLocations/config with the provided one
        you'll have to fix your settings because this will reset them
    2.edit the provided customlocations.json 
        you can skip this step
        this can be done in notepad or notepad++, or whatever text editor
        locate the json file for each of the mods you have in the tooltips folder which are named accordingly
        copy everything in the first file 
        paste it between the {braces} after "CustomMapTooltips" in the customlocations.json file
    3.replace the customlocations.json file in the NPCMapLocations/maps/* with that file
        The name of the folder changes depending on which mods you're using,
        The folder name appears to be a comma seperated list of some mods,
        NPCMapLocations/maps/Rafseazz.RSVCP, flashShifter.stardewValleyExpandedCP, flashshifter.immersivFarm2Remastered/customlocations.json
        is the folder where I found the customlocations.json file to edit, which isn't necessarily where you will find yours
        updating the wrong customlocations.json file doesn't do anything, so go ahead and just update them all

You can skip step 2 if you need. It is only there to make the map display tooltips for locations when you highlight different parts of the map. Since I don't want it to show tooltips for mods that I don't have I didn't include this by default. NPCMapLocations ignores the data for mods you don't have in the other cases
        
    
These mods may not be fully completed as I have only implemented the locations which I have reached in my playthough or found other people's implementations for.

Because Stardew Valley Expanded is used as a base, some locations may need to be adjusted if you don't have it installed
    
mods that have tooltips:
 
    -Stardew Valley Expanded
    -Ridgeside Village

currently implemented mods which change the map:

    -Walk to the Desert
    -Garden Village
    -East Scarpe
    -The Stray Catfe
    -Juliet and Jessie Joja Clerks
    -Lunna - Astray in Stardew Valley
    -Mermaid Island
    -Custom NPC - Riley

currently implemented NPC Mods:

    -Jade NPC
    -Beatrice NPC
    
