# Nomad 1.0 Modding Quick Start

Will try to keep things short and easy to follow.
Mostly for Windows PC but you can also do it from the headset if you have the right file manager installed.

[Looking for compatible mods](#looking-for-compatible-mods)

## Prerequisites

- v1.0+ of Blade & Sorcery: Nomad installed and launched at least once to generate the folder structure
- A nexusmods account, to download the mods
- Any data capable usb cable to connect your Quest headset to your PC, to transfer mods over

## Looking for compatible mods

Navigate to [nexusmods](https://www.nexusmods.com/games/bladeandsorcerynomad/mods?sort=updatedAt&title=1.0)
- Link has been presorted by last updated and searching for titles with "1.0" in them to make things easier.
  - Not all 1.0+ compatible mods may have "1.0" in the title

Once you found a mod you would like to get, make sure the title, description or file download pages mentions it is for nomad 1.0+.
Otherwise, the mod may not load or work properly. If not explicitly stated, stay away from non 1.0 mods. (U12, U11, U10 etc)
Double check posts and bugs tab to see if anyone else has tried it on 1.0+ or download and test them yourself.
> [AI Healthbar U1.0 (Nomad)](https://www.nexusmods.com/bladeandsorcerynomad/mods/4418) - Compatible
>
> [Choking for 1.0](https://www.nexusmods.com/bladeandsorcerynomad/mods/3870) - Compatible
>
> [The Force Overhaul](https://www.nexusmods.com/bladeandsorcerynomad/mods/4853?tab=description) - Might be compatible, need to find out yourself
>
> [U12 Super speed mod](https://www.nexusmods.com/bladeandsorcerynomad/mods/3827) - Not compatible, unless they have an updated version for download

## Downloading and extracting the mods

Hit the "Manual" download button near the top right and select slow/fast download accordingly.
![image](https://github.com/user-attachments/assets/8c4cb40d-62a9-4c05-8c4d-ceaec91dab10)

Once downloaded, move all your mod zips into one folder for easy management, [modzip] in this example.
Create another folder for the extracted mods, [extracted] in this example.
Extract each mod.
  - If you have 7-Zip, select all the zip files, Right Click, 7-Zip, Extract Here.
    - You will end up with the following folder structure:
      - [modzip] folder
        - [modName] folder
          - a bunch of json, asset files and/or folders

       
  - If you extract via the built in windows explorer Right Click, Extract All...
    - You will end up with an additional folder:
      - [modzip] folder
        - [zipName] folder
          - [modName] folder
            - a bunch of json, asset files and/or folders
         
We are only interested in the [modName] folders that contains the mod files we need. 
So move all [modName] folders into the [extracted] folder.

## Transferring the mods onto your headset

Now it is time to transfer all the mods over to the headset.
Connect your headset to your PC. There will be a notification on your headset for file access. Click on it and hit Allow.
You should now be able to see you headset on windows explorer.
Navigate to Headset > Internal Storage > Android > data > com.Warpfrog.BladeAndSorcery > files > Mods. (you might have to launch the game once to generate the folder structure)
Inside the Mods folder should be a Readme.txt.
This is where we will be transferring all our [modName] folders to and you will end up with:
  - Mods folder
    - Readme.txt
    - [modName] folder
    - [modName] folder
    - [modName] folder
    - etc and so on
![image](https://github.com/user-attachments/assets/20426e2d-4158-48ed-9f5f-c248564b7e19)

Once transferred, you can unplug your headset and launch the game.

## Allow loading of mods

Once you have booted into Nomad, when you get prompted to, allow the loading of mods so that you can actually use them.
When you are in Crysal Hunt or Sandbox mode, check your Menu > Mods page to see the loaded mods.
Some mods work right away while others require you to look for them or spawn them in.

#End
