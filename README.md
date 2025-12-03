This research paper compares four Bluetooth Low Energy (BLE) distance measurement techniques—RSSI, RTT, AoA/AoD, and Channel Sounding—for 
indoor positioning where GPS fails, such as in libraries, malls, or warehouses.​

Experiments using ESP32-C6 boards in multipath environments (university library, corridor) tested 
RSSI (signal strength via log-distance path loss) and RTT (round-trip time), collecting 50 measurements 
at 0.5m intervals from 0.5-5m. RTT showed better stability (1-2m accuracy) than RSSI's fluctuations 
(2-5m errors), while AoA/AoD and Channel Sounding (Bluetooth 6.0) offer sub-meter precision but need specialized hardware.​

The paper provides guidelines: use RSSI for low-cost zone detection, 
RTT for asset tracking, and advanced methods for precision robotics/navigation, 
highlighting trade-offs in accuracy, power, cost, and device support.​
