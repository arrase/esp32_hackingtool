# ESP Hacking Tool

This repository is a fork of the original project [Kl0ibi/esp32_hackingtool](https://github.com/Kl0ibi/esp32_hackingtool). Thanks to the original author for their work.

## Changes from the original version

- Display-related code was removed, leaving only the CLI interface via USB terminal.
- Built with ESP-IDF 5.2.2.
- Bug fixes.

## Requirements

- ESP32
- [ESP-IDF 5.2.2](https://docs.espressif.com/projects/esp-idf/en/v5.2.2/esp-idf)
- USB cable for terminal connection

## Installation

Follow these steps to set up the environment and build the project:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/arrase/esp32_hackingtool.git
    cd esp32_hackingtool
    ```

2. **Set up the ESP-IDF environment:**

    Follow the official instructions to [set up the ESP-IDF](https://docs.espressif.com/projects/esp-idf/en/v5.2.2/get-started/index.html#step-4-set-up-the-tools).

3. **Build the project:**

    ```sh
    idf.py set-target esp32
    idf.py build
    ```

4. **Flash the firmware to the ESP32:**

    ```sh
    idf.py flash
    ```

5. **Open the monitor for the CLI interface:**

    ```sh
    idf.py monitor
    ```

## Usage

Once the device is flashed and connected, open a terminal and use `idf.py monitor` to interact with the hacking tool via the CLI.

