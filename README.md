# LearnPico
**No Headache Guide to Raspberry Pi Pico**

This repository is your ultimate guide to learning and mastering the Raspberry Pi Pico. With step-by-step instructions, easy-to-understand explanations, and clear code examples, this guide will help you explore the world of microcontrollers without any headaches.

![Raspberry Pi Pico](https://github.com/user-attachments/assets/acd90499-2c8c-4d1c-bb28-896fca34f381)

## What You’ll Learn
- **Raspberry Pi Pico Basics:** Understand the hardware and software essentials.
- **Development Environment Setup:** Configure your tools for seamless coding.
- **Project Execution:** Start with simple tasks and advance to more complex projects.

---

## Setup Instructions

Before you begin your projects, ensure your Raspberry Pi Pico and development environment are properly set up.

### 1. Setting Up Your Raspberry Pi Pico

- **Installing MicroPython:**
  - Follow the official [MicroPython setup guide](https://www.raspberrypi.com/documentation/microcontrollers/micropython.html) to install MicroPython on your Raspberry Pi Pico.
  - Detailed steps can be found in the [Raspberry Pi Pico Python SDK](raspberry-pi-pico-python-sdk.pdf), which provides a comprehensive overview of setting up MicroPython, flashing the firmware, and running your first script.

> [!NOTE]
> Ensure your Pico is disconnected from any power source before flashing the firmware.

### 2. Installing Thonny IDE

Thonny is a beginner-friendly IDE recommended for programming with the Raspberry Pi Pico. Here's how to set it up:

- **Download and Installation:**
  - Visit the [Thonny website](https://thonny.org) and download the latest version for your operating system.
  - Refer to the setup instructions detailed in your course's [Lab 1 document](cs65_lab1.pdf), which provides step-by-step guidance on installing and configuring Thonny.

> [!TIP]
> Thonny is perfect for beginners, but as you advance, consider using Visual Studio Code for more features.

- **Writing Your First Program:**
  - Once Thonny is installed, you can start by writing a simple "Hello, World!" program. Create a new file, write your code, and execute it using the "Run" button.
  - Refer to the [MicroPython documentation](micropython-docs.pdf) for additional examples and coding tips.

> [!CAUTION]
> Always save your work frequently to avoid losing progress due to unexpected errors.

### 3. Using Visual Studio Code for Pico Projects

For users who prefer a more feature-rich environment:

- **VS Code Setup:**
  - Install the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) and configure it for MicroPython development.
  - Check out the [Raspberry Pi Pico Python SDK](raspberry-pi-pico-python-sdk.pdf) for instructions on setting up VS Code for Pico projects.

> [!IMPORTANT]
> Always verify that your Python extension is properly configured for MicroPython to avoid issues during development.

- **Debugging Tips:**
  - VS Code offers powerful debugging tools. Use breakpoints to pause code execution and inspect variables.
  - Refer to the [VS Code Debugging Guide](https://code.visualstudio.com/docs/editor/debugging) for advanced tips and techniques.

### 4. Flashing the Pico with Firmware

- **Boot Mode and Flashing:**
  - Hold the BOOTSEL button while connecting your Pico to your computer to enter USB mass storage mode.
  - Copy the MicroPython UF2 file to the Pico's storage to flash the firmware.
  - Detailed instructions can be found in the [MicroPython setup guide](https://www.raspberrypi.com/documentation/microcontrollers/micropython.html) and [Pico SDK documentation](raspberry-pi-pico-python-sdk.pdf).

> [!WARNING]
> Flashing the wrong firmware can render your Pico non-functional. Always double-check the file before proceeding.

> [!TIP]
> After flashing, your Pico will reboot automatically. If it doesn't, disconnect and reconnect it to your computer.

---

## Tutorials

### Getting Started

- **Hello World:**
  - Your first step into Pico programming is to blink the built-in LED. This simple "Hello World" equivalent helps you verify that your setup is working correctly.
  - Follow the [Setup Guide](https://www.raspberrypi.org/documentation/microcontrollers/micropython.html) to get started.

> [!NOTE]
> The built-in LED is connected to GPIO pin 25 on the Pico.

### Basic Projects

- **Button Controlled LED:**
  - Learn how to control an external LED using a button. This project introduces you to GPIO pin manipulation.
  - Refer to the [Raspberry Pi Pico Python SDK](raspberry-pi-pico-python-sdk.pdf) for GPIO pin details and example code.

> [!CAUTION]
> Be careful when wiring the button and LED to ensure correct polarity and avoid damaging components.

- **Temperature Sensing:**
  - Utilize the onboard temperature sensor to read and display temperature values. This project covers analog-to-digital conversion and data handling.
  - The [MicroPython documentation](micropython-docs.pdf) provides an in-depth explanation of the ADC (Analog-to-Digital Converter) and how to use it with the Pico.

> [!TIP]
> Experiment with different temperature ranges to calibrate your sensor readings for accuracy.

### Intermediate Projects

- **Internet Connectivity with Pico W:**
  - Connect your Pico W to the internet using Wi-Fi. This project will guide you through the process of setting up a network connection and sending data over the web.
  - Follow the [Pico W guide](connecting-to-the-internet-with-pico-w.pdf) for detailed instructions and example projects.

> [!IMPORTANT]
> Ensure your Wi-Fi credentials are securely stored and not hard-coded into your scripts to protect your network.

- **Servo Control:**
  - Control servo motors with the Pico to create moving projects. Learn about PWM (Pulse Width Modulation) and how to use it for precise control of servos.
  - The [Raspberry Pi Pico Python SDK](raspberry-pi-pico-python-sdk.pdf) includes example code and a deeper understanding of PWM.

> [!TIP]
> Start with small, low-torque servos to avoid overloading your Pico during initial testing.

### Advanced Projects

- **Home Automation:**
  - Use the Pico to create basic automation systems for your home. This project might involve controlling lights, appliances, or security systems.
  - Consider integrating internet connectivity and sensor data to enhance your automation project. Refer to the [Pico W guide](connecting-to-the-internet-with-pico-w.pdf) for IoT-related tasks.

> [!CAUTION]
> When working with high-voltage systems, always prioritize safety and consider consulting an electrician.

- **Robotics:**
  - Build and control simple robots using your Pico. This project covers motor control, sensor integration, and basic autonomous behavior.
  - The [MicroPython documentation](micropython-docs.pdf) offers insights into interfacing with various sensors and actuators.

> [!NOTE]
> Robotics projects often require additional power sources beyond what the Pico can supply. Ensure you have adequate power management.

---

## Resources

Here are some essential resources to further assist you in your Raspberry Pi Pico journey:

![Resources](https://github.com/user-attachments/assets/267f21df-050f-4665-b996-57faf604c288)

- **Official Documentation**
  - [Raspberry Pi Pico Python SDK](raspberry-pi-pico-python-sdk.pdf): This document is the go-to resource for everything related to programming your Pico with MicroPython.
  - [Raspberry Pi Pico C/C++ SDK](https://datasheets.raspberrypi.com/pico/raspberry-pi-pico-c-sdk.pdf): If you're interested in using C/C++ instead of Python, this is the guide for you.

- **MicroPython Documentation**
  - [MicroPython Docs](micropython-docs.pdf): A comprehensive guide to MicroPython, covering the language, libraries, and examples specific to the Pico.

- **Development Tools**
  - [Thonny IDE](https://thonny.org): A beginner-friendly IDE for MicroPython development.
  - [Visual Studio Code](https://code.visualstudio.com/): A powerful IDE with extensive plugin support, ideal for advanced users.

- **Learning Resources**
  - [MicroPython on the Raspberry Pi Pico](https://projects.raspberrypi.org/en/projects/getting-started-with-the-pico): An official Raspberry Pi project that walks you through getting started with the Pico.
  - [Introduction to MicroPython](https://www.learnmicropython.com/): A tutorial series covering the basics of MicroPython.

> [!TIP]
> Bookmark these resources for quick access during your development process.

---

## Community and Support

Join the Raspberry Pi community to get help, share your projects, and stay updated on the latest developments:

- **Raspberry Pi Forums:** [forums.raspberrypi.com](https://forums.raspberrypi.com/)
- **Reddit:** [r/raspberry_pi](https://www.reddit.com/r/raspberry_pi/)

Additionally, you can find support for Thonny and MicroPython-specific queries:

- **Thonny Forum:** [thonny.org](https://thonny.org)
- **MicroPython Forum:** [forum.micropython.org](https://forum.micropython.org)

> [!NOTE]
> Engaging with the community can provide you with new ideas, solutions to problems, and feedback on your projects.

---

## Contributing

We welcome contributions to this guide! Whether it's improving existing content, adding new projects, or correcting errors, your help is appreciated. Please check out our [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
