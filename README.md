
## Overview

**Animéa** is an open-source hardware project designed to bring a traditional doll to life. It consists of a compact, feature-rich development board built around the **ESP32** microcontroller, specifically created to serve as the "brain" of an interactive smart doll (or any voice-enabled toy).

The board enables realistic interactions such as voice recognition, speech synthesis, emotional sound responses, and physical animations.

## Features

- **ESP32-WROOM** microcontroller with WiFi & Bluetooth
- High-quality speaker for clear voice output and sound effects
- Built-in microphone for voice input and local/cloud voice recognition
- Multiple USB ports for programming, charging, and expansion
- Dedicated FPC connector for display or LED matrix (e.g., eyes)
- Two programmable tactile buttons + one physical button
- Status LEDs and expansion headers for motors/servos
- LiPo battery management
- Compact form factor optimized for embedding into a doll or toy

## Project Goal

The main objective of **Animéa** is to transform a static doll into an engaging, responsive, and educational companion that can:
- Talk and sing
- React to the child's voice
- Play interactive voice games
- Express emotions through sound, light, and movement

## Hardware Specifications

- **Main MCU**: ESP32 (WiFi + Bluetooth)
- **Audio**: Power amplifier + large speaker
- **Input**: Digital microphone
- **User Interface**: BUTTON1, BUTTON2 + BOOT button
- **Connectivity**: Multiple USB-C/USB ports + FPC connector
- **Power**: LiPo battery support with charging circuit

## Repository Contents

- Hardware design files (KiCad)
- Firmware source code
- 3D models for doll integration (soon)
- Documentation and pinout
- Example code (voice, audio, sensors)

## Getting Started

1. Clone the repository
2. Flash the initial firmware using ESP-IDF or Arduino IDE
3. Connect a LiPo battery and speaker
4. Explore the example projects

Detailed setup instructions are available in the [docs](docs/) folder.

## Future Plans

- Full voice assistant integration (local + cloud options)
- Face/eye animation with LCD or LED matrix
- Motor control for head and limb movements
- Mobile app companion
- Educational games and stories

## License

This project is open source under the [MIT License](LICENSE).

---

**Made with ❤️ for interactive toys and creative makers.**

Feel free to open issues, suggest features, or contribute!
