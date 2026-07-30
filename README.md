# Carte Meteo Lora 1

Solar and battery powered LoRa weather station

## IC List

- STM32L431CCT6 (Low power MCU)
- HT7150 (+3V3 LDO)
- SX1262TR8 (SX1262 LoRa module)
- WS2812B (Addressable RGB LED)
- MS5607 (Pressure sensor)
- GXHT30 (Humidity and temperature sensor)
- HTU21D (Humidity and temperature sensor)
- BQ25798 (1s battery charger with MPPT)
- TPS6282 (SMPS)

## Top preview

<img width="1254" height="850" alt="image" src="https://github.com/user-attachments/assets/5ebe8a58-f0a8-4b58-b20e-9a0a2d850274" />

## Preview 3d render

<img width="1388" height="797" alt="image" src="https://github.com/user-attachments/assets/c361e7a9-1dff-4442-b063-5578eef9e790" />

## Pictures

## Pin definitions

```c
#define LORA_RST_PIN PB0
#define LORA_DIO1_PIN PB1
#define LORA_BUSY_PIN PB11
#define LORA_DIO3_PIN PB10
#define LORA_CS_PIN PA4
#define LORA_SCK_PIN PA5
#define LORA_MISO_PIN PA6
#define LORA_MOSI PA7

#define BTN_PIN PB12
#define STATUS_PIN PB13

#define SCL_PIN PB6
#define SDA_PIN PB7
#define CE_PIN PA11
#define INT_PIN PA12
#define QON_PIN PA10

#define RGB_PIN PC13

#define RAIN_PIN PB4
#define W_DIR_PIN PA1
#define WIND_PIN PA0
```
