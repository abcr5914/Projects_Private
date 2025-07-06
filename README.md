# 🧪 Bottle Filling Simulation – README

This project simulates the process of filling a bottle with air under different physical assumptions. It is organized into logical sections for clarity and flexibility.

---

## 🔧 Setup: Code Blocks 1–4 (Initialization)

These code blocks must be executed **before** any of the simulation sections.

They define:
- Physical constants (e.g., gas constant, heat capacities)
- Initial conditions (e.g., initial pressure, volume)
- Required formulas and helper functions

> ⚠️ **Make sure to run these blocks first.** They are essential for the rest of the code to function correctly.

---

## 🚀 Main Simulation Options

Choose **only one** of the following sections based on your goal. Each one offers a different level of complexity and realism.

---

### 1. 💡 Rough Estimate

- **Purpose**: Quick approximation of the filling time.
- **Method**: Based on basic assumptions (constant flow, no temperature or pressure dynamics).
- **Use Case**: When you want a fast, ballpark estimate of how long the filling will take.

---

### 2. 🔥 Adiabatic Process

- **Purpose**: Models the process with **no heat exchange** between the bottle and the environment.
- **Method**: Assumes air compression causes temperature and pressure to rise inside the bottle.
- **Use Case**: Useful for understanding the thermodynamic behavior under idealized conditions.

---

### 3. 🌡️ Non-Adiabatic Process

- **Purpose**: Adds **realistic heat transfer** between the bottle and surroundings.
- **Method**: Includes cooling effects as the bottle fills, making the model more physically accurate.
- **Use Case**: Recommended for detailed simulations where heat loss matters (e.g., scuba tanks, gas cylinders).

---

## 🧭 How to Use

1. **Run Initialization**: Execute Code Blocks 1 to 4.
2. **Select a Simulation**:
    - 💡 Rough Estimate  
    - 🔥 Adiabatic Process  
    - 🌡️ Non-Adiabatic Process  
3. **Run the chosen section only**. Each section is independent and should be executed separately.

---

## 📘 Notes

- The model assumes air behaves like an ideal gas.
- Units must be consistent (e.g., pressure in Pa, volume in m³).
- You can tweak parameters like bottle volume or ambient temperature in the initialization blocks to explore different scenarios.

---

Explore the simulation step-by-step — from a rough estimate to a fully dynamic thermodynamic model — to understand how air behaves when compressed into a confined space.
