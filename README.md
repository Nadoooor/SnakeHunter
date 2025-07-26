# **SnakeHunter - ESP32 Multi-Tool**  
*(Inspired by Flipper Zero)*  

A versatile **ESP32-based** device with a **TFT touchscreen**, inspired by the **Flipper Zero**, but focused on **IR control, and more**. Built on the **Bruce firmware** framework, this project turns your ESP32 into a pocket-sized hacking. <br>
I made this project because I love cybersecurity specialy networks and the idea of cloneing them.

---  

## **Features**  
**IR Remote Control** – Transmit & receive infrared signals (like a universal remote)  
**RFID/NFC (Optional)** – Read & emulate RFID/NFC tags (requires PN532 module)    
**Wi-Fi Tools** – Basic network scanning & deauthentication (for educational purposes)  
**Bluetooth HID** – Connect & control devices via Bluetooth  
**Custom Apps & Plugins** – Expandable with Bruce firmware modules  

---  

## **Hardware Setup**  
### **Required Components**  
- **ESP32 (WiFi + Bluetooth)** – ESP32-WROOM or similar  
- **TFT Touchscreen** – ILI9341, ST7789, or similar (SPI interface)  
- **IR Transmitter & Receiver** – VS1838B + IR LED  
- **Power Supply** – LiPo battery + charging circuit (or USB power)  

### **Optional Modules**  
- **PN532 NFC/RFID** – For badge emulation  
- **CC1101 RF Module** – Sub-GHz radio (like Flipper Zero)
  
### **Photos**
<img width="735" height="867" alt="case" src="https://github.com/user-attachments/assets/213c4a4b-2f6b-4f98-8a7a-50e1aecd2dcb" />
<img width="739" height="606" alt="schem" src="https://github.com/user-attachments/assets/aff0e6a6-4690-4f7d-8f79-8ddbd42625fa" />


