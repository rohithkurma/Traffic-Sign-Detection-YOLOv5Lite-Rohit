# Traffic Sign Detection using YOLOv5-Lite

This project implements a real-time traffic sign detection system using a lightweight YOLOv5-Lite model, optimized for resource-constrained edge devices such as the Raspberry Pi 5. It enables autonomous navigation support by detecting key traffic signs and triggering corresponding actions.

## 📌 Key Features

- Real-time object detection on Raspberry Pi 5 using YOLOv5-Lite
- Custom-trained model on traffic signs (turn left, turn right, stop, honk, etc.)
- Optimized for speed and accuracy using a lightweight PyTorch model
- Python-based control logic for action mapping (e.g., movement commands)
- Modular design for integration with robotic platforms

## 🧰 Tools & Technologies

- Python
- YOLOv5-Lite (PyTorch)
- OpenCV
- Raspberry Pi OS
- Pi Camera (IMX219 or compatible)
- GPIO control for motors and sensors

## 🛠️ System Overview

1. A Pi camera captures frames in real-time.
2. YOLOv5-Lite detects traffic signs in the frame.
3. The detected sign is mapped to a predefined robot action.
4. The robot adjusts its direction or behavior based on the sign.


## 📷 Sample Output

*Real-time detection output showing bounding boxes and labels on detected signs.*  
(Working On it)


## 👨‍💻 Author

**Rohit **  
Traffic Sign Detection | Autonomous Robotics | YOLOv5  
[LinkedIn](https://www.linkedin.com/in/rohit-kurma-2a7249274/) • [Email](rohitkurma2000@gmail.com)


