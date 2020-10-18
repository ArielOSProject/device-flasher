# Device Flasher
A cross platform tool that simplifies the process of flashing factory images onto phones.

## Getting Started

### Prerequisites
* Download the [latest release](https://github.com/AOSPAlliance/device-flasher/releases) of device flasher for your platform
* Download a factory image ZIP file for your device

### Flashing
* Connect your phone over USB
* Open a terminal and run device flasher for your platform:
  * Windows: 
    ```
    .\device-flasher.exe -path <factory image zip>
    ```
  * Linux: 
    ```
    sudo ./device-flasher.linux -path <factory image zip>
    ```
  * OSX:
    ```
    ./device-flasher.darwin -path <factory image zip>
    ```

## License
This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details.