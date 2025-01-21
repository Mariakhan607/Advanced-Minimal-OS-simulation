# Advanced-Minimal-OS-simulation
Advanced Minimal Operating System Simulation
Team Members:
* Isra Abbas: 2023S-BCYS-031

* Maria Khan: 2023S-BCYS-030

Project Overview:
This project presents a simulation of a minimal operating system that integrates advanced features such as process scheduling, memory management, and system call handling. The implementation leverages a graphical user interface (GUI) for seamless user interaction, enabling inputs like process arrival times, burst times, priority levels, and memory allocation parameters. The simulation serves as an educational tool for comprehending foundational operating system concepts.

Objectives:
1. Process Scheduling:
- Implement efficient scheduling algorithms, including:
 - Round-Robin (RR) with time quantums.
 - Priority Scheduling.
 - Shortest Job First (SJF) scheduling.
- Provide real-time visualization for enhanced learning.

2. Memory Management:
- Simulate dynamic allocation and deallocation mechanisms.

3. System Calls:
- Provide a robust interface for user programs to request OS services.

4. Graphical User Interface:
- Develop an intuitive GUI for simplified interaction and enhanced user experience.

Key Features:
1. Interactive Process Scheduling:
- Supports user-defined inputs for process attributes: arrival time, burst time, priority, etc.
- Implements the following algorithms:
 - Round-Robin: Time-slice-based scheduling with visualized queue updates.
 - Priority Scheduling: Real-time representation of process execution based on priority levels.
 - Shortest Job First (SJF): Highlights shortest processes in each cycle dynamically.
- Real-time graphical representation of scheduling progress.

2. Dynamic Memory Management:
- Simulates memory allocation and deallocation with visual feedback.
- Enables users to define memory blocks and monitor utilization.

3. System Call Interface:
- Facilitates communication between user programs and the OS simulation.

4. Advanced GUI:
- User-friendly design for easy navigation and interaction.
- Provides a dashboard for monitoring system states (e.g., CPU usage, memory state) in real time.

Tools and Technologies:
* Programming Language: C

* GUI Framework: GTK+ and Qt

Development Process:
1. Requirement Analysis:
- Defined core functionalities, including scheduling algorithms and GUI requirements.

2. Design Phase:
- Architected modular components for process scheduling, memory management, and GUI.
- Designed GUI mockups for usability testing.

3. Implementation:
- Developed backend logic in C for scheduling algorithms.
- Integrated GUI with system processes for real-time interaction.

4. Testing:
- Conducted unit and integration tests for accuracy and performance.
- Validated GUI responsiveness and user experience.

5. Documentation:
- Created comprehensive user and developer manuals.

Challenges and Solutions:
1. Real-Time Synchronization:
- Challenge: Synchronizing GUI updates with backend processes.
- Solution: Implemented efficient threading and event-handling mechanisms.

2. Scalability:
- Challenge: Extending functionalities without compromising simplicity.
- Solution: Designed a modular architecture for easy feature addition.

3. GUI Integration:
- Challenge: Creating a seamless GUI for technical concepts.
- Solution: Used modern frameworks and conducted iterative user testing.

Conclusion:
The Advanced Minimal Operating System Simulation combines essential OS principles with a modern, interactive GUI to provide a practical and engaging learning experience. By integrating Round-Robin, Priority, and Shortest Job First scheduling algorithms alongside dynamic memory management and system call handling, the project bridges the gap between theoretical knowledge and hands-on application. This makes it a valuable resource for understanding and applying core OS concepts.
