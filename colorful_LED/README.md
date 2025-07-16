# Colorful LED Controller with PWM + OLED Display

This project demonstrates a circuit that controls a common-cathode RGB LED using PWM signals based on potentiometer inputs. The intensity of each color channel (Red, Green, Blue) is controlled via three potentiometers, and the current RGB values are displayed on an SSD1306 OLED screen, both in decimal (PWM duty cycle) and hexadecimal (color code) formats.

🔗 **Live Wokwi Simulation**:  
[https://wokwi.com/projects/436583863299535873](https://wokwi.com/projects/436583863299535873)

---

## 💡 Project Goals

This Wokwi simulation serves as a **demonstration prototype**. The ultimate goal is to:
- **Design and fabricate** a physical PCB using **KiCad**
- Use a standalone **microcontroller chip** (e.g., ATtiny, ATmega, or RP2040)
- Download and adapt the control code (Arduino/C++ or other as needed) to match the chip and toolchain
- Build a functional, soldered hardware unit with rotary knobs and a color feedback display

---

## 🔧 Features

- 3x potentiometers to control R, G, B levels
- RGB LED color mixing via PWM
- SSD1306 OLED shows current values:
  - PWM (0–255) for each channel
  - HEX color code for reference
- Fully interactive **Wokwi simulation**

---

## 🛠️ To Do

- [ ] Design the PCB in KiCad
- [ ] Select a microcontroller (e.g., ATtiny1616, ATmega328P)
- [ ] Adapt the code for that MCU (using AVR-GCC or Arduino core)
- [ ] Print and etch the PCB
- [ ] Assemble and test the final circuit

---

## 📁 Files

- `main.ino`: Arduino sketch used in Wokwi
- `README.md`: Project overview and simulation link
- KiCad design files: *coming soon*


## License

MIT License — free to use and modify.

