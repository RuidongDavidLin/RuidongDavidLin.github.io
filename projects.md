---
layout: page
permalink: /projects/index.html
title: Projects
---

### **Research Projects**

- Research Cooperated with Prof. Kangping Li@SJTU 《Meteorological-implicit Graph Learning-based Distributed PV Data Cleaning Framework》 (Submitted)
    - High-quality distributed photovoltaic (PV) power data serves as critical infrastructure in modern power systems, enabling grid stability assessment, energy forecasting, and distributed energy market trading. Compared with centralized PV plants, distributed installations exhibit inherent monitoring complexities arising from their spatial dispersion and scale effects, which systematically induce data degradation. This necessitates the development of robust data cleaning methodologies to ensure data quality. Current methodologies, limited by the absence of site-specific meteorological references, predominantly adopt isolated strategies focusing either on temporal consistency checks or spatial correlation analysis. These methods are fundamentally constrained by their inability to capture the inherent spatiotemporal coupling characteristics that define distributed PV systems. To bridge the gap encountered by existing methods, this paper proposes a Meteorological-implicit Graph Learning-based (MiGL) framework which synergistically encodes both spatial correlation and temporal dynamics through a graph adjacency matrix. Another key innovation resides in designing an adjacency learner that disentangles heterogeneous spatiotemporal dependencies via data-driven learning, effectively bypassing the need for explicit prior knowledge. Integrating with the post-cleaning validation mechanism, our proposed MiGL-based framework achieves state-of-the-art performance in distributed PV data cleaning, as empirically validated using a real-world distributed PV power dataset consisting of 69 PV sites’ high-quality data.

<figure class="floatpic">
<img src="/images/PaperFig/GCN.png" class="floatpic" width="2783" height="950" alt="GCN">
</figure>

##### 全国大学生智能汽车竞赛讯飞组
- 项目内容：在搭载激光雷达等传感器的无人驾驶车上实现机器人定位、自动驾驶、自动避障、目标检测、智能语音交互等功能，并完成赛项规定任务
- 负责工作：完成整体任务思路构建，协调团队内部工作。实现机器人SLAM环境构建算法、自动驾驶与导航算法、机器人自主定位算法、目标检测算法与车辆运动控制算法的构建与优化
- 项目成果：国家级竞赛一等奖两项（其中一项全国第四名）同时于Github（全球最大的开源社区）平台开源本队伍参赛代码框架(https://github.com/RuidongDavidLin/CUMTB-2022-Opensource)目前收获21个star，8个fork，在同平台同类代码中处于领先水平

##### 中国机器人及人工智能大赛智能分拣挑战赛
- 项目内容：在实现无人驾驶车的各项基本功能的基础上，完成无人车与智能机械臂之间的多机通讯，共同协同实现物品的智能识别与搬运
- 负责工作：完成机器人自动与导航驾驶算法、机器人自主定位算法、目标检测算法与车辆运动控制算法的构建与优化。同时设计实现机器人与机械臂的局域网通信与协调调度配合
- 项目成果：国家级竞赛一等奖两项（两项一等奖均为全国第一名，该比赛被央视新闻于2021年12月报道）

##### 全国大学生智能汽车竞赛智能视觉组
- 项目内容：在智能车上完成卡片分类、最优路径规划以及高精度定位等工作
- 负责工作：完成基于EKF（拓展卡尔曼滤波）的多传感器融合定位算法
- 项目成果：国家级竞赛二等奖一项

##### 《一种低成本的垃圾分类指导与监督系统》
- 项目内容：在低成本边缘计算设备Jetson Nano(2GB)上构建YoloV5目标检测算法，同时结合摄像头与语音播报系统，对行人投放的街头垃圾进行垃圾的分类与指导
- 负责工作：完成目标检测算法在边缘计算设备上的部署工作，采集与标定垃圾分类数据集，完成目标检测神经网络的训练与优化
- 项目成果：国家级三等奖一项