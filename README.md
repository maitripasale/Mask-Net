
![enter image description here](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/masknet.png)
# Mask-Net

## Description

Mask-Net is an IOT device that can be easily attached with existing cameras or surveillance system for effective mask-based detection system. It consists of a Raspberry Pi, webcam and an Ultrasonic sensor. The device uses advanced Machine Learning models to detect whether a person is wearing a mask or not with an accuracy of 90-95%.

## Hardware
![enter image description here](https://github.com/maitripasale/Mask-Net/blob/main/image-057.jpg)
-   Webcam
-   Ultrasonic sensor
-   Speaker
-   LEDs
-   Jumper wires

![enter image description here](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/image-078.jpg)


## Software

-   Android app (Java)

1. Login Screen

![sign in using face](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/image-059.jpg)

1. Sign up using face

![enter image description here](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/image-060.png)

1. View Penalties

![enter image description here](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/image-028.jpg)

1. Pay Penalities

![enter image description here](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/image-029.jpg)

- Backend:
-   Database (SQLite, MongoDB)
-   Framework (TensorFlow, Keras, OpenCV, SKLEARN)
-   Server (Fast Api)
-   Cloud provider (Microsoft azure)
-   Cloud Technology (Azure Virtual Machine Server)

- Admin Dashboard

![enter image description here](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/image-030.jpg)

![enter image description here](https://raw.githubusercontent.com/maitripasale/Mask-Net/master/image-031.jpg)

## Functionality

1.  The ultrasonic sensor detects movement and triggers the camera to capture an image of the person at a distance of 100cm.
2.  The captured image is sent to the cloud server where the mask detection algorithm checks if the person is wearing a mask or not.
3.  If the algorithm detects the mask, a green light will light on the Raspberry Pi, and the image is stored in the database as a record.
4.  In the event of no mask being worn, a red light will glow, a buzzer will beep, and the admin will receive an SMS containing the picture of the person.
5.  The device also has an Android app and website for the admin, which includes features such as user authentication, display of all the events such as MASKED, UNMASKED, and Suspicious events with accurate photo of the person and time stamp.

## Aim & Objectives

Looking at the current pandemic situation, the aim of this project is to develop a software system to maintain people’s safety and to awaken people and introduce mask as new normal in their life. The device is particularly useful for monitoring employees without masks and sending them reminders to wear a mask at office premises. The ultimate goal is to prevent the spread of the corona virus.

## Installation

1.  Install the latest version of Python on your device.
2.  Install the required libraries and frameworks by running `pip install -r requirements.txt`
3.  Configure the device settings in the `config.py` file.
4.  Run the main script by executing `python main.py`

## Contributing

We welcome contributions to this project. If you are interested in contributing, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://chat.openai.com/chat/LICENSE.md) file for details.

## Acknowledgments

We would like to acknowledge the following for their support and contributions to this project:

-   [Dhruv2211patel](https://github.com/Dhruv2211patel)
