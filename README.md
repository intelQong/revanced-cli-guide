# revanced cli guide

## Things we need to download before patching
1. Openjdk `sudo pacman -S jdk-openjdk` / [Java](https://www.oracle.com/bd/java/technologies/downloads/)
2. [revanced patches](https://github.com/ReVanced/revanced-patches/releases) (rename the rvp file as `patches.rvp`)
3. [revanced cli](https://github.com/ReVanced/revanced-cli/releases)(rename the jar file as `revanced-cli.jar`)
4. Download the targeted apk from [APKmirror](https://www.apkmirror.com/) (rename that apk to `input.apk`

## Patch an APK (Download apk version not bundle)
1. `java -jar revanced-cli.jar patch -p patches.rvp input.apk`

_Move the `input-patched.apk` to your android phone and install 🎉 _
   
