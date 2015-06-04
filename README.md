Blazing Rom Github
===================

Setting up Build Environment
---------------------------
- Official build environment as per Google and AOSP [Android source page](http://source.android.com/source/index.html)
- XDA user guides [Ubuntu 14.04 Trusty LTS](http://forum.xda-developers.com/showthread.php?t=2639611) , [Ubuntu 14.10 Utopic](http://forum.xda-developers.com/chef-central/android/howto-setup-ubuntu-14-10-utopic-unicorn-t2862442)
- [Arch Linux](https://wiki.archlinux.org/index.php/android#Building_Android)

Initializing the Source
-----------------------
(Assuming you have a valid build environment setup)
- mkdir blaze
- cd ~/blaze
- repo init -u https://github.com/Blazing-Rom/platform_manifest.git -b layers

Sync the Source
---------------
- repo sync -jx (x being the number of CPU jobs)

Getting Ready to Build
----------------------
- . build/envsetup.sh
- breakfast device
- brunch device


Credits
-------
- Google for AOSP
- SAOSP-L
- Rascarlo and RastaPop
- Altaf-Mahdi and Euphoria-OS
- DariosF and Purity ROM
- Paranoid Android (AOSPA)
- AOSPAL
- CyanogenMod
- Dirty Unicorns
- LiquidSmooth
- AOKP
- SlimROMS
- Project D.I.S.C.O. Team
- PartimusPrime for bootanimations
- OmniROM
- Lichti1901 and Terminus
- Sykopompos
- Team Horizon and XenonHD
- Chet and OptiPop
- VanirAOSP
- PurifiedROM
- The-Ancile-Project
- AOD-Lollibeans
- Android Open Development
- BitSyko Development
- Others we may have missed
