# 🦾 PROJECT: THE VERTICAL HAND SUBSYSTEM
**Goal**: Build a production-grade C++/ROS2 control stack for a 5-DOF dexterous hand in simulation.

## 🗺️ PROJECT SUMMARY
A "Vertical" slice of Figure AI's Hand Subsystem. From **Motor Control** (Embedded) to **Grasp API** (Integration).

| Phase | Days | Name | Focus | Key Deliverable |
| :--- | :--- | :--- | :--- | :--- |
| **I** | 1-25 | **The Nerves** | Embedded / Control | 1kHz C++ PID loop in Docker/ROS2. |
| **II** | 26-50 | **The Skeleton** | Planning / Kinematics | Inverse Kinematics (IK) solver for 5 fingers. |
| **III** | 51-75 | **The Eyes** | Perception / Bridge | Python/AI node detecting "Grasp Points" via camera. |
| **IV** | 76-100| **The Brain** | Integration / Polish | Full "Pick & Place" autonomous loop + Dockerized CLI. |

## 📊 THE 100-DAY ROADMAP

| Day | Task | Status | Notes |
| :--- | :--- | :--- | :--- |
| **01-05** | **Environment Setup** | ⏳ | Docker + ROS2 Humble + VS Code Dev Containers. |
| **06-15** | **The Mock Hand** | ⏳ | Create a C++ Node that simulates motor feedback. |
| **16-25** | **PID Tuning** | ⏳ | Implement a real-time control loop for smooth movement. |
| **26-40** | **Math & IK** | ⏳ | Calculate 3D joint angles (Eigen library). |
| **41-50** | **Simulation (Isaac)** | ⏳ | Spawn the Hand URDF in NVIDIA Isaac Sim. |
| **51-70** | **Vision Bridge** | ⏳ | Integrate a pre-trained model to "see" the object. |
| **71-85** | **The API** | ⏳ | Build the high-level `hand.grasp()` interface. |
| **86-100**| **The Final Flex** | ⏳ | Automated test suite + GitHub Demo Video. |

## 🛠️ THE STACK (PARETO 20/80)
*   **Language**: Modern C++ (20), Python (Testing).
*   **Middleware**: ROS2 Humble.
*   **Infra**: Docker, GitHub Actions (CI/CD).
*   **Sim**: NVIDIA Isaac Sim / Gazebo.
*   **Math**: Eigen / KDL (Kinematics).
