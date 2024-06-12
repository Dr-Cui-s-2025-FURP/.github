
# :robot: Dr. Cui's FURP Project (Summer 2024)
Research and Development of AMR Fleet Meta-Universe Simulator & Marker-Free 6D Motion Capture System 

## :gear: Basic Environment
To participate in this project, it's recommended that you set up your environment with the following:

Operating System: Ubuntu 20.04 LTS / Ubuntu 22.04 LTS

Simulation Platform: Omniverse Isaac sim （compulsory for AMR group）
 
## :books: Documentation & Resources
Below are some valuable resources and documentation to help you get acquainted with the tools and platforms we'll be using:

**Isaac Sim:**

[NVIDIA Isaac Sim](https://developer.nvidia.com/isaac-sim)

[Getting Started](https://docs.omniverse.nvidia.com/isaacsim/latest/core_api_tutorials/tutorial_core_hello_world.html)

[Tutorial](https://www.bilibili.com/video/BV1Cs4y1a7hS/?share_source=copy_web&vd_source=fc0fccd172256256b42fd83530583747)

**ROS**

[ros-noetic (recommended)](https://www.ros.org/)

**PyTorch**

[PyTorch](https://pytorch.org/)
 

## :chart_with_upwards_trend: Progress
### Week 1-2

**Autonomous Mobile Robots (AMR) Group**
All team members are expected to go through the Isaac Sim tutorials.
Individuals should try to replicate the tutorial results to gain hands-on experience with the simulation environment.
Familiar with ROS (Robot Operating System).
Practical exercises and experimentation with ROS are encouraged to understand the basics of robot software development.
1. Begin setting up a simple environment within Isaac Sim, you can use the built-in environment.
2. Select any of the built-in AMR models and configure it.
3. Make the built-in AMR auto-move by commands.
4. Focus on enabling the AMR to perform basic tasks such as moving from one point to another and obstacle avoidance.

**Motion Capture System Group**
For neural network code implementation work, we recommend using PyTorch (with CUDA, make good use of your GPU resource)

1. Learning CNN (Convolutional Neural Networks)
  - Dive into the fundamental concepts of CNNs, which are vital for understanding many computer vision tasks.
  - Explore various architectures and applications of CNNs in the context of motion capture and object recognition.

2. Replicating **PoseCNN** and **PointNet** Algorithms
  - Study and replicate the PoseCNN algorithm, which is designed for object detection and pose estimation in images.
  - Similarly, work on understanding and implementing the PointNet algorithm, which processes point cloud data for classification and segmentation tasks.
  - Document the replication process, challenges, and outcomes as part of your weekly reports.

3. Data Collection
  - Begin the practical work of collecting data by setting up sensors and ensuring time synchronization among multiple sensors.
  - Document the setup process, data collection methodology, and any preliminary results.
Lab Work Requirement:
- Some aspects of data collection will require access to the physical lab environment.
- Ensure you schedule lab time in advance to perform the necessary experiments and data collection sessions.

 
## :raising_hand: Contributing
Please create a repo in our GitHub organization, naming your name + 'weekly report', then write an one-page learning note per week.

## :memo: Notes
To be eligible for the final FURP certificate the faculty provides, participants must demonstrate consistent and reasonable progress throughout the project. All software-related progress must be clearly documented on GitHub within your repository. This includes:

- Weekly reports
- Code commits
- Result updates

### Weekly Report Guidelines
Your weekly reports are a crucial part of your project documentation. They should be committed to a specific folder in your repository and must include the following:

1. Literature Review
   - Conduct a review of papers and articles related to your project's topic.
   - Summarize the key points, methodologies, and findings of the literature you've reviewed.
   - Reflect on how this literature informs or impacts your project work.
2. Code Implementation Process
   - Document your weekly progress in terms of code development or algorithm replication.
   - Include details about the specific tasks you've worked on and any challenges you've encountered.
   - Share the results of your implementation, including any output data, graphs, or operational insights.
It is essential to maintain this documentation rigorously as it will not only contribute to your learning experience but also serve as an evaluation tool for your involvement and performance in the project.

### :thumbsup: Good Practice
We strongly encourage all contributors to make full use of Git for version control. This not only ensures a robust workflow but also serves as valuable practice for your software engineering skills.

To help you get started or to serve as a quick reference, here's a handy [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) provided by GitHub Education. It covers the most common Git commands and workflows that you'll likely use while contributing to this project.

Remember, becoming proficient with Git is a crucial skill in your software engineering toolkit. It allows for better collaboration, code management, and understanding of the software development lifecycle. 

