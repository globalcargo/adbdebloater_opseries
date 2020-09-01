<img src="https://github.com/DevilDipan/adbdebloater_opseries/blob/master/logo.jpg" width="500" /><br>
# OOS/H2OS Debloater
This is a Debloater for Oxygen OS. Though it doesn't come with many bloats there are still bloats that could be removed to increase performance and battery life.

This is a fork from the magicalmammal's excellent work for the OP7 series. I am using this fork to curate my personal setup for the OP Nord (EU rom). I have tried to document the various apps and commented out (using a leading "#" suitable for bash for Linux) those I am not removing. My setup may not be right for you or even break your device, for which I take no responsibility. So please keep that in mind when using this work. 

###### Though the performance improvement is not visible the same to me battery life increased by 30+%.

## XDA
###### The xda page is [here](https://forum.xda-developers.com/oneplus-7/how-to/debloat-oxygen-os-debloater-t4009133)

## License
### This is under MIT License.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/DevilDipan/Wiki-Bot/blob/master/LICENSE)

## Requirments
1. Windows/MAC/Linux
2. ADB [Working!!!]
3. OP7/7T/8/7Pro/Nord/Lite

## Instructions
1. Connect the phone using ADB.
2. Open Command Prompt/PowerShell/Shell/Terminal
3. Run ADB -
```shell
ADB devices
```
4. Type
```shell
ADB shell
```
5. Then use any one of [this](https://github.com/DevilDipan/adbdebloater_opseries/releases)
6. If you don't want some apps to be removed remove respective lines.
7. Done Enjoy!!!

## Scripts
1. Debloaters
* With [Uninstall Method](https://github.com/DevilDipan/adbdebloater_opseries/blob/master/debloater.txt) **(Safe)**
* With [Disable Method](https://github.com/DevilDipan/adbdebloater_opseries/blob/master/debloater_enable.txt) **(Recommended)**
2. Optional Scripts
* With [Uninstall Method](https://github.com/DevilDipan/adbdebloater_opseries/blob/master/optional_debloats.txt) **(Highly Risky)**
* With [Disable Method](https://github.com/DevilDipan/adbdebloater_opseries/blob/master/optional_debloatsenable.txt) **(Recommended)**
3. Overlay Script (For paranoid people)
* With [Uninstall Method](https://github.com/DevilDipan/adbdebloater_opseries/blob/master/overlay.txt) **(Risky)**
* With [Disable Method](https://github.com/DevilDipan/adbdebloater_opseries/blob/master/overlay_enable.txt) **(Recommended)**

### What if I want any app back?
#### **Answer**:- Easy just install it from Play store or Install its Apk file.

### What if I want to remove the deep sleep script?
#### **Answer**:- Reboot

## Testing
1. [Me](https://forum.xda-developers.com/member.php?u=9670192) on OP7 on android pie/10 beta & EU.
2. Nicole on OP7 Pro on android 10 stable.
3. [haris_94](https://forum.xda-developers.com/member.php?u=9931329) on OP7 on android stable.
4. [Croize](https://forum.xda-developers.com/member.php?u=5758653) on OP7T on android stable.
I am using this Debloater for a year now and it didn't give me any issues on stable variant. <br>

Also if you want to be updated please post it or write it to me.

## Versions
**v1** <br>
Basic User and System Bloatware Removal <br>
Deep Sleep Script <br>

**v2** <br>
Chrome Removed from the script <br>
Oneplus Gallery Removed from the script <br>
Oneplus Account Removed from the script <br>

**v3** <br>
Amazon bloatware <br>
Oneplus Icons Packs <br>
One plus community apps <br>

###### Added enabling method
```
pm enable <package_to_enable>
```
**v4** <br>
Removed the failures commands as posted by [haris_94](https://forum.xda-developers.com/member.php?u=9931329) <br>

**v5** <br>
Added a few more optional scripts <br>

**v6** <br>
Added a few more optional scripts <br>

**v7** <br>
Removed deep sleep scripts from the script <br>

**v8** <br>
Added with optional debloat enable <br>

**v9** <br>
A lot of things <br>

**v10** <br>
Added Overlay script <br>
A lot of things <br>

**v11** <br>
A lot of things <br>

## For modifying and posting code
Fork this repo before you modify it

## Thanks for Suggestions<br>
[haris_94](https://forum.xda-developers.com/member.php?u=9931329)<br>
[Kinto](https://forum.xda-developers.com/member.php?u=1755710)<br>
[dude_abided](https://forum.xda-developers.com/member.php?u=10663973)<br>
[Illuminatus_](https://forum.xda-developers.com/member.php?u=4391705)<br>
[RainGater](https://forum.xda-developers.com/member.php?u=5379867)

### Git Guardian Active
