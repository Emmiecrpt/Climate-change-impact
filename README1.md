# Climate Change Impact Assessment with Satellite Imagery and AI

## Introduction

This repository contains code and resources for assessing the impact of climate change using satellite imagery and artificial intelligence (AI) techniques. With the increasing concern over climate change and its effects on the environment, it's crucial to have tools that can efficiently analyze and interpret satellite data to understand these impacts better.



## Code Files

### Main.ipynb

`Main.ipynb` performs image classification using ESRGAN and then further classification into the following categories:

- Agriculture
- Clear primary road
- Clear primary water
- Cloudy
- Haze primary
- Partly cloudy primary

Three models are applied for classification:

1. CNN
2. VGG
3. DenseNet

### ClimateForecasting.ipynb

`ClimateForecasting.ipynb` is dedicated to time series analysis. It works on a window size of 21 and analyzes the following parameters:

- Average temperature (`tavg`)
- Minimum temperature (`tmin`)
- Maximum temperature (`tmax`)
- Precipitation (`prcp`)
- Snowfall (`snow`)
- Wind direction (`wdir`)
- Wind speed (`wspd`)
- Wind peak gust (`wpgt`)
- Pressure (`pres`)

This analysis provides insights into climate trends and patterns over time.

## Usage

Each notebook provides detailed explanations of the code and its functionality. You can run the notebooks in a Jupyter environment or any compatible platform.



## Getting Started

To use the best model identified through our research, follow these steps:

1. Clone the repository:

    ```
    git clone <https://github.com/ifyweezle/AdvancePractice>
    ```

2. Extract the `Webapp.zip` file:

    ```
    unzip Webapp.zip
    ```

3. Navigate to the extracted folder using the command line.

4. Install the required Python libraries. You can do this using pip:

    ```
    pip install -r requirements.txt
    ```

## Usage

Once you have set up the environment and installed the necessary libraries, you can run the application using Streamlit. The primary Python script for running the application is `app.py`. 

To run the application, execute the following command:
    ```
    streamlit run app.py
    ```


## Contributions

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
