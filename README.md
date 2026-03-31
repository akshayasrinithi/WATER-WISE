WATER-WISE

AC Condensation Water Recovery and Monitoring System

Overview

WATER-WISE is a system designed to capture and reuse water generated from air conditioning units. The project focuses on reducing water wastage by integrating data monitoring and visualization tools.

Problem Statement

Air conditioners produce a significant amount of condensate water, which is typically wasted. This project aims to collect, monitor, and repurpose that water for practical use.

System Description

The system consists of three main components:

Water Collection
Condensed water from AC units is collected and stored.
Data Monitoring (Wokwi + ThingSpeak)
Sensor data is simulated using Wokwi and transmitted to ThingSpeak for real-time monitoring.
Visualization (Unity)
A 3D model is developed in Unity to represent the system and its operation.

## Technologies Used

- **Wokwi**: For simulating and prototyping electronic circuits.
- **ThingSpeak**: To collect, store, and visualize data online.
- **Unity**: For creating an interactive 3D representation of the water collection process.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/water-wise.git
   cd water-wise
   ```

2. **Set up Wokwi**:
   - Visit [Wokwi](https://wokwi.com/) and create your circuit using the provided components.
   - Import the Wokwi project files from the repository.

3. **ThingSpeak Configuration**:
   - Sign up for a ThingSpeak account at [ThingSpeak](https://thingspeak.com/).
   - Create a new channel to store your water collection data.
   - Update the API keys in your project code.

4. **Unity Setup**:
   - Download and install Unity Hub.
   - Create a new 3D project and import the assets from the repository.
   - Set up the scene to represent the water collection process.

## Usage

1. **Run the Wokwi Simulation**: Start the simulation to see how the water collection system operates.
2. **Monitor Water Collection**: Check the ThingSpeak channel for real-time data on the amount of condensed water collected.
3. **Explore the Unity Visualization**: Launch the Unity project to interact with the 3D representation of your water-saving system.

## Unity Project Configuration

This project is configured using Unity and includes several essential packages. Below is the content of the `Packages/manifest.json` file, which specifies the dependencies used in this project:

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
    "com.unity.xr.arkit": "4.2.10",
    "com.unity.modules.ai": "1.0.0",
    "com.unity.modules.androidjni": "1.0.0",
    "com.unity.modules.animation": "1.0.0",
    "com.unity.modules.assetbundle": "1.0.0",
    "com.unity.modules.audio": "1.0.0",
    "com.unity.modules.cloth": "1.0.0",
    "com.unity.modules.director": "1.0.0",
    "com.unity.modules.imageconversion": "1.0.0",
    "com.unity.modules.imgui": "1.0.0",
    "com.unity.modules.jsonserialize": "1.0.0",
    "com.unity.modules.particlesystem": "1.0.0",
    "com.unity.modules.physics": "1.0.0",
    "com.unity.modules.physics2d": "1.0.0",
    "com.unity.modules.screencapture": "1.0.0",
    "com.unity.modules.terrain": "1.0.0",
    "com.unity.modules.terrainphysics": "1.0.0",
    "com.unity.modules.tilemap": "1.0.0",
    "com.unity.modules.ui": "1.0.0",
    "com.unity.modules.uielements": "1.0.0",
    "com.unity.modules.umbra": "1.0.0",
    "com.unity.modules.unityanalytics": "1.0.0",
    "com.unity.modules.unitywebrequest": "1.0.0",
    "com.unity.modules.unitywebrequestassetbundle": "1.0.0",
    "com.unity.modules.unitywebrequestaudio": "1.0.0",
    "com.unity.modules.unitywebrequesttexture": "1.0.0",
    "com.unity.modules.unitywebrequestwww": "1.0.0",
    "com.unity.modules.vehicles": "1.0.0",
    "com.unity.modules.video": "1.0.0",
    "com.unity.modules.vr": "1.0.0",
    "com.unity.modules.wind": "1.0.0",
    "com.unity.modules.xr": "1.0.0"
  }
}
```

## Contributing

Contributions are welcome! If you'd like to contribute to the Water-Wise project, please fork the repository and create a pull request.

## Acknowledgements

- Special thanks to the Wokwi, ThingSpeak, and Unity communities for their valuable resources and support.
- A shout-out to everyone who believes in sustainable practices and contributes to water conservation initiatives.


---




