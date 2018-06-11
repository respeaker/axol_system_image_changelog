# ReSpeaker Core v2 debian image

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
    
### Known bugs/problems:
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
    
### Known bugs/problems:
    - BOOT disk part cannt auto mount in host PC
    - bluetooth auido maybe has noise on some device
    - speaker volume will be zero when system do restart
