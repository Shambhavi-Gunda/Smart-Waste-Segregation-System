# 🗑️ Automated Waste Segregation System

An Arduino-powered smart system designed to automate the process of waste segregation into dry, wet, and metallic categories using various sensors. This project aims to enhance waste management efficiency, reduce human intervention, and promote environmental sustainability.

## 👥 Team Members

- Shruti Gugilwar (22BCE8957)
- Sourav Vir Singh (22BEC7186)
- Shambhavi Gunda (22BCE8204)
- Aman Yadav (22BCE9004)
- Chirag Agarwal (22BCE9167)
- Shrawani Kulkarni (22BCE9256)

**Mentor:** Dr. Prof. Udit Narayana Kar  
**University:** Vellore Institute of Technology

---

## 🎯 Objective

To design and implement a prototype that can detect and categorize waste using sensor data, sort it using servo-actuated bins, and display the waste type on an LCD. The system aims to:

- Reduce manual labor
- Minimize health risks
- Improve recycling efficiency
- Raise public awareness on sustainable waste disposal

---

## ⚙️ Technologies & Components Used

### 🧠 Microcontroller:
- Arduino Uno

### 🔍 Sensors:
- Ultrasonic Sensor (detect waste presence)
- Infrared (IR) Sensor (detect non-metallic objects)
- Moisture Sensor (detect wet waste)
- Inductive Metal Sensor (detect metallic waste)

### 🛠️ Actuators & Output Devices:
- Servo Motors (bin movement)
- Conveyor Belt (waste transport)
- LCD Display (waste category visualization)
- Load Cells (optional: weight measurement)

### 💡 Additional:
- Motor Driver Circuit
- Power Supply
- Enclosure
- Waste Bins

---

## 🧪 Working Principle

1. Waste is placed into the input container.
2. An ultrasonic sensor detects the presence of waste.
3. The waste is scanned by:
   - **Metal sensor**: If metal, waste is directed to the metal bin.
   - **Moisture sensor**: If wet, sent to wet bin.
   - Otherwise, it is considered dry waste.
4. LCD displays the identified waste type.
5. Servo motors adjust to direct waste into the appropriate bin.

---

## 🧰 How to Run

1. Upload the provided Arduino code to your Arduino Uno.
2. Connect all sensors and actuators as per the circuit diagram.
3. Power on the system.
4. Drop waste into the input section and observe the sorting mechanism.

---

## 🔬 Future Enhancements

- Integration with IoT for real-time bin status updates.
- Adding more waste categories (e.g., hazardous, glass).
- Auto composting of wet waste.
- App notification when bins are full.

---

## 🌍 Use Cases

- Homes and apartments
- Offices and commercial buildings
- Hospitals, schools, and public parks
- Waste management stations

---

## 📜 References

- [Arduino Official Docs](https://www.arduino.cc/reference/en/)
- [Semantics Scholar - IoT Based Waste Segregator](https://www.semanticscholar.org/paper/IoT-Based-Automated-Waste-Segregator)
- [ResearchGate – Smart Waste Segregation Systems](https://www.researchgate.net/publication/349530230_Smart_Waste_Segregation_and_Monitoring_System_using_IoT)

---





> Designed with sustainability in mind 🌱
