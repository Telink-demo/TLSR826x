# TLSR826x Family


TLSR826x family offers concurrent multi-protocol IoT solution at ISM 2.4GHz band, including Bluetooth Smart (BLE4.0 and BLE4.2), BLE Mesh, 6LoWPAN, Thread, Zigbee, RF4CE, HomeKit and 2.4GHz proprietary protocols. TLSR826x supports hardware OTA and multiple boot switching, allowing convenient product feature roll outs and upgrades, it provides 32-bit MCU, BLE/802.15.4/2.4G Radio, 16K/32KB SRAM, 128KB-512KB Flash, 14bit ADC with PGA, Analog and Digital Microphone, 6-channel PWM (2-channel IR), one quadrature decoder (QDEC), abundant GPIO interfaces, and multi-stage power management.

| Part Number      | Package | Size           | SRAM (KB) | Flash (KB) | Tx    | Rx           | Power Consumption                                                                         | Protocol                            |
|------------------|---------|----------------|-----------|------------|-------|--------------|-------------------------------------------------------------------------------------------|-------------------------------------|
| TLSR8269F512ET32 | QFN32   | 5x5x0.75mm-0.5 | 32        | 512        | +7dBm | -92dBm@BLE1M | 12mA@Rx_transceiver 15mA@Tx0dBm_transceiver 10uA@suspend(SRAM) 1.7uA@deepsleep(IO_Wakeup) | BLE5.0(2M Only)/Zigbee/SigMesh/2.4G |
| TLSR8267F512ET48 | QFN48   | 7x7x0.75mm-0.5 | 16        | 512        | +7dBm | -92dBm@BLE1M | 12mA@Rx_transceiver 15mA@Tx0dBm_transceiver 10uA@suspend(SRAM) 1.7uA@deepsleep(IO_Wakeup) | BLE4.2/2.4G                         |
| TLSR8267F512ET32 | QFN32   | 5x5x0.75mm-0.5 | 16        | 512        | +7dBm | -92dBm@BLE1M | 12mA@Rx_transceiver 15mA@Tx0dBm_transceiver 10uA@suspend(SRAM) 1.7uA@deepsleep(IO_Wakeup) | BLE4.2/2.4G                         |
| TLSR8261F512ET24 | QFN24   | 4x4x0.75mm-0.5 | 16        | 128        | +7dBm | -92dBm@BLE1M | 12mA@Rx_transceiver 15mA@Tx0dBm_transceiver 10uA@suspend(SRAM) 1.7uA@deepsleep(IO_Wakeup) | BLE4.2/2.4G                         |
| TLSR8646F512ET32 | QFN32   | 5x5x0.75mm-0.5 | 16        | 512        | +7dBm | -92dBm@BLE1M | 12mA@Rx_transceiver 15mA@Tx0dBm_transceiver 10uA@suspend(SRAM) 1.7uA@deepsleep(IO_Wakeup) | BLE4.2/2.4G                         |
| TLSR8646F512ET32 | QFN32   | 5x5x0.75mm-0.5 | 16        | 512        | +7dBm | -92dBm@BLE1M | 12mA@Rx_transceiver 15mA@Tx0dBm_transceiver 10uA@suspend(SRAM) 1.7uA@deepsleep(IO_Wakeup) | Zigbee/2.4G                         |


## Datasheet

Download [TLSR8261 Product Brief](http://wiki.telink-semi.cn/doc/ds/PB_TLSR8261-E_Product%20Brief%20for%20Telink%20BLE%20SoC%20TLSR8261.pdf) | Download [TLSR8261 Datasheet](http://wiki.telink-semi.cn/doc/ds/DS_TLSR8261-E_Datasheet%20for%20Telink%20BLE%20SoC%20TLSR8261.pdf)

Download [TLSR8266 Product Brief](http://wiki.telink-semi.cn/doc/ds/PB_TLSR8266-E_Product%20Brief%20for%20Telink%20BLE%20SoC%20TLSR8266.pdf) | Download [TLSR8266 Datasheet](http://wiki.telink-semi.cn/doc/ds/DS_TLSR8266-E_Datasheet%20for%20Telink%20BLE%20SoC%20TLSR8266.pdf)

Download [TLSR8267 Product Brief](http://wiki.telink-semi.cn/doc/ds/PB_TLSR8267-E_Product%20Brief%20for%20Telink%20BLE%20SoC%20TLSR8267.pdf) | Download [TLSR8267 Datasheet](hhttp://wiki.telink-semi.cn/doc/ds/DS_TLSR8267-E_Datasheet%20for%20Telink%20BLE%20SoC%20TLSR8267.pdf)

Download [TLSR8269 Product Brief](http://wiki.telink-semi.cn/doc/ds/PB_TLSR8269F512-E_Product%20Brief%20for%20Telink%20BLE%20+%20IEEE802.15.4%20Multi-Standard%20Wireless%20SoC%20TLSR8269F512.pdf) | Download [TLSR8269 Datasheet](http://wiki.telink-semi.cn/doc/ds/DS_TLSR8269F512-E_Datasheet%20for%20Telink%20BLE%20+%20IEEE802.15.4%20Multi-Standard%20Wireless%20SoC%20TLSR8269F512.pdf)

## Reference Design and SDK

| Reference Design       | Chipset       | Quick Start Guide          | SDK Download         | SDK Development Manual | HW Design Document                 |
|------------------------|---------------|----------------------------|----------------------|------------------------|------------------------------------|
| BLE Generic            | TLSR826x      | [Generic Solution Guide](http://wiki.telink-semi.cn/dokuwiki/doku.php?id=menu:solution:generic)     | [826x_ble_sdk v3.2](http://wiki.telink-semi.cn/tools_and_sdk/BLE_SDK/826x_SDK/ble_sdk.rar)    | [SDK Developer Handbook](http://wiki.telink-semi.cn/tools_and_sdk/BLE_SDK/826x_SDK/Handbook.zip) | [826x Generic Ref](http://wiki.telink-semi.cn/doc/hw/TLSR826X_DevelopmentBoard_TLSR826XDK48D.zip)                   |
| BLE Remote Control     | TLSR826x      | [Remote Control Quick Guide](http://wiki.telink-semi.cn/dokuwiki/doku.php?id=menu:solution:rcu826x) | [826x_ble_sdk v3.2](http://wiki.telink-semi.cn/tools_and_sdk/BLE_SDK/826x_SDK/ble_sdk.rar)    | [SDK Developer Handbook](http://wiki.telink-semi.cn/tools_and_sdk/BLE_SDK/826x_SDK/Handbook.zip) | [826x RCU Ref](http://wiki.telink-semi.cn/doc/hw/TLSR826X_AudioRCU_TLSR826XRC48D.zip)                       |
| BLE Telink Mesh        | TLSR8267/8269 | [Telink Mesh Quick Guide](http://wiki.telink-semi.cn/dokuwiki/doku.php?id=menu:solution:telinkmesh)    | [SDK V1.M and Tools](http://wiki.telink-semi.cn/telink_shenzhen/telink_mesh/telink_mesh_sdk.7z)   | [Development Manual](http://wiki.telink-semi.cn/telink_shenzhen/telink_mesh/telink_mesh_doc.7z)     | [826x Generic Ref](http://wiki.telink-semi.cn/doc/hw/TLSR826X_DevelopmentBoard_TLSR826XDK48D.zip) | [826x Blub Demo](http://wiki.telink-semi.cn/doc/hw/TLSR826X_Dongle_TLSR826XDG32D.zip)  |
| BLE SIG Mesh           | TLSR8269      | [SIG Mesh Quick Guide](http://wiki.telink-semi.cn/dokuwiki/doku.php?id=menu:solution:mesh)       | [SDK V2.9.0 and Tools](http://wiki.telink-semi.cn/telink_shenzhen/SIG_mesh/sig_mesh_sdk.7z) | [Development Manual](http://wiki.telink-semi.cn/telink_shenzhen/SIG_mesh/sig_mesh_doc.7z)     | [826x Generic Ref](http://wiki.telink-semi.cn/doc/hw/TLSR826X_DevelopmentBoard_TLSR826XDK48D.zip) | [826x Blub Demo](http://wiki.telink-semi.cn/doc/hw/TLSR826X_Dongle_TLSR826XDG32D.zip)  |
| Zigbee                 | TLSR8269/8646 | [Zigbee Quick Guide](http://wiki.telink-semi.cn/doc/an/AN_18110500-E_Telink%20Zigbee%20Demo%20User%20Guide.pdf)         | [ZB V3.2.1.0 SDK ](http://wiki.telink-semi.cn/tools_and_sdk//Zigbee_SDK/82xx_SDK/zigbee_sdk.zip)      | [Development Manual](http://wiki.telink-semi.cn/doc/an/AN_19052900-E_Telink%20Zigbee%20SDK%20Developer%20Manual.pdf)     | [826x Generic Ref](http://wiki.telink-semi.cn/doc/hw/TLSR826X_DevelopmentBoard_TLSR826XDK48D.zip) | [826x Dongle Ref](http://wiki.telink-semi.cn/doc/hw/TLSR826X_Dongle_TLSR826XDG32D.zip) |
| 2.4G+BLE Dual-Keyboard | TLSR8267      |                            | [SDK V2.0.4](http://wiki.telink-semi.cn/telink_shenzhen/dual_keyboard/826x/dual_km_8267.7z)           |                        |                                    |
| 2.4G+BLE Dual-Mouse    | TLSR8261      |                            | [SDK V2.4.0](http://wiki.telink-semi.cn/telink_shenzhen/dual_mouse/826x/dual_mouse_8261.7z)           |                        |                                    |
| BLE Generic(Mi)        | TLSR826x      |                            | SDK V2.1.0           |                        |                                    |


## Hardware Developing Tools

[Antenna and PCB Circuit Design Guide](http://wiki.telink-semi.cn/doc/an/AN_16080500-E_Telink%20Antenna%20Design%20Guide.pdf)
[826x Hardware Design Guide](http://wiki.telink-semi.cn/doc/an/AN_16101000-E_Telink%20Hardware%20Design%20Guide.pdf)
[Suggestion for Coin Cell Battery application](http://wiki.telink-semi.cn/doc/an/AN_16122100-E_Suggestions%20for%20Application%20Design%20with%20Coin%20Cell%20Battery.pdf)
[Wireless Product Certification Guide](http://wiki.telink-semi.cn/doc/an/AN_17091400-E_Wireless%20Product%20Certification%20Guide.pdf)
[PCB layout Guide](http://wiki.telink-semi.cn/doc/an/PCB%20layout%20guideline.pdf)

## Manufacture Support Tools

[Mass Production Testplan](http://wiki.telink-semi.cn/doc/an/AN_16071800-E_Telink%20Mass%20Production%20Program%20And%20Test%20Plan.pdf)
[Telink Testbench 1x6 User Guide](http://wiki.telink-semi.cn/doc/an/AN_18071200-E_Assembly%20and%20Maintenance%20Manual%20for%20Telink%20BLE%201x6%20Test%20System%203.2.pdf)
[Telink Testbench 1x1 User Guide](http://wiki.telink-semi.cn/doc/an/AN_16052600-E_Assembly%20and%20Maintenance%20Manual%20for%20Telink%20BLE%201x1%20Test%20System%202.1.pdf)
