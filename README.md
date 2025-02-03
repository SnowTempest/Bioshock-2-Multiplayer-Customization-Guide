<img src="ImagesFiles/Bioshock2Startup.png" alt="Bioshock 2 Multiplayer Logo" width="700"/>

<br>

# Splicer Customization

This page will explain what custom character customizations are possible in Bioshock 2 Multiplayer. 

## Setup

1. Go to `AppData\Roaming\Bioshock2Steam`
2. Look for a file named similarily to `User_01234567890123456.ini`. Note that the numbers are based on your Steam Community id.
3. Open this file and scroll down until you see the values.

        UserProfileCharacterId=
        UserProfileMaskIndex=
        UserProfileMeleeWeaponIndex=
        UserProfileRebirthCount=

## Details

### UserProfileCharacterId
```
This is the character id index of your current character.
```
### UserProfileMaskIndex
```
This is the mask id index of your current character.
```
### UserProfileMeleeWeaponIndex
```
This is the melee id index of your current character.
```
### UserProfileRebirthCount
```
This value was originally meant to count the number of rebirths on your profile. However, due to a bug in the game's code, the `UserProfileMeleeWeaponIndex` overwrites this value. Both values need to be the same in order for your melee to save properly.
```

## Instructions
1. Now that you know what values to modify, you can change them to get a character, mask, and melee combination of your choice.
2. Scroll down below and click on 'START' to open a new page that brings you to a chart that explains the ids for each value.

## Links

[START](SplicerCustomization.md)