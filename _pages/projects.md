---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<table>
  <style>
    table {
      font-size: 16px; /* 设置表格内所有文本的字体大小为18px */
    }
  </style>
  <tr>
    <td width="20%"><img src="../images/stewart.gif" width="800" /></td>
    <td>
      <strong>6-DoF Stewart Platform 2024</strong> <br>   
      Supervised by Prof. Mark Yim, the director of GRASP Lab.
      <br> 
      • Developed a set of <strong>self-calibration algorithms</strong> for it to ensure the accuracy of motion control.<br>
      • Built <strong>PID</strong> position controller for linear actuators’ velocity feedback control with position sensor.<br>
      • Developed and trajectory tracking and <strong>polynomial interpolation</strong> with desired trajectory recorded by <strong>Vicon</strong> Motion Capture System.<br>
    </td>
  </tr>

  <tr>
    <td><img src="../images/510.jpg" width="800" /></td>
    <td>
      <strong>Grant Theft Autonomous 2023</strong><br>
      • Find the competition recording at <a href="https://www.youtube.com/watch?v=Pt5Qd4mry5I&t=9516s">GRASP Lab Youtube Channel</a>.<br>
    </td>
  </tr>

  <tr>
    <td><img src="../images/520.jpg" width="800" /></td>
    <td>
      <strong>Pick and Place Challenge 2023</strong><br>
      • Find the competition recording at <a href="https://www.youtube.com/watch?v=enAke8V9i44">GRASP Lab Youtube Channel</a>.<br>
    </td>
  </tr>

  <tr>
    <td><img src="../images/recon.png" width="800" />
    </td>
    <td>
      <strong>3D Reconstruction in Augmented Reality Context - Part1 2023</strong><br>
      • Implemented visual odometry by <strong>optical flow</strong> and visualized the depth map.<br>
      • Utilized <strong>SIFT</strong> matches and <strong>RANSAC</strong> estimated essential matrix to recover the pose and reconstructed 3D scene.<br>
    </td>
  </tr>

  <tr>
    <td><img src="../images/vr.gif" width="800" /></td>
    <td>
      <strong>3D Reconstruction in Augmented Reality Context - Part2 2023</strong><br>
      • Estimated the homography that maps the video images onto the Penn Engineering logo points.<br>
      • Established world coordinate system by AprilTags and solved <strong>PnP</strong> problem mapping objects to 3D view.<br>
    </td>
  </tr>
  
  <tr>
    <td><img src="../images/slam.png" width="800" /></td>
    <td>
      <strong>Differential Wheeled Robot Lidar SLAM in Indoor Environment 2022</strong><br>
      • Deployed <strong>PRM</strong> and <strong>RRT*</strong> indoors generating global path in 2.0 second in <strong>Gazebo</strong> simulation environment.<br>
      • Adapted <strong>MPC</strong> controller in dynamic state lattice following the trajectory, visualized by ROS <strong>Rviz</strong>.<br>
      • Implement <strong>EKF</strong> against particle filter as localization and achieve 80% time decrease and higher accuracy.<br>
      • Mapping by <strong>Bresenham's line algorithm</strong> with Lidar and wheel odometry data and corrected by loop closure.<br>
    </td>
  </tr>

  <tr>
    <td><img src="../images/map.png" width="800" /></td>
    <td>
      <strong>2D Path Planning Interface on OpenStreetMap 2022</strong><br>
      • Implemented <strong>DFS</strong>, <strong>BFS</strong>, <strong>Greedy Best First</strong> compared with A* planning algorithm on building dense 2D map.<br>
      • Improved <strong>weighted A*</strong> setting cost function based on real-time traffic and road conditions. <br>
      • Developed algorithm visualization GUI interface interact with mouse clicking by <strong>JAVA</strong>.<br>
    </td>
  </tr>

  <tr>
    <td><img src="../images/v.png" width="800" /></td>
    <td>
      <strong>Information Retrieval (Named Entity Recognition) using Hidden Markov Model 2022</strong><br>
      • Fitting the <strong>HMM</strong> transition and emission parameters with the train set of 6000 documents on MITMovie Dataset.<br>
      • Implemented <strong>Viterbi</strong> algorithm and Laplace smoothing achieving 98% accuracy on 2000 test documents.<br>
    </td>
  </tr>

  <tr>
    <td><img src="../images/car.jpg" width="800" /></td>
    <td>
      <strong>National Engineering Practice 2021</strong><br>
      In this project, we've custom-built a logistics cart from the ground up. It's designed to automatically detect the color of materials and adeptly place them in their designated spots on the shelves. <br>
      • Find video <a href="https://youtu.be/IHseo0RF8Oc">here</a>.<br>
      After implementing an array of sophisticated control strategies for tracking and precise positioning, we discovered that a finely-tuned hard-coded speed control, especially after refining the curve trajectories, offered the most reliable performance. This experience underscored a valuable lesson: complexity isn't inherently superior; adaptability and tailoring solutions to meet specific demands are crucial. Our approach paid off handsomely as we clinched the silver award in the national competition, standing out amongst over two hundred universities.<br>
      • The result was featured in <a href="https://www4.mae.cuhk.edu.hk/newsnawards/silver-award-in-the-national-finals-of-the-2021-china-university-students-engineering-practice-and-innovation-ability-competition/">the website of MAE department</a>.<br>
    </td>
  </tr>
  
</table>

with diagonal heuristic and cross tie breaker achieving 40 times improvement in sparse grid map.
