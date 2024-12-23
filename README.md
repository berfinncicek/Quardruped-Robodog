# Robotic Dog Project

This project is a robotic dog controlled via a microcontroller. It integrates servo motors, sensors, and a display module to simulate walking, balance control, and movement dynamics.

## **Hardware Components**
- **Arduino Board**: Main controller.
- **Adafruit PWM Servo Driver**: Controls multiple servo motors.
- **MPU6050 Accelerometer/Gyroscope**: Measures orientation and balance.
- **TFLI2C Distance Sensor**: Detects obstacles.
- **Adafruit PCD8544 LCD Display**: Displays basic graphics and information.
- **Servo Motors (12x)**: Controls leg joints for movement.

## **Libraries Used**
- `Wire.h`
- `Servo.h`
- `Adafruit_PWMServoDriver.h`
- `MPU6050.h`
- `TFLI2C.h`
- `SPI.h` 
- `Adafruit_GFX.h`
- `Adafruit_PCD8544.h`


## **Setup**
1. Connect servo motors to the Adafruit PWM Servo Driver.
2. Attach the MPU6050 and TFLI2C sensors to the I2C bus.
3. Connect the PCD8544 LCD display to the specified SPI pins.
4. Upload the firmware using Arduino IDE.

## **Usage**
- Power the Arduino and initialize the robot via `setup()`.
- The robot begins walking using `loop()` with predefined step patterns.
- Monitor balance and adjust dynamically with sensor data.

## **Functions Overview**
- `fakestep()` / `fakestep_2()` – Simulates walking steps.
- `dinamik()` – Balances robot dynamically.
- `kinematik()` – Calculates kinematic parameters for leg movement.
- `swrite()` – Controls individual servos.
- `calculate_func()` – Calculates step-related parameters.

## **Safety Precautions**
- Ensure all servo motors are properly connected and calibrated.
- Avoid exceeding servo motor angle limits.
- Secure power connections to prevent sudden shutdowns.

##  **Contributing**
Feel free to contribute by improving code, fixing bugs, or suggesting new features. Open an issue or pull request on GitHub.

## 📜 **License**
This project is licensed under the MIT License. See the LICENSE file for more details.

  - ![kinematic](https://github.com/berfinncicek/Quardruped-Robodog/assets/107148931/e0677449-ed3e-4ae8-9e66-9a903e0ab2e5)

https://github.com/berfinncicek/Quardruped-Robodog/assets/107148931/4e4f1e92-da8c-4909-8264-80582108dd2b

https://github.com/berfinncicek/Quardruped-Robodog/assets/107148931/8e00a746-0836-48ba-806a-246b0fec133c




  

  







