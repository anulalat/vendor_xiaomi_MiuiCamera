# MiuiCamera
## Getting Started :
### Cloning :
• Clone this repo in vendor/xiaomi/miuicamera in your working directory by :
```
git clone https://github.com/SonalSingh18/vendor_xiaomi_miuicamera.git -b thirteen vendor/xiaomi/miuicamera
```
### Changes Required :
• You will need following changes in your device tree:

• Makefile changes
- [Inherit MiuiCamera](https://github.com/SonalSingh18/android_device_xiaomi_sm6250-common/commit/6e5ced47138b7299bc5a9cdf9b631b48101cdb08)

• Props Changes
- [Add miuicamera to aux packagelist](https://github.com/SonalSingh18/android_device_xiaomi_sm6250-common/commit/5311c2126d84a3f54311850f8bf0471f288158d6)
- [Skip stream size check for miuicamera](https://github.com/SonalSingh18/android_device_xiaomi_sm6250-common/commit/10b3951e963ec8e28156fd143496ef6eadbf4768)
- [Add more props needed for miuicamera](https://github.com/SonalSingh18/android_device_xiaomi_sm6250-common/commit/8a6add90c043e8021a349660715cd60984ab9edd)

• Sepolicy changes
- [Address miuicamera sepolicy denials](https://github.com/SonalSingh18/android_device_xiaomi_sm6250-common/commit/cc4066751033bed576680c58f54a4fc5cdc7992d)

• Furthermore, below are the patches needed in ROMs sources
- [13-camera-privapp](https://review.arrowos.net/q/topic:13-camera-privapp)
- [thirteen-jemalloc](https://review.arrowos.net/q/topic:thirteen-jemalloc)

• Done, continue building your ROM as you do normally.
