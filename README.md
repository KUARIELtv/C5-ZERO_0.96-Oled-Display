# C5-ZERO_0.96-Oled-Display
[C5_0.96_schematic.pdf](https://github.com/user-attachments/files/26047865/C5_0.96_schematic.pdf)

diy flipper zero esp32-c5
<img width="1728" height="366" alt="image" src="https://github.com/user-attachments/assets/63d5d696-1130-43b9-9229-535102a00d4c" />
<img width="1324" height="1116" alt="image" src="https://github.com/user-attachments/assets/fe458b45-8950-44df-87f7-57e48cdebbd1" />
<img width="1085" height="245" alt="image" src="https://github.com/user-attachments/assets/12936955-ced1-4ba3-a95e-21612c17f845" />
<img width="630" height="200" alt="image" src="https://github.com/user-attachments/assets/56ee58b2-e1f4-4f1a-8807-c3507b3ae29f" />
<img width="791" height="409" alt="image" src="https://github.com/user-attachments/assets/817888f9-b77b-4846-9783-46e7119da524" />
// --- New SPI Pin Definitions ---
#define SCK_PIN  8
#define MISO_PIN 9
#define MOSI_PIN 10

// --- CC1101 ---
#define CC_CS    26
#define CC_GDO0  25

// --- nRF24 Modules ---
#define NRF1_CS  24
#define NRF1_CE  23
#define NRF2_CS  15
#define NRF2_CE  27

// --- Infrared ---
#define IR_RX    4
#define IR_TX    5
OLED (I2C)	SDA / SCL	6 / 7
