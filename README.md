[![Repository size](https://img.shields.io/github/repo-size/FredHappyface/Mario64_720p.svg?style=for-the-badge)](../../)
[![Issues](https://img.shields.io/github/issues/FredHappyface/Mario64_720p.svg?style=for-the-badge)](../../issues)
[![License](https://img.shields.io/github/license/FredHappyface/Mario64_720p.svg?style=for-the-badge)](/LICENSE.md)
[![Commit activity](https://img.shields.io/github/commit-activity/m/FredHappyface/Mario64_720p.svg?style=for-the-badge)](../../commits/master)
[![Last commit](https://img.shields.io/github/last-commit/FredHappyface/Mario64_720p.svg?style=for-the-badge)](../../commits/master)
[![Downloads](https://img.shields.io/github/downloads/FredHappyface/Mario64_720p/total.svg?style=for-the-badge)](../../releases)

# Mario64_720p

<img src="readme-assets/icons/name.png" alt="Project Icon" width="750">


## Credits
Credit to GhostlyDark for this awesome texture pack. Get the UHD version at
https://evilgames.eu/texture-packs/sm64-reloaded.htm.


## Comparison

|Texture Size|Texture Scale|Resolution |Size |URL|
|:--         |------------:|:---------:|----:|:--|
|4k          |           x8|1440p-4k   |6.82G|https://evilgames.eu/texture-packs/sm64-reloaded.htm|
|1440p       |           x4| 720p-1440p|83.7M|See Download Below|
|1440pPNG    |           x4| 720p-1440p|21.9M|See Download Below|
|1440pPC     |           x4| 720p-1440p|60.1M|See Download Below|
|1440pGlideN64|          x4| 720p-1440p|57.4M|See Download Below|
|720p        |           x2|native-720p|64.1M|See Download Below|
|720pPNG     |           x2|native-720p|7.03M|See Download Below|


Note that the non-png versions have a larger file size as they use the 4k HUD
(downscaling the HUD resulted in misbehaving textures)


## Installation


### Dolphin

#### All

First things first, configure Dolphin to use textures

- Options (Menu Bar) > Graphics Settings
- Advanced (Tab)
- (Utility) Load Custom Textures + (Utility - Optional) Prefetch Custom Textures

#### 4k

Download the pack from one of the links above

- DDS or PNG pack goes to: %username%/Documents/Dolphin Emulator/Load/Textures
- Graphics ⇢ Advanced: Load Custom Textures
- Graphics ⇢ Advanced: Prefetch Custom Textures (2 GB RAM DDS / 6 GB RAM PNG)

#### 720p/1440p - DDS

The best way to do this is probably to download `Mario64_[720p/1440p].7z` from
the releases

1. Download `Mario64_[720p/1440p].7z` from the releases
2. Copy the `Mario64_[720p/1440p]` Directory to
   `..\Dolphin Emulator\Load\Textures`
3. Launch Dolphin

#### 720p/1440p - PNG

Tested to title screen only. Best to use dds version if at all possible.

The best way to do this is probably to download `Mario64_[720p/1440p]PNG.7z`
from the releases

1. Download `Mario64_[720p/1440p]PNG.7z` from the releases
2. Copy the `Mario64_[720p/1440p]PNG` Directory to
   `..\Dolphin Emulator\Load\Textures`
3. Launch Dolphin


### GlideN64

#### 4k

See https://evilgames.eu/texture-packs/sm64-reloaded.htm for more info

#### 1440p - PNG

1. Clone/ Download the repository (see below for step-by-step instructions)
2. The textures are under `Mario64_1440pPC`

**Out Now - Follow Instructions Above**

#### 720p/1440p HTS -- 720p PNG

**Not Planned**

### PC

#### 4k

Download the pack from one of the links above

Use sm64pcbuilder2 to compile sm64ex with External Data and a DirectX backend
of your choice. Navigate to the folder res, unpack base.zip and copy all PNG
textures into the gfx directory. You need at least 6 GB of free RAM.

#### 1440p - PNG

1. Clone/ Download the repository (see below for step-by-step instructions)
2. The textures are under `Mario64_1440pPC`

**Out Now - Follow Instructions Above**

#### 720p - PNG

**Not Planned**

## Download
### Clone
#### Using The Command Line
1. Press the Clone or download button in the top right
2. Copy the URL (link)
3. Open the command line and change directory to where you wish to
clone to
4. Type 'git clone' followed by URL in step 2
```bash
$ git clone https://github.com/FredHappyface/Mario64_720p
```

More information can be found at
<https://help.github.com/en/articles/cloning-a-repository>

#### Using GitHub Desktop
1. Press the Clone or download button in the top right
2. Click open in desktop
3. Choose the path for where you want and click Clone

More information can be found at
<https://help.github.com/en/desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop>

### Download Zip File

1. Download this GitHub repository
2. Extract the zip archive
3. Copy/ move to the desired location

## Community Files
### Licence
All Rights Reserved License
Copyright (c) Admentus
(See the [LICENSE](/LICENSE.md) for more information.)

### Changelog
See the [Changelog](/CHANGELOG.md) for more information.

### Code of Conduct
Online communities include people from many backgrounds. The *Project*
contributors are committed to providing a friendly, safe and welcoming
environment for all. Please see the
[Code of Conduct](https://github.com/FredHappyface/.github/blob/master/CODE_OF_CONDUCT.md)
 for more information.

### Contributing
Contributions are welcome, please see the
[Contributing Guidelines](https://github.com/FredHappyface/.github/blob/master/CONTRIBUTING.md)
for more information.

### Security
Thank you for improving the security of the project, please see the
[Security Policy](https://github.com/FredHappyface/.github/blob/master/SECURITY.md)
for more information.

### Support
Thank you for using this project, I hope it is of use to you. Please be aware that
those involved with the project often do so for fun along with other commitments
(such as work, family, etc). Please see the
[Support Policy](https://github.com/FredHappyface/.github/blob/master/SUPPORT.md)
for more information.

### Rationale
The rationale acts as a guide to various processes regarding projects such as
the versioning scheme and the programming styles used. Please see the
[Rationale](https://github.com/FredHappyface/.github/blob/master/RATIONALE.md)
for more information.
