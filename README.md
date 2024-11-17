# ESP32 Digital Clock with OLED Display ⏰
A digital clock simulation using ESP32 and an SSD1306 OLED display. Displays time dynamically in HH:MM:SS format.


A simple project that simulates a digital clock using the ESP32 and an OLED display (SSD1306). This project demonstrates how to dynamically update and display time (hours, minutes, seconds) on a 128x64 OLED screen.

🛠 Features

   • Real-time clock simulation without an RTC module.
   
   • Dynamically updates every second using millis().
   
   • Clear and easy-to-read digital clock display.
   
   • Compatible with 4-pin I2C OLED screens.

📸 Screenshot
![Bez názvu](https://github.com/user-attachments/assets/c3f608ed-99c5-435d-a596-11215d131a4e)

⚙️ Requirements

   Hardware:
   
   •  ESP32 development board.
   
   •  OLED display (128x64, I2C, SSD1306).
   
   •  Jumper wires and breadboard.
   

   Software:
   
   • Arduino IDE with the following libraries installed:
   
   • Adafruit GFX Library
   
   • Adafruit SSD1306
   
   • Wire.h


🔧 Wiring

![obrázok](https://github.com/user-attachments/assets/c6b12c96-682a-45f6-a9b0-bfabdbe8ca7d)


🚀 Getting Started

   1. Clone the repository:

    git clone https://github.com/CabPal/esp32-digital-clock.git

   2. Open the project in Arduino IDE.
   3. Install the required libraries:
       • Go to Tools > Manage Libraries, search for the libraries, and install them.
   4. Connect the hardware as per the wiring table.
   5. Upload the code to your ESP32.
   6. Watch the clock in action! 🎉

📜 Code Overview

The code dynamically updates the time using the millis() function and formats it into HH:MM:SS. The Adafruit_SSD1306 library is used to draw the text on the OLED display.

Key functions:

   • displayTime(): Updates the OLED screen with the current time.
   
   • setup(): Initializes the display and sets default values.
   
   • loop(): Handles the time calculations and refresh rate.
