# 🤖 Dr. Cui's FURP Research Group (2026)

> **FOSE Undergraduate Research Project (FURP)**
> School of Engineering | Artificial Intelligence, Robotics, and Operations Research

Welcome to the 2026 FURP GitHub Organization for Dr. Cui's research group! This year, our lab focuses on cutting-edge intersections between **Autonomous Mobile Robots (AMRs), Reinforcement Learning, and Next-Generation Logistics Optimization**. 

Our philosophy is simple: bridge the gap between classroom theory and the real-world research frontier through rigorous simulation, mathematical modeling, and hands-on deployment.

---

## 🔬 Our Research Projects (2026)

This year, we are offering four distinct, highly challenging, and deeply rewarding research tracks. Students are expected to choose one track to focus on for their FURP journey.

### 1. [Vision-Language Navigation for Smart Warehouse AMRs](./VLN_README.md)
Tired of blindly obedient robots following absolute coordinates? In this project, you will build a digital-twin simulation using ROS 2 + Nav2 + Isaac Sim, and inject a Large Vision-Language Model (VLM) so the robot can understand and navigate via natural human language commands (e.g., *"Go to the blue shelf on the left"*).

### 2. [RL Balance & Roll: Reinforcement-Learning Control of a Ballbot](./RL.MD)
Throw out traditional manual math controllers. You will use NVIDIA IsaacLab to train thousands of digital robots simultaneously using Deep Reinforcement Learning (Trial and Error). You will start by teaching a two-wheeled robot to balance, scale up to a highly complex omni-directional Ballbot, and finally deploy your AI brain onto physical hardware in our Control Systems Lab (Sim2Real).

### 3. [HVRP-Connect: Hybrid Vehicle Routing Problem Combining UAVs and Autonomous Vehicles](./VRP.md)
Tackle the modern "Last-Mile Delivery" crisis. You will design advanced mathematical models and metaheuristic AI algorithms to coordinate a massive delivery truck acting as a "mobile aircraft carrier" for drones. It involves optimization mathematics, simulating downtown traffic (SUMO + AirSim), and multi-agent ROS 2 synchronization.

### 4. [Swap-N-Charge VRP: Energy-Aware Routing with Opportunistic Battery Exchange](./SWAP.md)
Solve the "Range Anxiety" of commercial EV fleets. You will build an algorithmic routing engine that acts like a smart human on a road trip—constantly calculating energy consumption and dynamically detouring to Battery Swap Stations (BSS) only when strategically necessary to prevent the fleet from dying mid-route.

---

## 🎓 Evaluation & "The 9-Node System"

This year, to ensure structured progress and prevent end-of-semester burnout, **every project in this organization is strictly divided into exactly 9 Milestones (Nodes)**. 
- **1/3** Introduction & Mathematical/Software Foundations
- **1/3** Core Algorithm Implementation & Baseline Reproduction
- **1/3** Innovation, Dynamic Simulation, or Sim2Real Hardware Deployment

### 🏆 How to Earn Your FURP Certificate:
To successfully complete the program and receive your official certificate, you **must** meet the following three criteria:
1. **Pass the 50% Threshold**: You must successfully complete (and push code for) at least **5 out of the 9 Nodes** configured for your specific project.
2. **Submit a Poster**: You must design and submit a formal academic poster summarizing your methodology and results to the annual end-of-year **FURP Showcase Event**.
3. **Maintain Repository Standard**: All project evaluations are solely based on your personal GitHub repository within this organization.

---

## 🛠️ Getting Started & Repository Rules

Instead of generic weekly notes, each student is required to create and maintain their own comprehensive project repository within this organization.

1. **Create Your Repo**: Name your repository strictly as `FirstnameLastname-ProjectKeyword` (e.g., `JohnDoe-VLN` or `JaneSmith-SwapVRP`).
2. **Copy the Template**: Copy the specific `README.md` from your chosen project track into your new repository. It will serve as your personal milestone tracker.
3. **Weekly Logs**: You must maintain a `/logs` folder in your repository to document weekly progress, blockers, and technical decisions.

### 💡 Git Best Practices
We operate like a professional software engineering and R&D team. We strongly encourage all students to make full use of Git for version control. It serves as valuable practice for your future career.
- Make frequent, atomic commits with clear descriptions (e.g., `feat: implement energy drain math model` rather than `update code`).
- If you are new to version control, here is a handy [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf) provided by GitHub Education.

Good luck, and we look forward to seeing your research breakthroughs this year! 🚀
