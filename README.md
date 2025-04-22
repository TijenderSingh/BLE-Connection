# BLE-Connection
🔌 BLE Connection Demo with SwiftUI & CoreBluetooth
This is a simple iOS demo project that shows how to scan, connect, and communicate with a Bluetooth Low Energy (BLE) device (such as an ESP32) using SwiftUI and CoreBluetooth.
🚀 Features
Scans for BLE devices
Automatically connects to a device named "ESP32_Relay"
Detects writable characteristics
Sends "ON" and "OFF" commands to the ESP32
Displays connection status using SwiftUI interface
Uses haptic feedback for better UX
📱 UI Preview
The interface is built with SwiftUI and includes two control buttons:
✅ Turn ON (Sends "ON" to ESP32)
❌ Turn OFF (Sends "OFF" to ESP32)
🧠 Tech Stack
SwiftUI
CoreBluetooth
ObservableObject for state updates
CBPeripheralDelegate & CBCentralManagerDelegate for BLE handling
💡 How to Use
Clone the repository
Open in Xcode
Run on a real iOS device (Bluetooth won’t work on simulator)
Make sure your ESP32 device is powered and broadcasting as "ESP32_Relay"
Tap "Turn ON" or "Turn OFF" to send commands
🛠 ESP32 Setup Tip
Make sure your ESP32 is configured to receive BLE messages and react to "ON" and "OFF" strings.
