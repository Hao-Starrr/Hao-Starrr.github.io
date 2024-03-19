---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
sitemap: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **University of Pennsylvania, 2023-2025 (Expected)**

  - Master of Engineering in Robotics
  - GPA: 4.0/4.0
    <br />

- **The Chinese University of Hong Kong, 2019-2023**

  - Bachelor of Engineering in Mechanical and Automation Engineering
  - **Rank 1/128**, Overall GPA: 3.81/4.00, Major GPA: 3.94/4.00
  - Exchanged to University of Toronto in Robotics, 3 graduate-level courses with A/A+ grade in junior year.
  - Elite Scholarship (4 years), Yu To Sang Memorial Scholarship (3 years) and total 16 scholarships and honors over 120k HKD.
  - Ranked top 0.3% in the National College Entrance Exam. Top 10 in Shanghai Jiao Tong University’s Independent Admissions Exam.
    <br />

## Research and Intern Experience

**The Fabric Workshop and Museum**
<span style="float:right;">Dec. 2023 – March 2024</span>  
_Robotics Engineer, Part-Time_
<span style="float:right;">_Philadelphia, United States_</span>

- Build a 6 degree of freedom Stewart Platform and developed end effector position control system, self-calibration system in C++ can following human movement based on analytical inverse kinematics.
- Developed and trajectory tracking and polynomial interpolation for movement smoothing with desired trajectory recorded by Vicon Motion Capture System.

**Hong Kong Centre for Logistics Robotics**
<span style="float:right;">Oct. 2022 – Mar. 2023</span>  
_Software Engineer Intern_
<span style="float:right;">_Hong Kong_</span>

- Deployed topological sparse graphs generation for pre-build volumetric maps, filled the gap between drone mapping and planning based on **CUDA**, achieved autonomous exploration of environment without human intervention.
- Developed high compression ratio map saving and loading functions by serialization in **C++** integrated with **Protobuf**, decreasing the size by 40%, enabling multiple drones to share the rough pre-built maps and refine the exploration with multiple speed.
- Deployed **Fast-planners** on real-world unmanned air vehicle, successfully automatically controlled the drone in digitalized building 3D point cloud models which is built by on-board GPU increasing the mapping speed 10 times.

**University of Toronto Institute for Aerospace Studies**
<span style="float:right;">May 2022 – Aug. 2022</span>  
_Research Assistant_
<span style="float:right;">_Toronto, CA_</span>

- Researched convex optimization algorithms (SDP relaxation) for robot sensors trajectory alignment, resulting in certifiable optimization in targetless environments. Improved sensor accuracy and efficiency in hand-eye calibration.
- Developed a **GN solver** for scaled cloud point registration in **Python**, implemented relaxation in **CVXPY**, enabling the algorithm used on monocular camera, expanding the applicability to various robotic systems.
- Innovatively derived the Lie algebra pose perturbation model. Intergraded our system with **ORB-SLAM3** and analyze the trajectory with ground truth, showing our method achieve over 80% optimal with 100% translation noise.

**BlockStudio Qianzhi Technology Ltd. (Startup)**
<span style="float:right;">June 2021 – Sept. 2021</span>  
_Automation Engineer Intern_
<span style="float:right;">_Shenzhen, China_</span>

- Designed, built and tested differential conveyor belt plan and vibrating plate plan for toy blocks separation, achieving a 95% success rate and reduced manual inspection requirements.
- Intergrated and tested computer vision algorithm in **OpenCV** for block counting, achieved autonomous quality inspection for blocks production.
- Modeled the blocks assembly line using **SolidWorks** and regulated the process, achieved autonomous weighing and selection of building blocks.

## Competition

**2023 Grant Theft Autonomous**  
Nov. 2023 - Dec. 2023

- Led the team in developing an autonomous robot equipped with infrared sensors, **Vive** system, **TOF**, capturing trophies without visual assessment, culminating in **Championship** among 40 teams and interview featured on UPenn campus newspaper.
- Independently designed the architect of robot including 7 modular systems, made decisions on every details of structure design, electrical layout, library chosen, algorithms and strategies, scored highest in a single game.
- In charge of the project timelines, task distribution, presentations, managed code by **Git**, ensuring efficient project execution and being the first team checked with full extra credits.
- Developed **HTML** page using HTTP for robot control and implemented communication protocols in ESP-NOW, along with **PID** controller, leading to improved operational efficiency.

**2023 Pick and Place Challenge**  
Nov. 2023 - Dec. 2023

- Achieved a record-breaking score for the course with 8 blocks. Emerged as the **Champion** in the GRASP Lab annual competition of 20 teams.
- Developed a noise elimination and axis alignment algorithm for block detection integrated with **Kalman filter**, enhancing the accuracy and robustness of the system, and making grabbing success rate as 100%.
- Implemented the **offline RRT\*** path planning algorithm compared with **Informed RRT\*** on Franka manipulator with the OOP principle, resolving challenges of collision with noise data with high operational efficiency.

**2021 National Engineering Practice Competition (Logistics Robot)**  
Jan. 2021 - June 2021

- Won **1st** place in Hong Kong, and **Silver Award** in the national final among 601 teams from 267 universities.
- Conceptualized and executed the robot’s design, including part selection, fabrication of non-standard parts using laser cutting, **CNC** and **3D printing**, and implementing vision object detection on **OpenMV**.
- Enhanced motion logic by incorporating additional tracking sensors and improved stability with **speed smoothing** techniques, increasing the robot’s reliability and speed.

## Leadership and Community Service

**Initiator of WEHEARD Program**  
Jan. 2023 - Apr. 2023

- Conducted in-depth research on the employment conditions of hearing-impaired persons (HIP) in the food delivery industry in Hong Kong.
- Collaborated with NGOs, restaurants, and HIP deliverers to gather insights and identify challenges faced by HIPs.
- Developed a comprehensive First-stage Report, highlighting the employment situation, difficulties with phone communication, and unfair policies in the industry.
- Created a documentary showcasing the daily struggles of an HIP deliverer and uploaded it on YouTube, generating over 350 views and positive feedback.
- Find the link [here](https://weheard.github.io/).

**Captain of CUHK Mandarin Debate Team**  
May 2020 - May 2021

- Coordinated a team of 120+ members and prepared over 9-hours-weekly training and managed logistics for 10+ international competitions, monthly reading sharing sessions. Organized and hosted over 100 mock competitions within one year.
- Conducted two rounds of recruitment interviews with 121 candidates, overseeing 30 helpers, time management, documentation, and selection processes.
- Revolutionized information management and communication for team by implementing a streamlined system with Gmail and Google Calendar for effective notifications and team coordination. Established comprehensive file organization protocols and operational procedures, leading to enhanced efficiency and standardization, significantly improving team synchronization and operational automation. The standards are continually used until now.

**Founder of 2021 Exemplar Tournament Freshman Mandarin Debate Competition**  
March 2021 - May 2021

- Founded the "Exemplar Tournament" Freshman Mandarin Debate Competition, the first international Mandarin debate competition initiated by CUHK. Secured funding of more than 14,000 HKD from the university. Promoted the competition extensively on the CUHK Office of Student Affairs homepage.
- Drafted the Tournament Regulations, effectively handled multiple emergencies throughout the 2-month competition period, and facilitated team registration for more than 50 universities and debate clubs worldwide.

## Skills

Programming: C/C++, Python (SciPy, NumPy, PyTorch, CVXPY), MATLAB (Simulink)

Framework: ROS/ROS2 (Gazebo, Rviz, MoveIt!, OMPL), CUDA, Qt, Arduino, Embedded Programming

Software: Git, SolidWorks, CAD
