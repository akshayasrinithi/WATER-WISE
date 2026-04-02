 AC Condensation Water Recovery and Monitoring System
# 💧 WATER-WISE

### AC Condensation Water Recovery and Monitoring System

---

## 🚀 Overview

WATER-WISE is an intelligent system designed to capture, monitor, and reuse water generated from air conditioning units. The project focuses on minimizing water wastage by integrating real-time data monitoring and interactive visualization tools.

This system demonstrates how everyday appliances can be transformed into sustainable resource generators using technology.

---

## 🎯 Problem Statement

Air conditioners generate a significant amount of condensate water during operation.

However:

* This water is typically discarded
* No monitoring or tracking systems are used
* Potential reuse opportunities are ignored

WATER-WISE addresses this gap by creating a system that collects, tracks, and visualizes this otherwise wasted resource.

---

## 💡 System Description

The system consists of three major components:

### 1. 💧 Water Collection

* Condensed water from AC units is captured
* Stored for reuse in practical applications (cleaning, irrigation, etc.)

### 2. 📡 Data Monitoring (Wokwi + ThingSpeak)

* Sensor data is simulated using **Wokwi**
* Data is transmitted to **ThingSpeak** cloud platform
* Enables real-time monitoring and analysis

### 3. 🎮 Visualization (Unity)

* A 3D model built in **Unity** represents the system
* Provides an interactive view of water flow and storage
* Enhances understanding through visual simulation

---

## 🛠️ Technologies Used

* **Wokwi** – Circuit simulation and prototyping
* **ThingSpeak** – Cloud-based data collection and visualization
* **Unity** – 3D modeling and interactive simulation

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/water-wise.git
cd water-wise
```

---

### 2. Wokwi Setup

* Visit: https://wokwi.com/
* Create or import the circuit from this repository
* Run the simulation to generate sensor data

WOKWI LINK FOR AUDR'S WATER-WISE:
https://wokwi.com/projects/399206350042061825

<img width="1802" height="815" alt="Screenshot 2026-04-02 112137" src="https://github.com/user-attachments/assets/9fdd64f0-460c-4760-87ac-a3fbc7ea6e14" />

---

### 3. ThingSpeak Configuration

* Create an account: https://thingspeak.com/
* Create a new channel
* Copy API keys
* Update them in your project code

<img width="1908" height="863" alt="Screenshot 2026-04-02 112800" src="https://github.com/user-attachments/assets/432218c5-e25c-421d-bab8-55b2dd49a3cc" />

---

### 4. Unity Setup

* Install Unity Hub
* Open the Unity project from this repository
* Load the scene and run the simulation
<img width="1703" height="836" alt="Screenshot 2026-04-02 112202" src="https://github.com/user-attachments/assets/f2c95523-2922-4f6a-8b62-1fd666075b35" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/e80cdaff-312d-4202-a2a3-683a42fb49db" />

---

## ▶️ Usage

1. Run the Wokwi simulation
2. Observe real-time data on ThingSpeak
3. Launch Unity to interact with the 3D system

---

## 📊 System Workflow

1. AC generates condensate water
2. Water is collected and stored
3. Sensor data is simulated (Wokwi)
4. Data is sent to ThingSpeak
5. System is visualized in Unity
<img width="672" height="454" alt="Screenshot 2026-04-02 114021" src="https://github.com/user-attachments/assets/b38b0451-53fd-4236-88c5-35c4b0d5815f" />

---

## 🧠 Unity Project Configuration

This project uses Unity with the following package dependencies defined in `Packages/manifest.json`:

```json
{
  "dependencies": {
    "com.unity.collab-proxy": "1.17.2",
    "com.unity.feature.development": "1.0.1",
    "com.unity.ide.rider": "3.0.15",
    "com.unity.ide.visualstudio": "2.0.22",
    "com.unity.ide.vscode": "1.2.5",
    "com.unity.inputsystem": "1.4.4",
    "com.unity.postprocessing": "2.3.0",
    "com.unity.shadergraph": "12.1.7",
    "com.unity.test-framework": "1.1.31",
    "com.unity.textmeshpro": "3.0.6",
    "com.unity.timeline": "1.6.4",
    "com.unity.ugui": "1.0.0",
    "com.unity.visualscripting": "1.7.8",
    "com.unity.xr.arfoundation": "4.2.10",
    "com.unity.xr.arkit": "4.2.10"
  }
}
```

---

## 🔮 Future Enhancements

* 🤖 AI-based water generation prediction
* 📱 Web dashboard (Streamlit integration)
* 🌐 IoT hardware implementation (real sensors)
* 🌾 Smart irrigation system using collected water

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Submit a pull request

---

## 🙌 Acknowledgements

* Wokwi for circuit simulation
* ThingSpeak for IoT data visualization
* Unity for 3D system modeling

Special thanks to all initiatives promoting sustainable water usage 🌱

---

## 👨‍💻 Author

**Akshaya Srinithi SV**
Final Year ECE | AI + Electronics Enthusiast

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
