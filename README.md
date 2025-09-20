Intelligent Traffic Control System 🚦

This project implements an Intelligent Traffic Control System using YOLOv3 (You Only Look Once), a real-time object detection algorithm. The system is designed to optimize traffic signal management at intersections by dynamically prioritizing lanes based on vehicle density and emergency vehicle detection.

🔑 Key Features

YOLOv3-based Detection: Detects and counts vehicles in each lane using real-time object detection.

Lane Scanning: Each lane is scanned for a fixed duration of 15 seconds to determine traffic density.

Dynamic Signal Allocation: The green light is assigned statically to the lane with the highest number of vehicles.

Emergency Vehicle Priority: Special priority is given to emergency vehicles (e.g., ambulances, fire trucks, police cars) to ensure they can pass through quickly.

Traffic Optimization: Reduces congestion and improves overall efficiency of traffic flow.

⚙️ How It Works

The camera feed from each lane is processed using the YOLOv3 model.

Vehicles are detected and classified in real time.

A counting mechanism determines the total number of vehicles in each lane during the 15-second scanning window.

The system assigns the green light to the lane with maximum density.

If an emergency vehicle is detected, its lane gets highest priority, regardless of density.

📌 Applications

Smart cities and intelligent transportation systems.

Emergency response support.

Real-time congestion management.

🛠️ Tech Stack

Python

YOLOv3 (You Only Look Once) for object detection

OpenCV for image/video processing

Deep Learning Frameworks (TensorFlow / PyTorch)
