# ReSpeaker Core v2 debian image

## 20180730

### News
    - Update linux kernel to 4.4.138-respeaker-r0
    - Pulseaudio update to 12.2, bluetooth auido noise disappeared.
    - Use seeed.respeaker.io as respeaker debian apt source
    - All disk partitions switch to the MBR partition. So BOOT partition can auto mount in host PC.
    - set rockchp's xf86-video-armsoc as default X.org graphics driver.

### TODO
    - support lxqt desktop 2D/3D accelerate. rockchp's xf86-video-armsoc looks like a semi-finished product, This feature may not be supported in the future
    - support hardware video encode/decode, I think it's working, but I don't have any demos.
    - optimize x11vnc,current software eat too much cpu.
    - support linux kernel overlayfs


## 20180610

Note: This version lack of flasher image

### News
    - Update linux kernel to 4.4.132-respeaker-r5
    - fix speaker volume always zero when system do restart

### TODO
    - support lxqt desktop 2D/3D accelerate
    - optimize x11vnc,current software eat too much cpu.
    - support hardware video encode/decode
    - support linux kernel overlayfs
    - BOOT disk part cannt auto mount in host PC 
    - bluetooth auido maybe has noise on some device
    - lack of flasher image


## 20180606

Note: This version is not recommended to use, have been deleted.

### News
    - Update linux kernel to 4.4.126-respeaker-r2
    - system support  Rockchip DMC(Dynamic Memory Controller) 
    - fix led light up randomly at power on
    - fix hdmi can’t hot-plug
    - update mraa and upm, to support more Grove sensors
    - add os-config(fork the armbian-config) script
    - bluetooth support bcm43438a1 and bcm43438a0 chip together
    - Improves system fluency
### TODO
    - support lxqt desktop 2D/3D accelerate
    - optimize x11vnc,current software eat too much cpu.
    - support hardware video encode/decode
    - support linux kernel overlayfs
    - BOOT disk part cannt auto mount in host PC
    - bluetooth auido maybe has noise on some device
    - speaker volume will be zero when system do restart
