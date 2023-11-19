# Air Pollution Prediction Python Project

## Overview

The Air Pollution Prediction Python project focuses on predicting air pollution based on a dataset that monitors the variation in indoor gas concentration over time. The data collected from an array of 6 low-cost sensors is used to evaluate the type of activity carried out in a room. Through the implementation of artificial intelligence, a quantitative approach to determining gas concentration is achieved without the need for careful sensor calibration.

## Context

The dataset contains values acquired by electrochemical gas sensors, including MQ sensors (MQ2, MQ9, MQ135, MQ137, MQ138) and an Analog CO2 gas sensor (MG-811). The sensors are selected based on technical specifications related to their ability to detect classes of compounds. The dataset includes 1845 samples describing four target situations:

1. **Normal situation:** Clean air, a person sleeping, studying, or resting. (Samples: 595)
2. **Preparing meals:** Cooking meat or pasta, frying vegetables, with one or two people in the room and forced air circulation. (Samples: 515)
3. **Presence of smoke:** Burning paper and wood for a short period in a room with closed windows and doors. (Samples: 195)
4. **Cleaning:** Use of spray and liquid detergents with ammonia and/or alcohol. Forced air circulation can be activated or deactivated. (Samples: 540)

Each sample consists of 7 values, where the first six values represent sensor outputs, and the last is the index of the action that generated the values.

## Dataset Details

- **Sensor Types:**
  - MQ sensors: MQ2, MQ9, MQ135, MQ137, MQ138
  - Analog CO2 gas sensor: MG-811

- **Target Situations:**
  1. Normal situation
  2. Preparing meals
  3. Presence of smoke
  4. Cleaning

- **Sample Count:** 1845 samples

## Dataset Source

The dataset was provided by Gambi, Ennio in 2020 and is available on Mendeley Data with the following citation:

Gambi, Ennio (2020), “Air Quality dataset for ADL classification”, Mendeley Data, V1, doi: 10.17632/kn3x9rz3kd.1

## Acknowledgements

Special thanks to Ennio Gambi for providing the dataset for this project.

## Project Structure

- **`notebooks/`:** Jupyter notebooks for data exploration, model training, and evaluation.
- **`src/`:** Python scripts for data preprocessing, model building, and utility functions.
- **`data/`:** Contains the dataset and any additional data files.
- **`models/`:** Saved model files after training.

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/air-pollution-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Explore the Jupyter notebooks in the `notebooks/` directory for detailed analysis.
4. Execute the scripts in the `src/` directory for data preprocessing and model training.

## Dependencies

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `tensorflow`

Feel free to contribute, provide feedback, or report issues. Happy coding!
