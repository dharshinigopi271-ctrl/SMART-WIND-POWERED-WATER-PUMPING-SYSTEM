# Smart Wind-Powered Water Pumping System Using Deep Learning

## 📌 Overview

A Deep Learning project for **water output prediction and fault detection** in a smart wind-powered water pumping system.

The project uses sensor and operational data such as wind speed, generator parameters, pump power, water flow, tank level, energy generation, and fault information.

Three Deep Learning models are implemented:

- Artificial Neural Network (ANN)
- Recurrent Neural Network (RNN)
- 1D Convolutional Neural Network (1D CNN)

---

## 🎯 Objectives

- Predict water output using system and environmental parameters.
- Detect faults in the water pumping system.
- Compare ANN, RNN, and 1D CNN models.
- Analyze important sensor and operational features.
- Apply Deep Learning for intelligent renewable-energy-based water pumping.

---

## 📊 Dataset

The dataset contains **100,000 records and 18 features**.

### Main Features

- WindSpeed_mps
- WindDirection_deg
- AirTemperature_C
- Humidity_pct
- AirPressure_hPa
- GeneratorRPM
- GeneratorVoltage_V
- GeneratorCurrent_A
- BatteryVoltage_V
- PumpStatus
- PumpPower_W
- WaterFlow_LPM
- TankLevel_pct
- EnergyGenerated_Wh
- EnergyConsumed_Wh
- FaultCode
- WaterOutput_LPH

---

## 🤖 Models Used

### Water Output Prediction

Regression models:

- ANN
- RNN
- 1D CNN

Target:

```text
WaterOutput_LPH
