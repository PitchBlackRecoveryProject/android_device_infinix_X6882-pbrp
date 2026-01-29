# PBRP Tree For Infinix HOT 50 4G (X6882)

# Checks
Blocking checks
- [✔] Correct screen/recovery size
- [✔] Working Touch, screen
- [✔] Backup to internal/microSD
- [✔] Restore from internal/microSD
- [✔] reboot to system
- [✔] ADB

Medium checks
- [✔] update.zip sideload
- [?] UI colors (red/blue inversions)
- [✔] Screen goes off and on
- [✔] F2FS/EXT4 Support, exFAT/NTFS where supported
- [✔] all important partitions listed in mount/backup lists
- [✔] backup/restore to/from external storage
- [✔] backup/restore to/from adb 
- [✔] decrypt /data
- [?] Correct date

Minor checks
- [✔] MTP export
- [✔] reboot to bootloader
- [✔] reboot to recovery
- [✔] poweroff
- [✔] battery level
- [ x ] temperature
- [✔] encrypted backups
- [✔] input devices via USB (USB-OTG) - keyboard and mouse and storage
- [✔] USB mass storage export
- [✔] set brightness
- [ X ] vibrate
- [✔] screenshot
- [✔] partition SD card
- [✔] Fastbootd

# Clone (example)
    git clone https://github.com/XTENSEI/android_device_infinix-X6882-pbrp.git -b android-12.1 device/infinix/X6882

# Build
    export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch pb_X6882-eng; m pbrp
