# Robodog

**Aşağıda kodda kullanılan bazı mekaniklerin açıklaması verilmiştir

## class motor_set
  -Motor pin bilgisini tutar
  -Her motor için kalbirasyon noktasını tutar

## Dinamik()
  - 6 eksenli gyro-ivme sensöründen verileri alır
  - Robotun eğim değişimlerinde dengesini sağlayarak gövdesini düz tutmasını sağlar

## swrite()
  - Motorlardan alınan PWM sinyallerini işler
  - Açı verilerini PWM sinyallerine dönüştürerek daha okunaklı bir kod yazmamızı sağlar

## pos_cal()
  - Robotun tüm bacaklarını kalibirasyon için sıfır konumlarına getirir

## kinematik()
  - Her bacağın gideceği konumu kordinat olarak alır
  - Gitmesi gereken konum için Femur, Tibia ve Coxa açılarını hesaplar
  - Ayak uçlarını istenilen konuma açı verisi alınmadan kendisi hesaplayarak götürür
  - ![kinematik](https://github.com/berfinncicek/Quardruped-Robodog/assets/107148931/e0677449-ed3e-4ae8-9e66-9a903e0ab2e5)

https://github.com/berfinncicek/Quardruped-Robodog/assets/107148931/4e4f1e92-da8c-4909-8264-80582108dd2b

https://github.com/berfinncicek/Quardruped-Robodog/assets/107148931/8e00a746-0836-48ba-806a-246b0fec133c




  

  







