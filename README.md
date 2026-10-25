# RFID Core

This is a variant of the [MakeACS NFC Core](https://github.com/MakeACS/HW-NFC-Core), that has its NFC reader replaced with an ASK/FSK 125KHz RFID reader module. This allows for use in organizations that use older RFID card standards for access control, like HID or EM. 

The primary hardware, firmware, and mechanical development takes place in the [NFC Core repository](https://github.com/MakeACS/HW-NFC-Core), with the hardware being cloned and the reader being swapped out when a new release is needed. All issues and development progress are tracked on the [NFC Core issues page](https://github.com/MakeACS/HW-NFC-Core/issues). The current RFID Core is based on NFC Core V3.1.0. 

The firmware and mechanical aspects of the RFID Core are identical to the NFC Core. Firmware is built on release with a variant to account for the different reader, but everything else is identical. 

End-user documentation on the use of the RFID Core is also integrated into the [NFC Core User Manual](https://makeacs.github.io/HW-NFC-Core/)

## License
This project is licensed under the CERN-OHL-S 2.0 License. See LIECENSE.txt for more information.
