# m5stack
- Using GRAY

## Setup
- CP210X driver
  - https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/drivers/CP210x_VCP_MacOS.zip
  - need to allow from System Preferences
- Boards manager
  - Open Arduino IDE
  - Arduino -> preferences -> Settings
  - Input Additional Boards Manager URLs
    - https://dl.espressif.com/dl/package_esp32_index.json
  - Tools -> Boards Manager
    - Search esp32
    - Install it (version was 1.0.4 when I did)
  - Tools -> Board -> M5Stack-Core-ESP32
- M5Stack Library
  - Sketch -> Include Library -> Manage Labraries
    - Search M5Stack
    - Install M5Stack (vresion was 0.3.0 when I did)
- Port
  - Tools -> Port -> Sfelect /dev/cu.SLAB_USBtoUART

## Test
- File -> Examples -> Examples from Custom Libraries -> M5Stack -> Game -> Tetris
- Compile and Upload

## references
- https://docs.m5stack.com/#/en/arduino/arduino_development