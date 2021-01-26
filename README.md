<img src="https://github.com/DevilDipan/adbdebloater_opseries/blob/master/logo.jpg" width="500" /><br>
# OOS/H2OS Debloater
This is a Debloater for Oxygen OS. Though it doesn't come with many bloats there are still bloats that could be removed to increase performance and battery life.

This is a fork from the magicalmammal's excellent work that started with the OP7 series. I am using this fork to curate my personal setup for the OP Nord (EU rom). I have tried to document the various apps and commented out (using a leading "#" suitable for bash for Linux) those I am not removing. My setup may not be right for you or even break your device, for which I take no responsibility. So please keep that in mind when using this work.

Also, some packages may not be installed on some roms. So you will see the relevant uninstall fail.

You can find the original releases without my customization [here](https://github.com/DevilDipan/adbdebloater_opseries/releases)

###### Though the performance improvement is not visible the same to me battery life increased by 30+%.

## XDA
###### The xda page for the original project is [here](https://forum.xda-developers.com/oneplus-7/how-to/debloat-oxygen-os-debloater-t4009133)

## License
### This is under MIT License.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/DevilDipan/Wiki-Bot/blob/master/LICENSE)

## Requirments
1. Linux
2. ADB [Working!!!]
3. OP Nord

## Instructions
1. Connect the phone using ADB.
2. Open Command Shell/Terminal
3. Run ADB -
```shell
ADB devices
```
4. Type
```shell
ADB shell
```
5. Use the files from this repo by pasting them into the prompt. Changes will be executed line by line. "#" prefixed lines will be treated as comments and ignored.
For optiona_debloats copy and paste the relevant line item.
6. If you don't want some apps to be removed remove respective lines or comment them out if your shell/script supports it.
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
4. Facebook cleanup (removes facebook services introduced on OP series 8 phones and the Nord)
* With [Uninstall Method](https://github.com/globalcargo/adbdebloater_opseries/blob/master/facebook_deletes) **(Riskier than disabling)**

### What if I want any app back?
#### **Answer**:- Easy just install it from Play store or Install its Apk file.

### What if I want to remove the deep sleep script?
#### **Answer**:- Reboot

## Testing
Me (globalcargo) OP Nord EU release


## For modifying and posting code
Fork this repo before you modify it

## Thanks for sharing your great work<br>

[themagicalmammal](https://forum.xda-developers.com/member.php?u=9670192)<br>
[haris_94](https://forum.xda-developers.com/member.php?u=9931329)<br>
[Croize](https://forum.xda-developers.com/member.php?u=5758653)<br>
[haris_94](https://forum.xda-developers.com/member.php?u=9931329)<br>
[Kinto](https://forum.xda-developers.com/member.php?u=1755710)<br>
[dude_abided](https://forum.xda-developers.com/member.php?u=10663973)<br>
[Illuminatus_](https://forum.xda-developers.com/member.php?u=4391705)<br>
[RainGater](https://forum.xda-developers.com/member.php?u=5379867)

### Git Guardian Active
