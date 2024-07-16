# Personal Carbon Calculator

This project is a Streamlit-based web application that calculates an individual's carbon footprint based on various daily activities such as transportation, electricity usage, diet, and waste generation. The application provides a user-friendly interface to input data and displays the results in a clear and concise manner.

## Table of Contents
1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Example](#example)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgements](#acknowledgements)

## Features

- **Calculate carbon emissions** from daily commute, electricity consumption, diet, and waste.
- **Provides annual carbon footprint** based on user inputs.
- **Displays carbon emissions by category** and the total carbon footprint.
- **Compare your carbon footprint** with the average per capita emissions.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment:**

    - On Windows:

        ```bash
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```bash
        source venv/bin/activate
        ```

4. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application:**

    ```bash
    streamlit run carbon_pro.py
    ```

## Usage

1. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).
2. Select your country (currently only India is supported).
3. Input your daily commute distance, monthly electricity consumption, weekly waste generation, and the number of meals per day.
4. Click on the **Calculate CO2 Emissions** button to see your results.

## Example

Here's an example of how to use the calculator:

- **Country:** India
- **Daily commute distance:** 20 km
- **Monthly electricity consumption:** 9.19 KWH
- **Weekly waste generation:** 10.99 kg
- **Number of meals per day:** 3

![image](https://github.com/user-attachments/assets/2b43230a-c785-466d-b9e6-ca6693a9557c)
![image](https://github.com/user-attachments/assets/5dc04b0d-7441-4755-bd0a-a13e0efc6a54)



Click the **Calculate CO2 Emissions** button to see the carbon emissions by category and the total carbon footprint.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. **Fork the repository.**
2. **Create a new branch** (`git checkout -b feature/your-feature-name`).
3. **Commit your changes** (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/your-feature-name`).
5. **Create a new Pull Request.**

## Acknowledgements

- **Streamlit** for providing the framework to build this web application.
