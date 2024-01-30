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

![kinematik](https://github.com/berfinncicek/Quardruped-Robodog/assets/107148931/4380fcd4-9abe-483b-b7d9-a138225c4fc3)
    
  

  







