# Drivers Drowsiness Detection using Deep Learning

## Overview

This project aims to enhance road safety by detecting driver drowsiness using deep learning techniques. Drowsy driving is a major cause of accidents, and this system helps mitigate risks by alerting drivers when signs of drowsiness are detected.

## Features

- Real-time monitoring of driver's facial expressions and eye movements.
- Utilizes a deep learning model for robust drowsiness detection.
- Immediate alerts through visual and auditory signals when drowsiness is detected.
- User-friendly interface and easy integration into existing vehicle systems.

## Requirements

- Python 3.x
- OpenCV
- TensorFlow
- Dlib
- Playsound
- Dataset Link:- http://mrl.cs.vsb.cz/eyedataset

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Driver-Drowsiness-Detection-using-Deep-Learning.git
   cd drivers-drowsiness-detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main script:
   ```bash
   python drowsiness_detection.py
   ```

2. Adjust settings in the configuration file (`config.yaml`) as needed.

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to [Dlib](http://dlib.net/) and [OpenCV](https://opencv.org/) for their invaluable contributions to computer vision.

Feel free to modify this README to suit your project's specific details and structure.

Data Preparation has been updated with train and test folder split automation.

