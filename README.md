<<<<<<< HEAD
# CM10-Jellybean for Kindle Fire HD
Slightly based on Hashcode's Nook Tablet JB repo
Slightly based on VeryGreen's Kindle Fire HD 8.9 Tablet JB repo
## Info

|||
|-----------------------------------:|:--------------------------|
|**Discussion thread**: | http://forum.xda-developers.com/showthread.php?t=2029826
|**IRC Channel**:   	| #kindlefire-dev on freenode


## Building 

### Initialize
[Get started](https://github.com/KFire-Android/android_local_manifest/wiki)

### Download sources

```bash
mkdir android/system
cd android/system
curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/repo
chmod a+x ~/repo
repo init -u git://github.com/CyanogenMod/android.git -b jellybean

wget -O .repo/local_manifest.xml https://github.com/jb2kred/android_manifests/raw/master/bowser-jb/local_manifest.xml

repo sync -j16
```

### Compile

```bash
. build/envsetup.sh
lunch cm_bowser-userdebug
. vendor/cm/get-prebuilts
mka bacon
=======
>>>>>>> 4c660b7637b861144051022c1f96dfa8d7918971
