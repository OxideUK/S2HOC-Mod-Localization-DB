# Stalker 2 Mod Localization Database

Anyone is free to access the files stored on MLDb, but edit access is restricted to active modders - Get in touch if you would like access

## Uploading Localization Files

Upload your files in .json format to the Mod Localization folder:
- Use the same naming format each time (e.g. OXA_EN.json or MutantLoot_UA.json)
- Only keep the latest version of your localization in the Mod Localization folder
- Do not overwrite vanilla localization

## Creating Localization Files

1. Download S2HOC Multi Localization Utility (S2HOCMM) and extract it - https://www.nexusmods.com/stalker2heartofchornobyl/mods/540
2. Download the contents of Base Localization to your S2HOCMM/JSONs folder
3. Download the contents of Mod Localization to the same folder
4. Launch S2HOCMM and go to the Localization Merger tab
5. Click 'Add', add all of the files in the JSONs folder, then click 'Merge'
6. Go to the Packer tab, click 'Pack', and add the contents of your Merged folder
7. Your finished localization will be in ModOutput/Pak

If you are familiar with GitHub, you can clone the repository to skip downloading the files seperately.

If you require a version without Real Weapon Names, you can use the files in Vanilla Localization rather than those in Base Localization.

## Naming Localization Files

In order to ensure users know which localization file is the most up to date, use the following naming convention:

  MLDb_Localization_\<MM>\<DD>\.pak
  - \<MM> is the month
  - \<DD> is the day

e.g. MLDb_Localization_0131 would be localization created on Jan' 31
Use the prefix MLDb_Vanilla_ if you aren't using Real Weapon Names.

## Uploading Localization Files

Once you've completed packing and renaming your localization, you can include it in your mod and upload it to the Pre-Packaged Localization folder. 
It is recommended that you keep the same naming convention when adding localization to your mod; this naming system ensures that the most recently produced localization will be loaded, regardless of how many the user may have in their mods folder.
