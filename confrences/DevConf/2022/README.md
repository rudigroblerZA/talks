# Self-Driving Cars Using GTA and Deep Learning
**Version:** 1.0.6  
**Speaker:** @rudigrobler  

## Abstract
This talk explores an experimental journey into building self-driving car models using *Grand Theft Auto V* (GTA V) as a simulated environment combined with deep learning techniques. The presentation outlines how realistic driving data can be collected from a modifiable game world, processed through machine learning models (including transfer learning and regression), and used to train autonomous driving behaviors. It highlights system architecture, challenges, and lessons learned while showcasing how gaming, AI, and engineering intersect to make self-driving experiments accessible and fun, even for hobbyists.

## Summary
### Overview
This presentation explores how deep learning techniques can be applied to create self-driving car models, using *Grand Theft Auto V* (GTA V) as a simulation environment for data collection and training. The talk blends concepts from autonomous driving, computer vision, and machine learning, demonstrating an experimental setup and architecture for building and testing such systems.

### Key Topics Covered

#### 1️⃣ What is self-driving?
- A self-driving car is a vehicle capable of sensing its environment and moving safely with little or no human input.
- References real-world efforts: Tesla Autopilot, comma.ai, OpenPilot, and Waymo.
- Highlights the complexity of self-driving technology — challenging but achievable through various approaches and techniques.

#### 2️⃣ Components and tasks of self-driving systems
- **Tasks:** 
  - Adaptive cruise control (longitudinal movement)
  - Steering (lateral movement)
  - Lane line detection
  - Image segmentation
  - Object detection
  - Image classification
  - Road following
- **Sensors:** 
  - Cameras for vision
  - IMU, gyroscopes, accelerometers for motion
  - Speedometer, GPS, and maps for car status

#### 3️⃣ Why use GTA V?
- Chosen for its:
  - Modifiability (supports scripting, data extraction)
  - Open-world and realistic environment
  - Fun, flexible sandbox
- Enables recording:
  - Realistic driving scenarios (day/night, weather variations)
  - Car state (speed, steering, throttle, brake, etc.)
  - Diverse trips and drivers

#### 4️⃣ Data collection process
- Trips recorded from point A to B (~10 mins at 7 fps)
- Varied conditions (day/night, rain/sunshine, time of day)
- Multiple drivers and cars for data diversity
- Data includes:
  - Video frames (800x600 RGB)
  - Correlated car states (steering angle, throttle, brake)

#### 5️⃣ Deep learning approach
- Techniques:
  - Transfer learning
  - Regression
  - Use of models like ResNet, AlexNet
- Frameworks use GPU acceleration
- Demos on training and evaluation

#### 6️⃣ System architecture
- Distributed using **ZeroMQ (ZMQ)** for communication
- Components:
  - Screen/car state publishers & subscribers
  - Control server/client
- Runs on Windows (Dell) + Ubuntu (NVIDIA Jetson Nano)

#### 7️⃣ Development disclaimers
- Speaker notes:
  - Not a Python developer, AI expert, or gamer
  - All code available (mostly Jupyter notebooks)
  - Over-engineered for fun and learning

#### 8️⃣ Summary of key message
- Machines can learn human tasks through pattern recognition
- The collect → train → evaluate cycle applies beyond driving: fruit sorting, security systems, etc.

## Takeaways
- GTA V is a flexible, low-cost platform for self-driving experiments.
- Combining game data and deep learning provides a safe, fun way to explore AI.
- The project demonstrates that advanced AI work can be accessible to enthusiasts.
