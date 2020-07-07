# Urufu's Big Sur Icons
![Airdrop](https://github.com/MisutaaUrufu/Urufus-bigSurIcons/raw/master/Iconsets/AirDrop-1016.iconset/icon_64x64.png)![Twitter](https://github.com/MisutaaUrufu/Urufus-bigSurIcons/raw/master/Iconsets/Twitter-1016.iconset/icon_64x64.png)![Discord](https://github.com/MisutaaUrufu/Urufus-bigSurIcons/raw/master/Iconsets/Discord-1016.iconset/icon_64x64.png)![Telegram](https://github.com/MisutaaUrufu/Urufus-bigSurIcons/raw/master/Iconsets/Telegram-1016.iconset/icon_64x64.png)![Parallels](https://github.com/MisutaaUrufu/Urufus-bigSurIcons/raw/master/Iconsets/Parallels-1016.iconset/icon_64x64.png)![Windows VM](https://github.com/MisutaaUrufu/Urufus-bigSurIcons/raw/master/Iconsets/Windows-1016.iconset/icon_64x64.png)<br/>
Custom macOS 11 Big Sur icon collection for the following applications:

* Twitter
* Parallels
* Discord
* Telegram
* Windows (Any VM)
* AirDrop (Finder)

## Icons
Contains the relevant premade Apple `ICNS` icon files, ready for download. [\[&nbsp;Preview↗&#xFE0E;&nbsp;\]](https://github.com/MisutaaUrufu/Urufus-bigSurIcons/blob/master/Preview.md)

## Iconsets
Contains the deconstructed ICNS files, as Apple `iconset` folders, ready for build, or modification.

#### To Build
Using the Apple **`iconutil(1)`** terminal application, build the desired icon(s) with the following syntax:
```zsh
iconutil -c ICNS -o [path to output]/[filename].icns [path to iconset]/[iconset] 
```
Example:
```zsh
iconutil -c ICNS -o ~/Pictures/Twitter-1016.icns ~/Downloads/Urufus-bigSurIcons/Iconsets/Twitter-1016.iconset
```

#### To Modify
1. Open the desired `iconset` you wish to modify
2. Remove all files, *except* **`icon_512x512.png`**
3. Open **`icon_512x512.png`** in your desired photo editor, and apply the relevant changes
4. Export *downscaled* versions of this file using the following syntax:<br/>
**`icon_[width]x[height].png`**\^
5. Duplicate all files within the directory
6. Rename all **duplicates** using the following syntax:<br/>
`icon_[width/2]x[height/2]@2.png`\^
7. Follow instructions under header [**To Build**](#to-build).

#### \^Naming Convention Cheat Sheet
##### Standard Sizes
`512x512`&nbsp;&nbsp;->&nbsp;&nbsp;`icon_512x512.png`<br/>
`256x256`&nbsp;&nbsp;->&nbsp;&nbsp;`icon_256x256.png`<br/>
`128x128`&nbsp;&nbsp;->&nbsp;&nbsp;`icon_128x128.png`<br/>
`64x64`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;->&nbsp;&nbsp;`icon_64x64.png`<br/>
`32x32`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;->&nbsp;&nbsp;`icon_32x32.png`<br/>

##### Scaled Sizes
`512x512`&nbsp;&nbsp;->&nbsp;&nbsp;**`icon_256x256@2.png`**<br/>
`256x256`&nbsp;&nbsp;->&nbsp;&nbsp;**`icon_128x128@2.png`**<br/>
`128x128`&nbsp;&nbsp;->&nbsp;&nbsp;**`icon_64x64@2.png`**<br/>
`64x64`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;->&nbsp;&nbsp;**`icon_32x32@2.png`**<br/>
`32x32`&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;->&nbsp;&nbsp;**`icon_16x16@2.png`**<br/>
