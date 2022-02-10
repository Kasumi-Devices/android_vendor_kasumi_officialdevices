# Official devices in Project Kasumi

## Mainline

### [Motorola Moto G⁵](https://github.com/Kasumi-Devices/android_device_motorola_cedric)

Codename: Cedric

Maintainer: [Beru Shinsetsu](https://t.me/WindowZ414)

Upstream: Nick @ Project Materium

### [LeEco Le2](https://github.com/Kasumi-Devices/android_device_leeco_s2)

Codename: S2

Maintainer: [Rajat Prime](https://t.me/rajat_prime)

### [Motorola Moto G⁷ Power](https://github.com/Kasumi-Devices/android_device_motorola_ocean)

Codename: Ocean

Maintainer: [Botan Yuukan](https://t.me/Botan_Yuukan)

Upstream: brvn0 @ Project Sakura

### [Xiaomi Redmi 9 & POCO M2 // Unified](https://github.com/Kasumi-Devices/android_device_xiaomi_lava)

Target device: Xiaomi Redmi 9 (Lancelot)

Additional devices;
- POCO M2 (Shiva)

Codename: LaVa

Maintainer: [Soni Dharma](https://t.me/DreamersGo)

Upstream: Redmi-MT6768

### [Xiaomi Redmi 4X](https://github.com/Kasumi-Devices/android_device_xiaomi_santoni)

Codename: Santoni

Maintainer: [キアリ (Ro. Kiari)](https://t.me/Krxyzn)

Upstream: Jabiyeff Project

### [Xiaomi Redmi 9C/9C NFC/9A/9 India & POCO C3 // Unified](https://github.com/Kasumi-Devices/android_device_xiaomi_garden)

Target device: Xiaomi Redmi 9C (Angelica)

Additional devices;
- Xiaomi Redmi 9C NFC (AngelicaN)
- Xiaomi Redmi 9A (Dandelion)
- Xiaomi Redmi 9 India (Cattail)
- POCO C3 (AngelicaIN)

Codename: Garden

Maintainer: [みかず (Ro. Mikazu)](https://t.me/mikazuuu07)

Upstream: LineageOS

### [Xiaomi Redmi Note 4](https://github.com/Kasumi-Devices/android_device_xiaomi_mido)

Codename: Mido

Maintainer: [Rasyid Al Kautsar](https://t.me/RasyidAlKautsar)

Upstream: zeelog

### [Xiaomi Mi MIX 2](https://github.com/Kasumi-Devices/android_device_xiaomi_chiron)

Codename: Chiron

Maintainer: Shreyas

### [Xiaomi Redmi Note 7](https://github.com/Kasumi-Devices/android_device_xiaomi_lavender)

Codename: Lavender

Maintainer: [MooniTime](https://t.me/MooniTimeBich)

Upstream: LineageOS

-----

## Backstage

### [Vestel Venus V5 & Turk Telekom Venus V5 // Unified](https://github.com/Kasumi-Devices/android_device_vestel_teos)

Target device: Vestel Venus V5 (Teos)

Additional devices;
- Turk Telekom Venus V5 (TeosTT)

Codename: Teos

Maintainer: [Beru Shinsetsu](https://t.me/WindowZ414)

Upstream: Teos-Dev

-----

To add lunch combos for these devices at once, do commands like these;
```bash
source build/envsetup.sh
for i in $(cat vendor/kasumi/officialdevices/list_backstage.txt)
do
add_lunch_combo kasumi_$i-userdebug
done
```

-----

Moveleft (M) 2021-2022 Project Kasumi. All Rights Reserved.
