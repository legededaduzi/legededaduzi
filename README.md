<!--
  GitHub Profile README — XinJie Zhang
-->

<p align="right">
  <strong>English</strong>
  &nbsp;·&nbsp;
  <a href="./README.zh-CN.md">简体中文</a>
</p>

<div align="center">
<div align="center">
  <img
    src="./assets/profile/scens.gif"
    width="100%"
    height="300"
    style="object-fit: fill;"
  />
</div>

  <br />

  <h1>Xinjie Zhang</h1>
  <h3>Mechanical Engineering</h3>

  <p>
    <code>SLAM</code>&nbsp;&nbsp;·&nbsp;&nbsp;
    <code>UAV Autonomous Systems</code>&nbsp;&nbsp;·&nbsp;&nbsp;
    <code>Embedded Systems</code>
  </p>

  <p><strong>Building robotic systems from algorithms to real-world deployment.</strong></p>
  <p>
    Algorithm Development&nbsp;&nbsp;·&nbsp;&nbsp;Software Architecture&nbsp;&nbsp;·&nbsp;&nbsp;
    Simulation&nbsp;&nbsp;·&nbsp;&nbsp;Hardware Integration&nbsp;&nbsp;·&nbsp;&nbsp;Field Deployment
  </p>
</div>

<br />

## Core Expertise

<table>
  <tr>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/slam.png" width="420" height="285" alt="SLAM point cloud and trajectory visualization" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🛰️ SLAM</h2>
      <p><strong>LiDAR–IMU–Vision Fusion SLAM Framework</strong></p>
      <p><sub>Independently developed core modules for localization, mapping, and multi-sensor fusion</sub></p>
      <ul>
        <li>LiDAR–Inertial Odometry</li>
        <li>Iterated Error State Kalman Filter (IESKF)</li>
        <li>Incremental Mapping and Map Management</li>
        <li>Stereo Vision Fusion and Multi-Sensor Calibration</li>
      </ul>
      <p><sub>Implemented with ROS2 · C++ · LiDAR / IMU / Vision</sub></p>
    </td>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/uav.png" width="420" height="285" alt="Autonomous UAV navigation visualization" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🚁 UAV</h2>
      <p><strong>PX4–ROS2 Autonomous UAV System</strong></p>
      <p><sub>Independently designed the airframe and propeller guards, assembled the onboard hardware, and integrated the complete system</sub></p>
      <ul>
        <li>Custom Airframe and Propeller Guard Design</li>
        <li>Flight Controller, Onboard Computer, and Sensor Assembly</li>
        <li>PX4–ROS2 Communication and MAVLink Control</li>
        <li>Gazebo Simulation and Real-Flight Validation</li>
      </ul>
      <p><sub>Implemented with Custom Airframe · PX4 · ROS2 · Gazebo</sub></p>
    </td>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/embedded.png" width="100%" alt="Embedded robotics navigation visualization" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🔧 Embedded</h2>
      <p><strong>STM32 Robotic Embedded Control System</strong></p>
      <p><sub>Independently designed the controller hardware, firmware, device communication, and system integration</sub></p>
      <ul>
        <li>MCU and Peripheral Circuit Design</li>
        <li>PCB Design, Soldering, and Hardware Debugging</li>
        <li>Sensor Drivers and Data Acquisition</li>
        <li>CAN / UART / SPI / I2C Communication Interfaces</li>
      </ul>
      <p><sub>Implemented with STM32 · PCB · CAN / UART / SPI / I2C</sub></p>
    </td>
  </tr>
</table>

<br />

## Featured Engineering Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/legededaduzi/mini-livo">
        <img src="./assets/profile/mini-livo-cover-v3.png" width="100%" alt="Mini-LIVO project cover" />
      </a>
      <h3>
        <a href="https://github.com/legededaduzi/mini-livo">🔥 Mini-LIVO ↗</a>
      </h3>
      <p>A lightweight LiDAR-Inertial Odometry framework based on ROS2.</p>
      <p>
        <strong>Real-time SLAM</strong> · IESKF Backend<br />
        ikd-Tree Incremental Mapping · MID360 Support<br />
        D435 Stereo Vision · UAV Deployment
      </p>
      <p><a href="https://github.com/legededaduzi/mini-livo"><strong>Explore the system →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/legededaduzi/PX4-AeroFusion-Sim">
        <img src="./assets/profile/PX4_AeroFusion.png" width="100%" alt="ROS2 Gazebo robotics simulation project cover" />
      </a>
      <h3>
        <a href="https://github.com/legededaduzi/PX4-AeroFusion-Sim">🌎 PX4_AeroFusion Simulation Platform</a>
      </h3>
      <p>A complete robotics simulation environment for autonomy validation.</p>
      <p>
        <strong>PX4 UAV Simulation</strong> · Livox MID360 Model<br />
        RealSense D435 Model · Indoor / Tunnel Environment<br />
        Reproducible SLAM Evaluation
      </p>
      <p><a href="https://github.com/legededaduzi/PX4-AeroFusion-Sim"><strong>Explore the platform →</strong></a></p>
    </td>
  </tr>
</table>

<br />

## Technology Stack

<table>
  <tr>
    <td width="25%" valign="top">
      <h4>ROBOTICS</h4>
      <code>ROS2</code><br /><br />
      <code>SLAM</code> <code>LIO</code><br /><br />
      <code>VIO</code> <code>Gazebo</code><br /><br />
      <code>Frame Calibration</code>
    </td>
    <td width="25%" valign="top">
      <h4>PROGRAMMING</h4>
      <code>C++17</code><br /><br />
      <code>Python</code><br /><br />
      <code>Eigen</code> <code>PCL</code><br /><br />
      <code>Sophus</code>
    </td>
    <td width="25%" valign="top">
      <h4>EMBEDDED</h4>
      <code>STM32</code><br /><br />
      <code>CAN</code> <code>UART</code><br /><br />
      <code>SPI</code> <code>I2C</code><br /><br />
      <code>RS-485</code>
    </td>
    <td width="25%" valign="top">
      <h4>HARDWARE</h4>
      <code>PCB</code><br /><br />
      <code>Sensors</code> <code>UAV</code><br /><br />
      <code>Debugging</code><br /><br />
      <code>Soldering</code>
    </td>
  </tr>
</table>

<br />

## Engineering Philosophy

<p align="center">
  <img src="./assets/profile/engineering-pipeline.svg" width="92%" alt="Algorithm to software to hardware to real robot engineering pipeline" />
</p>

<p align="center">
  <strong>From mathematical models and production software to integrated hardware and real-world robots.</strong>
</p>

<br />

<div align="center">
  <sub>Open to opportunities in SLAM, robotics perception, autonomous UAV systems, and robotics engineering.</sub>
  <br /><br />
  <a href="https://github.com/legededaduzi">GitHub</a>
</div>
