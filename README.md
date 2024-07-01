

# Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

![Farmer in a field](farmer_in_a_field.jpg)

## Overview

Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints.

Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

## Dataset

The dataset used in this project includes the following features:
- `"N"`: Nitrogen content ratio in the soil
- `"P"`: Phosphorous content ratio in the soil
- `"K"`: Potassium content ratio in the soil
- `"pH"`: pH value of the soil
- `"crop"`: Categorical values that contain various crops (target variable)

Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the `"crop"` column is the optimal choice for that field.

## Installation

To run this project, you need to have Python and Jupyter Notebook installed on your machine. You can install the required packages using `pip` and the `requirements.txt` file.

1. Clone the repository:

    ```bash
    git clone https://github.com/https-404/CropsModel-scikitlearn.git
    cd CropsModel-scikitlearn
    ```

2. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Launch Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

5. Open the `cropsModel.ipynb` file in Jupyter Notebook to run the project.

## Usage

After opening the `cropsModel.ipynb` file in Jupyter Notebook, you can run the cells in the notebook to see the analysis and results. Make sure to follow the instructions within the notebook to understand how the data is processed and how the model is used to predict the best crops.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome all contributions that can help improve the project.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any questions or suggestions, please feel free to open an issue or contact us at areesh.192003@gmail.com

---

