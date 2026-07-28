<!-- GitHub 个人主页 README — XinJie Zhang -->

<p align="right">
  <a href="./README.md">English</a>
  &nbsp;·&nbsp;
  <strong>简体中文</strong>
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

  <h1>张心杰</h1>
  <h3>机械工程专业</h3>

  <p>
    <code>SLAM</code>&nbsp;&nbsp;·&nbsp;&nbsp;
    <code>无人机自主系统</code>&nbsp;&nbsp;·&nbsp;&nbsp;
    <code>嵌入式系统</code>
  </p>

  <p><strong>构建从算法研究到真实环境部署的完整机器人系统。</strong></p>
  <p>
    算法开发&nbsp;&nbsp;·&nbsp;&nbsp;软件架构&nbsp;&nbsp;·&nbsp;&nbsp;
    仿真模拟&nbsp;&nbsp;·&nbsp;&nbsp;硬件集成&nbsp;&nbsp;·&nbsp;&nbsp;实机部署
  </p>
</div>

<br />

## 核心能力

<table>
  <tr>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/slam.png" width="420" height="285" alt="SLAM 点云地图与轨迹可视化" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🛰️ SLAM</h2>
      <p><strong>雷达-IMU-视觉融合SLAM系统框架</strong></p>
      <p><sub>围绕定位、建图与多传感器融合，自主完成核心模块研发</sub></p>
      <ul>
        <li>雷达—惯性里程计</li>
        <li>迭代误差状态卡尔曼滤波（IESKF）</li>
        <li>增量式建图与地图管理</li>
        <li>双目视觉融合与多传感器标定</li>
      </ul>
      <p><sub>工程实现：ROS2 · C++ · LiDAR / IMU / Vision</sub></p>
    </td>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/uav.png" width="420" height="285" alt="自主无人机系统" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🚁 无人机</h2>
      <p><strong>PX4-ROS2无人机自主系统</strong></p>
      <p><sub>自主完成机架与保护圈设计、机载硬件搭建及整机系统联调</sub></p>
      <ul>
        <li>无人机机架与螺旋桨保护圈设计</li>
        <li>飞控、机载计算平台与传感器硬件搭建</li>
        <li>PX4–ROS2 通信与 MAVLink 控制</li>
        <li>Gazebo 仿真与实机飞行验证</li>
      </ul>
      <p><sub>工程实现：自研机架 · PX4 · ROS2 · Gazebo</sub></p>
    </td>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/embedded.png" width="100%" alt="嵌入式机器人控制器" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🔧 嵌入式</h2>
      <p><strong>STM32机器人嵌入式控制系统</strong></p>
      <p><sub>围绕硬件、固件与设备通信，自主完成控制器设计和系统联调</sub></p>
      <ul>
        <li>主控与外围电路设计</li>
        <li>PCB 设计、焊接与硬件调试</li>
        <li>传感器驱动与数据采集</li>
        <li>CAN / UART / SPI / I2C 通信接口</li>
      </ul>
      <p><sub>工程实现：STM32 · PCB · CAN / UART / SPI / I2C</sub></p>
    </td>
  </tr>
</table>

<br />

## 精选工程项目

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/legededaduzi/mini-livo">
        <img src="./assets/profile/mini-livo-cover-v3.png" width="100%" alt="Mini-LIO 项目封面" />
      </a>
      <h3>
        <a href="https://github.com/legededaduzi/mini-livo">🔥 Mini-LIO ↗</a>
      </h3>
      <p>基于 ROS2 的轻量级激光雷达—惯性里程计框架。</p>
      <p>
        <strong>实时 SLAM</strong> · IESKF 后端<br />
        ikd-Tree 增量建图 · MID360 支持<br />
        D435 双目视觉 · 无人机部署
      </p>
      <p><a href="https://github.com/legededaduzi/mini-livo"><strong>查看系统 →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/legededaduzi/PX4-AeroFusion-Sim">
        <img src="./assets/profile/PX4_AeroFusion.png" width="100%" alt="ROS2 Gazebo 机器人仿真项目封面" />
      </a>
      <h3>
        <a href="https://github.com/legededaduzi/PX4-AeroFusion-Sim">🌎 PX4_AeroFusion仿真平台</a>
      </h3>
      <p>面向自主系统验证的完整机器人仿真环境。</p>
      <p>
        <strong>PX4 无人机仿真</strong> · Livox MID360 模型<br />
        RealSense D435 模型 · 室内 / 隧道环境<br />
        可复现的 SLAM 评估
      </p>
      <p><a href="https://github.com/legededaduzi/PX4-AeroFusion-Sim"><strong>查看仿真平台 →</strong></a></p>
    </td>
  </tr>
</table>

<br />

## 技术栈

<table>
  <tr>
    <td width="25%" valign="top">
      <h4>机器人</h4>
      <code>ROS2</code><br /><br />
      <code>SLAM</code> <code>LIO</code><br /><br />
      <code>VIO</code> <code>Gazebo</code><br /><br />
      <code>坐标系标定</code>
    </td>
    <td width="25%" valign="top">
      <h4>编程</h4>
      <code>C++17</code><br /><br />
      <code>Python</code><br /><br />
      <code>Eigen</code> <code>PCL</code><br /><br />
      <code>Sophus</code>
    </td>
    <td width="25%" valign="top">
      <h4>嵌入式</h4>
      <code>STM32</code><br /><br />
      <code>CAN</code> <code>UART</code><br /><br />
      <code>SPI</code> <code>I2C</code><br /><br />
      <code>RS-485</code>
    </td>
    <td width="25%" valign="top">
      <h4>硬件</h4>
      <code>PCB</code><br /><br />
      <code>传感器</code> <code>无人机</code><br /><br />
      <code>硬件调试</code><br /><br />
      <code>焊接</code>
    </td>
  </tr>
</table>

<br />

## 工程理念

<p align="center">
  <img src="./assets/profile/engineering-pipeline.svg" width="92%" alt="从算法、软件、硬件到真实机器人的工程流程" />
</p>

<p align="center">
  <strong>从数学模型和工程软件，到硬件集成与真实机器人部署。</strong>
</p>

<br />

<div align="center">
  <sub>期待 SLAM、机器人感知、无人机自主系统与机器人工程方向的合作机会。</sub>
  <br /><br />
  <a href="https://github.com/legededaduzi">GitHub</a>
</div>
