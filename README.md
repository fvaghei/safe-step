# SafeStep - Warning System for the Blind 👟🔊

## Project Information
- **Project Name:** SafeStep  
- **Developers:** Fatemeh Vaghei, Mobina Amiri Notash  
- **University:** University of Tabriz  
- **Project Start Date:** March 25, 2025  

---

## 🎯 Project Goal  
The goal of SafeStep is to design and implement a smart warning system for blind individuals,
which can be installed on shoes. The system uses advanced sensors to detect obstacles and holes in the path,
alerting the user through vibration or sound.

## 🔥 Features and Capabilities
✅ **Obstacle and Hole Detection:** Using ultrasonic and infrared sensors  
✅ **Tactile and Audio Alerts:** Warning through vibration motors and small speakers  
✅ **Energy Efficiency:** Use of lithium batteries for reduced weight and extended battery life  
✅ **Upgradeable:** Future addition of GPS and machine learning for improved functionality  

---

## 🛠️ Core System Components  
| Component | Parts Used |
|-----------|------------|
| **Sensors** | Ultrasonic Sensor HC-SR04, IR Sensors |
| **Microcontroller** | Arduino or ESP32 |
| **Alert System** | Vibration Motor, Small Speaker |
| **Power Supply** | 3.7V Lithium Battery, TP4056 Charging Module |
| **Connectivity** | Bluetooth for mobile app connectivity (if upgraded) |

---

## 🗺️ Project Roadmap  
### **🔹 Phase 1: Research and Preparation**
- [x] Study the needs of blind users  
- [x] Select appropriate components (sensors, microcontroller, and alert systems)  
- [x] Initial system design  

### **🔹 Phase 2: Hardware and Software Development**
- [ ] Connect and test ultrasonic and IR sensors  
- [ ] Program Arduino / ESP32 to process data  
- [ ] Implement alert system (vibration and audio)  

### **🔹 Phase 3: Testing and Optimization**
- [ ] Test performance in different environments  
- [ ] Optimize energy consumption and obstacle detection accuracy  

### **🔹 Phase 4: Development and Feature Expansion (Optional)**
- [ ] Add Bluetooth connectivity for mobile app integration  
- [ ] Add GPS for improved user guidance  
- [ ] Optimize obstacle detection algorithm with machine learning  

---

## 🖥️ **Use of Renode for Hardware Simulation**  
Since we are focusing on using simulators to develop and test the system, **Renode** will be used to simulate the hardware, including sensors and microcontrollers, instead of using physical hardware for testing. This will allow us to develop and debug the system more efficiently in a virtual environment.

### Steps for Renode Integration:
1. **Simulate microcontroller (e.g., ESP32 or Arduino)** using Renode.
2. **Simulate sensors** (ultrasonic and IR sensors) and connect them to the simulated microcontroller.
3. **Test communication** between the sensors and alert system using Renode.
4. **Verify the system's response** to obstacle detection and alerts in a controlled, virtual environment before hardware deployment.

By utilizing **Renode**, we aim to ensure that the software and system logic are functioning correctly before the physical prototype is tested.

---

## 📌 How to Run  
1. Set up the Renode environment on your local machine.  
2. Clone the project repository and configure the virtual environment.  
3. Run the simulation using Renode to emulate the system's behavior and debug the logic.  
4. Once the simulation is successful, deploy the code to physical hardware (Arduino / ESP32).  

---

## 📢 Contributing and Development  
If you are interested in improving this project, feel free to submit a Pull Request or reach out to us! 😊
