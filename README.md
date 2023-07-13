# Enhancing-Hospital-Efficiency-Through-Web-Deployed-Object-Detection
Enhancing Hospital Efficiency Through Web-Deployed Object Detection: A YOLOv8-Based Approach for Automating Healthcare Operations


Overview

This repository contains the complete resources and codebase for our project: "Enhancing Hospital Efficiency Through Web-Deployed Object Detection". This project primarily aims to facilitate hospital procedures and improve efficiency through the power of Object Detection technologies. The project is built on the robust YOLOv8 object detection model and provides a web-deployed application interface built with React.js.

The repository contains frontend resources in React.js that load the YOLOv8 model, allowing users to run the application on their devices. It also features a conversion pipeline to export the YOLOv8's best.pt model to the ONNX format and further into TensorFlow.js. This transformation ensures the model can be successfully read and used by the React application.

In addition to the source code, the repository provides a video showcasing the application's running on an iPhone and a comprehensive Jupyter Notebook documenting the training process of the YOLOv8 model, performed in a Google Colab environment.
Repository Structure

    frontend/ - This directory contains the React.js frontend code which loads the YOLOv8 model.
    model_export_tfjs/ - This file holds the scripts used to convert the YOLOv8 best.pt model to ONNX and then to TensorFlow.js.
    results/ - A folder hosting a video demo of the React application running on an iPhone.
    TRAINING_YOLOV8_HOSPITAL_128.ipynb/ - This file includes a Jupyter Notebook detailing the model training process carried out in Google Colab.

Getting Started

    Clone this repository:

bash

git clone https://github.com/agsmilinas/Enhancing-Hospital-Efficiency-Through-Web-Deployed-Object-Detection.git

    Navigate to the react-app/ directory and install dependencies:

bash

cd react-app/
npm install

    To run the React.js frontend locally, execute:

bash

npm start

Model Conversion

To convert the YOLOv8 model to a format usable by the React app, follow the scripts in the model-conversion/ directory. Detailed instructions are provided in the respective directory.
Model Training

The training process for the YOLOv8 model is documented in a Jupyter Notebook stored in the model-training/ directory. You can view this notebook to understand the development and training of the model.
Demo Video

Visit the demo-video/ directory to view a video demonstrating the React application's operation on an iPhone.
Contributing

Contributions, issues, and feature requests are welcome! Please adhere to our contributing guidelines when submitting any changes.
