# Car Price Prediction

This repository contains a project for predicting car prices using machine learning techniques.
This repository also has a python app containerized using Docker.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Building Docker Image](#builddocker)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to build a machine learning model that can predict the price of a car based on various features such as make, model, year, mileage, and more.

## Dataset
The dataset used for this project contains information about various cars and their prices. It includes features such as:

| Feature       | Description                          |
|---------------|--------------------------------------|
| Make          | The manufacturer of the car          |
| Model         | The specific model of the car        |
| Year          | The year the car was manufactured    |
| Mileage       | The total distance the car has traveled (in miles) |
| Engine Size   | The size of the car's engine (in liters) |
| Horsepower    | The power output of the car's engine (in horsepower) |
| Transmission  | The type of transmission (e.g., automatic, manual) |
| Fuel Type     | The type of fuel the car uses (e.g., gasoline, diesel) |
| Price         | The price of the car (target variable) |

## Building Docker Image
Go to the required project directory:

```
prerequisite_projects/Car_Price/price_calc_app 
```

Build the Docker Image with the following command:

```
docker build -t car-price-app .
```

## Usage
Run the docker image with the following command:
```
docker run -d -p 8501:8501 car-price-app 
```

To access the app, visit this link in your web-browser:

```
http://0.0.0.0:8501
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.