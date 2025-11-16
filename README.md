






# PLUVERA – Advanced SMS & WiFi Control System

PLUVERA is a modern, powerful, and intelligent remote-control system designed for industrial, commercial, and smart-home applications. It allows full control of electrical equipment through **SMS** and **WiFi**, combining reliability, speed, and advanced hardware features.

---

## 🚀 Hardware Features

### 🔌 Outputs
- **Two Relays – 5A**
- **One Relay – 16A** (suitable for heavy loads)
- **One 220V Triac Dimmer – 6A** (fan/motor speed control)

### ⚡ Power Input
- **12V / 3A power input**

### 🛡️ Safety & System
- High-quality **EMI isolation modules**
- **Back-up battery + RTC** (keeps time/date)
- **Resettable fuses** for instant protection
- Fully stable in industrial environments

---

## 🔗 Connectivity
- **Micro USB** port for:
  - Firmware flashing  
  - Computer connection  
  - Direct programming  

---

## 📱 Mobile Application (Android & iOS)
- Modern, beautiful, and user-friendly interface  
- Very lightweight and fast  
- Supports **4 international languages**  
- Full control of **3 Relays + 1 Dimmer**  
- Configuration over **SMS** or **WiFi**  
- Custom animation/theme editing  
- Fast OTA updates  

---

## 🌐 Communication Features

### SMS Control:
- Set output states  
- Read device status  
- Configure system remotely  

### WiFi Control:
- Dashboard configuration  
- Output scheduling  
- Dimmer control  
- Online updates  

---

## 🔄 Update Policy
PLUVERA receives updates **every 10 days**, based on customer requests and improvements.

---

## 🧩 Available Files
This repository includes:
- **Complete hardware schematic**
- **HEX file** for the main controller
- Supporting documents & resources

---

## 📦 How to Get PLUVERA Sources

### 1. Buy the complete device  
Includes hardware + mobile app.

### 2. Purchase PCB files  
For customers who want to assemble manually.

### 3. Purchase full source code  
Recommended for manufacturers who want to build or customize their own product.

---

## 📞 Contact  
**Persian Electronic Pouya**

- **Phone:** +98 935 391 2827  
- **Email:** pepoya.info@gmail.com  
- **Telegram:** @persian_electronic_poya  


                     ┌──────────────────────────┐
                     │        Power Input        │
                     │       12V DC / 3A         │
                     └─────────────┬────────────┘
                                   │
                        ┌──────────┴──────────┐
                        │   Power Regulation   │
                        │  Protection Fuses &  │
                        │     Isolators        │
                        └──────────┬──────────┘
                                   │
                     ┌─────────────┴────────────────┐
                     │        Main Controller        │
                     │   (Microcontroller + RTC)     │
                     └───────┬───────────┬──────────┘
                             │           │
                ┌────────────┘           └────────────┐
                │                                       │
        ┌───────┴────────┐                    ┌────────┴────────┐
        │   GSM Module    │                    │    WiFi Module   │
        │   SMS Control   │                    │ Local Web Config │
        └───────┬────────┘                    └────────┬────────┘
                │                                       │
          SMS Commands                           WiFi Dashboard
                │                                       │
                └──────────┬───────────────────┬────────┘
                           │                   │
           ┌───────────────▼──────────────┐    │
           │        Output Drivers         │    │
           │  2 × Relay 5A                 │    │
           │  1 × Relay 16A                │    │
           │  1 × Triac Dimmer (6A)        │    │
           └───────────────┬──────────────┘    │
                           │                   │
                      Electrical Loads         │
       (Motors, Fans, Lamps, Pumps, Heaters)   │
                                               │
                                     ┌─────────▼─────────┐
                                     │   Mobile App       │
                                     │ Android / iOS      │
                                     │ Full Control +     │
                                     │ Configuration      │
                                     └────────────────────┘






<img width="412" height="879" alt="2" src="https://github.com/user-attachments/assets/2a34aa81-011b-4036-a526-592b91e16f9a" />
<img width="413" height="873" alt="1" src="https://github.com/user-attachments/assets/e44e401d-76e8-4759-b3f5-bbb0fe8d87c4" />
<img width="415" height="870" alt="14" src="https://github.com/user-attachments/assets/58475cb7-a8d7-416c-8062-ffbfe3002800" />
<img width="416" height="870" alt="13" src="https://github.com/user-attachments/assets/eb59be4f-8859-4f84-afeb-fff5e997884c" />
<img width="411" height="869" alt="12" src="https://github.com/user-attachments/assets/40e514ac-82c4-4067-b2a5-82574ed60081" />
<img width="411" height="873" alt="11" src="https://github.com/user-attachments/assets/23ddce48-0da6-423f-b6aa-60d066c8363d" />
<img width="416" height="873" alt="10" src="https://github.com/user-attachments/assets/2d30df20-048f-4f82-bd1d-c6319f38d2b3" />
<img width="411" height="874" alt="9" src="https://github.com/user-attachments/assets/df4f98fc-dbab-467f-bcfe-a209603883c5" />
<img width="411" height="874" alt="8" src="https://github.com/user-attachments/assets/42d1ac91-c61c-4fc5-a5e5-5b9e032bd383" />
<img width="412" height="871" alt="7" src="https://github.com/user-attachments/assets/90ea2c98-1d6b-485b-8808-7d4e18159924" />
<img width="416" height="868" alt="6" src="https://github.com/user-attachments/assets/9fa033c8-8902-432f-bc45-f862fba8c5cb" />
<img width="414" height="869" alt="5" src="https://github.com/user-attachments/assets/fc16d482-ae4f-43cf-8f42-a7b493d19a9d" />
<img width="412" height="869" alt="4" src="https://github.com/user-attachments/assets/867b716f-eaa8-4427-b390-63c115e3b956" />
<img width="412" height="875" alt="3" src="https://github.com/user-attachments/assets/2c1351e2-bf89-4f5e-9539-6a9bcc8d22b7" />


<img width="1000" height="951" alt="PL2" src="https://github.com/user-attachments/assets/1adf68b1-ece3-4d46-969b-c7e6497f03ac" />
<img width="1000" height="966" alt="PL3" src="https://github.com/user-attachments/assets/e78b5704-dedc-4430-a250-109f777a7f7e" />
<img width="1000" height="969" alt="PL4" src="https://github.com/user-attachments/assets/ca23b433-14ce-4247-b15d-28f20bb238f9" />


