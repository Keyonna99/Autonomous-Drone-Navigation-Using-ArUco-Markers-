# Autonomous-Drone-Navigation-Using-ArUco-Markers-

This project involved the development of an autonomous drone navigation system capable of detecting and navigating to predefined ArUco markers using computer vision techniques.

The drone was programmed to identify visual markers in its environment and autonomously fly to specific target positions without manual control.

This project was completed as a collaborative team effort, with a focus on autonomous flight control and computer vision integration.

⸻

My Role

As part of the team, my primary responsibilities included:
	•	Generating custom ArUco markers using Python and OpenCV
	•	Implementing marker detection logic
	•	Developing autonomous waypoint navigation logic
	•	Programming flight behavior for movement toward detected markers
	•	Assisting in debugging and real-world flight testing

⸻

Problem Statement

Manual drone navigation limits scalability and precision in real-world applications such as:
	•	Warehouse automation
	•	Search and rescue
	•	Inspection systems
	•	Smart delivery systems

This project aimed to simulate an autonomous guidance system using computer vision markers as reference waypoints.

⸻

System Architecture

1️⃣ ArUco Marker Generation
	•	Generated unique ArUco markers using OpenCV
	•	Created visual identifiers for drone recognition
	•	Printed and positioned markers in physical space for testing

2️⃣ Marker Detection System
	•	Used OpenCV to detect ArUco markers from live camera feed
	•	Extracted marker ID and position
	•	Estimated pose for directional movement

3️⃣ Autonomous Flight Logic
	•	Calculated positional offsets between drone and marker
	•	Adjusted pitch, roll, yaw, and throttle dynamically
	•	Executed controlled movement toward target marker

4️⃣ Navigation Flow
	1.	Initialize drone connection
	2.	Activate camera feed
	3.	Detect ArUco marker
	4.	Compute relative position
	5.	Adjust flight direction
	6.	Stop when marker is reached

⸻

Technologies Used
	•	Python
	•	OpenCV
	•	ArUco Marker Library
	•	Drone SDK (e.g., DJI Tello SDK / MAVSDK depending on hardware)
	•	Computer Vision
	•	Real-time video processing

  Engineering Concepts Demonstrated
	•	Computer vision-based localization
	•	Real-time image processing
	•	Autonomous navigation algorithms
	•	Control systems logic
	•	Sensor-based movement correction
	•	Team-based software development

⸻

Challenges Overcome
	•	Noise and lighting affecting marker detection
	•	Flight instability during position correction
	•	Latency between camera feed and control commands
	•	Accurate marker pose estimation

⸻

Future Enhancements
	•	Multi-marker route planning
	•	SLAM integration
	•	Obstacle avoidance system
	•	PID control refinement
	•	GPS-assisted outdoor navigation
	•	AI-based object recognition integration

⸻

Impact

This project demonstrates applied computer vision, robotics control systems, and autonomous navigation — bridging software engineering and real-world hardware implementation.
  
