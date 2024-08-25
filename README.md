# DMA Device Cloning Tool

This tool is designed to clone DMA devices, allowing you to create a `.bin` firmware file that will be saved in the same directory as the software. It offers flexible options for selecting device capacity, decryption methods, and handling device-specific locks.
![微信截图_20240826000850](https://github.com/user-attachments/assets/49a4d422-cfff-4163-b670-7a993ae173c2)

## Hardware requirements

- DMA(75T/35T)

- PCIE Dongle http://dongle.kkword.store/ You can get him here Mailings are only supported to some countries in Europe and Asia!

## Features

- **Select Capacity:** Choose between 75T or 35T for the device capacity.
- **Decryption Options:** Select from two modes: Forced Decryption or Comparison Decryption.
- **Lock ID Handling:** Option to clear device-specific locks if the firmware is locked to a specific device.
- **Firmware Extraction:** The extracted firmware is saved as a `.bin` file in the same directory.
- **Binary File Decryption:** After the firmware is extracted, the tool provides options to decrypt the binary file using the selected decryption method.

## Prerequisites

- Ensure that the DMA device is properly inserted before running the software.
- The software requires `psutil` for USB detection. Install it via pip if necessary:


### Explanation of the Updates

- **Binary File Decryption Section:** Added detailed information about the decryption options (Forced Decryption and Comparison Decryption) and how the tool handles the decryption of the `.bin` file.
- **Completion Step:** Updated to reflect that both the original and decrypted `.bin` files will be saved in the same directory.
- **Example Output:** Clarified that two files (`firmware.bin` and `decrypted_firmware.bin`) will be produced after the process completes.
- **Decryption Issues in Troubleshooting:** Added a note on what to do if decryption fails.
