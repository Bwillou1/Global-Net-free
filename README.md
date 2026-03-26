🌍 Global-Net-Free (GNF)
Universal Internet Access for ESP32 & SD Card Systems
Global-Net-Free is an open-source "Plug & Play" firmware designed to turn a simple ESP32 Mini into a smart, autonomous internet gateway. By using a high-capacity microSD card (8GB+), this system bypasses the need for complex configurations and provides essential web services anywhere a public Wi-Fi signal exists.

🚀 The Vision
To create a worldwide database of captive portal bypasses and open Wi-Fi scripts. An explorer, a student, or a cyclist should be able to carry a single ESP32 module and stay connected to Gemini AI, Weather, Maps, and Messaging across 5 devices simultaneously, without ever touching a settings menu.

🛠 Key Features
Auto-Hunt Logic: Scans and connects to open Wi-Fi networks (SSID: McDonald's, Starbucks, Airport_Free, etc.) in milliseconds.

SD-OS Architecture: Uses an 8GB microSD card to store offline maps, UI assets, and a global database of captive portal scripts.

NAT Routing: Acts as a private access point for up to 5 devices (iPhone, Mac, iPad) with built-in firewall.

Service Proxies: Lightweight API integration for:

Gemini AI: Real-time AI assistance via text-only protocols.

OpenMaps: Offline tile rendering for navigation.

Global Weather: Hyper-local forecasts.

Health & Emergency: Direct access to essential health databases.

📂 Project Structure
/firmware: Core C++ source code for ESP32/ESP32-S3.

/sd_files: Assets and JSON configuration files to be copied to the microSD.

/plugins: Community-contributed scripts for specific regional Wi-Fi bypasses.

/docs: Wiring diagrams for SD card modules and external antennas.

🤝 How to Contribute
We are looking for collaborators to help with:

Captive Portal Automation: Writing Python/C++ scripts to "click" the accept button on public networks.

RAM Optimization: Managing the 5-device connection limit on the ESP32's limited memory.

Global SSID Database: Building a JSON list of common open networks by country.

📜 License
This project is licensed under the MIT License - feel free to use, modify, and share!
