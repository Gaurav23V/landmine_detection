# Landmine Detection Model

This repository contains a Jupyter Notebook implementation of a landmine detection model using the YOLOv8 object detection algorithm. The model is trained on a dataset obtained from Roboflow.

## Dataset

The dataset used for training the model was downloaded from the Roboflow website. It consists of images of various terrains containing landmines, with bounding box annotations for the landmine objects. The dataset was preprocessed and organized into the required format for use with YOLOv8.

## Model

The landmine detection model is built using the YOLOv8 object detection algorithm, which is a state-of-the-art real-time object detection system. YOLOv8 is known for its high accuracy and fast inference speed, making it suitable for real-time applications such as landmine detection.

The model is implemented in a Jupyter Notebook, which provides a convenient environment for exploratory data analysis, model training, and evaluation.

## Requirements

To run the Jupyter Notebook and train the model, you'll need the following dependencies:

- Python (version 3.6 or higher)
- Jupyter Notebook
- PyTorch
- YOLOv8 (latest version)
- Other required Python packages (specified in the Notebook)

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies (listed above).
3. Open the `landmine_detection.ipynb` Jupyter Notebook file.
4. Follow the instructions in the Notebook to preprocess the data, train the model, and evaluate its performance.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The dataset was obtained from [Roboflow](https://roboflow.com/).
- The YOLOv8 object detection algorithm was developed by [Ultralytics](https://github.com/ultralytics/ultralytics).