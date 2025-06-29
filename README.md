# 🛠️ R4TKN 🔥 Wi-Fi Warfare Toolkit for Flipper Zero + BW16

This firmware turns your Flipper Zero (paired with BW16) into a powerful Wi-Fi testing device.  
Includes tools like **DEAUTH ALL**, **Targeted Disruption (Per Station / Client)**, with upcoming features like **Random SSID Spam**, **Beacon Floods**, and **Handshake Capture**.  
Perfect for Wi-Fi experiments, stress testing, and educational network security research.

> ⚠️ **License & Disclaimer**  
> This software is provided "as-is" for educational and research use only. The author disclaims all liability for misuse or damage incurred from its use. Always obtain proper authorization before testing any network security tool.


## Acknowledgements

 - [cypher-5G-deauther - dkyazzentwatwa](https://github.com/dkyazzentwatwa/cypher-5G-deauther/tree/mainawesome-README-templates)

 - [delfyRTL](https://github.com/gorebrau/delfyRTL/tree/main)
 - [flipper-zero-tutorials](https://github.com/jamisonderek/flipper-zero-tutorials)

 - [lopaka - sbrin](https://github.com/sbrin/lopaka)

 - [ambd_sdk](https://github.com/ambiot/ambd_sdk) Image Tool

 - [readme.so](https://github.com/octokatherine/readme.so) 

## Features

- ✅ **DEAUTH ALL**  
  Disconnect all nearby Wi-Fi devices from their networks.

- ✨ **TARGETED – PER STATION and PER CLIENT**  
  Choose a specific Access Point (Station) or a connected device (Client) to target.  
  _→ Other devices will NOT be affected._

---

## 🛠️ Upcoming / TODO Features

- 🚧 **RANDOM SSID** *(In Progress)*  
  Will flood the air with randomly generated fake Wi-Fi names (SSIDs) to confuse nearby scanners.

- 🚧 **BEACON + DEAUTH** *(In Progress)*  
  Will send fake beacon frames with deauth packets to simulate chaotic Wi-Fi environments.

- 🚧 **CAPTURE HANDSHAKE** *(Planned)*  
  Will enable WPA/WPA2 handshake capturing for research and testing.
  
- 🔧 **MORE SOON**  
  Additional tools and experimental features coming soon!
## 🔌 Pin Mapping: RTL8720DN BW16 ↔ Flipper Zero

| RTL8720DN BW16 | Flipper Zero |
|----------------|--------------|
| 5V             | (1) 5V       |
| GND            | (8) GND      |
| RX1            | (13) TX      |
| TX1            | (14) RX      |

> 📎 Pinout reference credits: [gorebrau/delfyRTL](https://github.com/gorebrau/delfyRTL)


## How to Upload Firmware 

### 📥 Flashing Instructions (BW16)

1. **Run as Administrator**  
   - Right-click the **Image Tool** and select `Run as administrator`.

2. **Select Chip Type**  
   - Click `Chip Select` at the top.  
   - Choose **`AmebaD (8721D)`**.

3. **Configure Serial Port**  
   - Go to the `SERIAL` section.  
   - Under `COM`, select the correct port for your connected **BW16**.  
   - Leave the rest of the settings as default.

4. **Load the Firmware**  
   - In the `Flash Download` section, scroll to the **last row**.  
   - Check the box to enable it.  
   - Click `Browse`, locate and select your `.bin` file (e.g. `km0_km4_image2.bin`).

5. **Put BW16 in Flash Mode & Start Flashing**  
   - If your BW16 is **not already in flash mode**, do the following:  
     - Hold the **BOOT** button.  
     - While holding BOOT, **press and release RESET**.  
     - Release the BOOT button.  
     - The BW16 is now in **flash mode**.  
   - Now click the `Download` button to flash the firmware.

### 🛠 Step-by-Step Instructions for Flipper Zero

1. **Install and Launch qFlipper**  
   - Visit the official qFlipper page and download the installer for your OS.  https://flippeprzero.one/update
   - Install and then open **qFlipper**.  
   - Connect your Flipper Zero via USB-C to your PC.

2. **Open the File Manager**  
   - In qFlipper, click the **“File manager”** tab to view the contents of your Flipper’s SD card.

3. **Locate or Create the `apps` Folder**  
   - Navigate to the `apps` directory on your SD card.  
   - If it doesn’t exist, **right-click** on the SD root and select **“New folder”**, then name it `apps`.

4. **Copy the `.fap` File**  
   - **Drag & drop** your `.fap` file directly into the `apps` folder via qFlipper, or  
   - **Right-click → Upload** to select and add it manually.

5. **Verify on the Flipper**  
   - On your Flipper device, navigate: **Applications → FAP Loader**.  
   - You should now see and be able to launch your newly added app.

## 📬 Support / Collaboration

Got questions, ideas, or want to collaborate?  
Drop an email at **web.r4tkn@gmail.com**

[![Buy Me a Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](http://coff.ee/rusn)
## Screenshots

![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/1.png)
![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/4.png)
![](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/Screenshot/7.png)


## PCB  

📦 Local Stocks Available! 🇵🇭 Philippines, 🇸🇬 Singapore, 🇲🇾 Malaysia

![PCB](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/PCB/10.png)
![PCB](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/PCB/8.png)
![PCB](https://github.com/rusyln/flipper-zero-bw16-r4tkn/blob/master/PCB/9.png)



