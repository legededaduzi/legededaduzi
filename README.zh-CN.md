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
      <p>
        <a href="https://github.com/legededaduzi/mini-livo">
          <strong>mini-LIVO ↗</strong>
        </a>
      </p>
      <p><sub>轻量级激光雷达—惯性—视觉 SLAM 框架</sub></p>
      <ul>
        <li>激光雷达—惯性里程计</li>
        <li>迭代误差状态卡尔曼滤波</li>
        <li> 增量式建图</li>
        <li>双目视觉融合</li>
        <li>多传感器标定</li>
      </ul>
      <p>
        <code>ROS2 Humble</code> <code>C++17</code> <code>Eigen</code><br />
        <code>Sophus</code> <code>PCL</code> <code>Gazebo</code>
      </p>
    </td>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/uav.png" width="420" height="285" alt="自主无人机系统" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🚁 无人机</h2>
      <p><strong>自主无人机系统</strong></p>
      <p><sub>从仿真测试到真实飞行的自主系统</sub></p>
      <ul>
        <li>PX4 系统集成</li>
        <li>无人机硬件平台</li>
        <li>ROS2 通信</li>
        <li>仿真测试</li>
        <li>真实飞行部署</li>
      </ul>
      <p>
        <code>PX4</code> <code>Gazebo</code> <code>ROS2</code><br />
        <code>MAVLink</code> <code>Sensor Fusion</code>
      </p>
    </td>
    <td width="33.33%" valign="top">
      <p align="center">
        <img src="./assets/profile/embedded.png" width="100%" alt="嵌入式机器人控制器" style="display:block; width:100%; height:285px; object-fit:contain; object-position:center; background:#2d2d2d;" />
      </p>
      <h2>🔧 嵌入式</h2>
      <p><strong>机器人嵌入式硬件</strong></p>
      <p><sub>面向机器人平台的可靠电子系统</sub></p>
      <ul>
        <li>STM32 固件开发</li>
        <li>PCB 设计</li>
        <li>传感器驱动</li>
        <li>通信接口</li>
        <li>硬件调试</li>
      </ul>
      <p>
        <code>STM32</code> <code>CAN</code> <code>UART</code><br />
        <code>SPI</code> <code>I2C</code> <code>PCB</code>
      </p>
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
      <a href="https://github.com/legededaduzi/mini-lio-sim">
        <img src="./assets/profile/project-simulation.svg" width="100%" alt="ROS2 Gazebo 机器人仿真项目封面" />
      </a>
      <h3>🌎 ROS2–Gazebo 机器人仿真</h3>
      <p>面向自主系统验证的完整机器人仿真环境。</p>
      <p>
        <strong>PX4 无人机仿真</strong> · Livox MID360 模型<br />
        RealSense D435 模型 · 室内 / 隧道环境<br />
        可复现的 SLAM 评估
      </p>
      <p><a href="https://github.com/legededaduzi/mini-lio-sim"><strong>查看仿真平台 →</strong></a></p>
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
      <code>VIO</code> <code>Gazebo</code>
    </td>
    <td width="25%" valign="top">
      <h4>编程</h4>
      <code>C++17</code><br /><br />
      <code>Python</code><br /><br />
      <code>Eigen</code> <code>PCL</code>
    </td>
    <td width="25%" valign="top">
      <h4>嵌入式</h4>
      <code>STM32</code><br /><br />
      <code>CAN</code> <code>UART</code><br /><br />
      <code>SPI</code> <code>I2C</code>
    </td>
    <td width="25%" valign="top">
      <h4>硬件</h4>
      <code>PCB</code><br /><br />
      <code>传感器</code> <code>无人机</code><br /><br />
      <code>硬件调试</code>
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
