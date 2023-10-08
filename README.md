# SwiftUIBluetooth
Example Swift UI Applications to Scan for Bluetooth Radios.

The class BLEManager is used to scan for BLE radios

The struct Peripheral is used to identify the radios (id, name, rssi, and keeps a copy of the device object: CBPeripheral)

DeviceView creates a row view for each radio discovered displaying the radios id, name, rssi.
