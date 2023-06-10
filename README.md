# Velocity Prediction for S2-33

![GitHub repo size](https://img.shields.io/github/languages/code-size/Skizzy-create/Velocity-Prediction-for-S2-33?style=plastic)
![GitHub license](https://img.shields.io/github/license/Skizzy-create/Velocity-Prediction-for-S2-33)
![GitHub repfile count](https://img.shields.io/github/directory-file-count/Skizzy-create/Velocity-Prediction-for-S2-33)

This project is a Linear Regression-based model created to predict the velocity of S2-33 at different stages of flight. The model utilizes various data parameters to make accurate predictions. The current accuracy of the model is 98.89%. 🚀🔮

## Table of Contents

- [Overview](#overview)
- [Data Parameters](#data-parameters)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The aim of this project is to develop a velocity prediction model for S2-33, an aircraft used in specific flight scenarios. By analyzing various data parameters, the model can estimate the velocity during different stages of flight. The model is built using Linear Regression, a popular machine learning algorithm for predicting continuous values. 📈🛩️

## Data Parameters

The following data parameters are used to predict the velocity:

- **Acceleration**: The rate of change of velocity over time. ⏩⏰
- **TWR**: The thrust-to-weight ratio, which indicates the efficiency of an aircraft's engines. ⚙️🏋️
- **AltitudeFromTerrain**: The vertical distance between the aircraft and the terrain. ⬆️🏔️
- **DownrangeDistance**: The horizontal distance covered by the aircraft. ➡️📏
- **Inclination**: The angle between the aircraft's flight path and the horizontal plane. ⤴️📐
- **VesselDeltaV**: The change in velocity of the aircraft. ΔV🔀
- **Apoapsis**: The point in the aircraft's orbit where it is farthest from the Earth. 🌍🛰️
- **Pressure**: The atmospheric pressure at the aircraft's current location. ☁️🌡️
- **GForce**: The gravitational force experienced by the aircraft. ⚖️🪂

## Installation

To run the Velocity Prediction model locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Skizzy-create/Velocity-Prediction-for-S2-33.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Velocity-Prediction-for-S2-33
   ```

3. Install the required dependencies. Make sure you have [Python](https://www.python.org/downloads/) installed. 🐍🔧

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure you have the training data available in the `traning.csv` file. The file contains 3224 rows of training data.

2. Run the `VelocityModel1.ipynb` notebook, which contains the code for the velocity prediction model.

3. The notebook will train the model using the provided training data and evaluate its accuracy. 📊✅

4. Once the model is trained, you can use it to predict velocities for different flight scenarios by providing the relevant data parameters.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request. Let's make this project better together! 😊🤝

## License

This project is licensed under the [MIT License](https://github.com/Skizzy-create/Velocity-Prediction-for-S2-33/blob/main/LICENSE). Feel free to use and modify the code according to the terms of the license.
