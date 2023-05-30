---
title: "Aquatic Monitoring"
weight: 2
type: docs
description: >
---

### **Aquatic Environment Monitoring Using Robotic Sensors**
Water resources around the world are faced with increasing challenges presented by natural and anthropogenic disasters such as crude oil spills, Harmful Algal Blooms (HABs), and waste discharges. In collaboration with experts in environmental engineering and ecology, we are creating a new paradigm for water system monitoring and sustainable utilization.

First, we developed an aquatic robot system that integrates an off-the-shelf smartphone and a gliding robotic fish. Using the smartphone camera and aquatic sensors, the system can detect spatially dispersed aquatic processes such as debris and HABs using lightweight computer vision algorithms. It intelligently uploads compute-intensive tasks to the cloud and leverages the power-efficient inertial sensors to assist image processing. Second, we proposed a new data-enabled framework for adaptive sampling and aquatic field reconstruction. In our approach, robotic sensors collaboratively profile the characteristics of a diffusion process such as oil spill, including its source location, discharged substance amount, and evolution over time, subject to limited sensor mobility and energy budget. Third, we developed a novel approach to reconstructing a spatiotemporal aquatic field such as HABs, which leverages feedback control and information theory to schedule robotic sensors’ movement and select their rendezvous points.

### **Funding**
1. National Science Foundation, Cyber Physical Systems (CPS), "CPS: Synergy: A Design Framework for Coupled Robotic and Biological Systems with Application to Fish Movement Ecology", $1,000,000, 2014-2018.
2. National Science Foundation, Cyber-Innovation for Sustainability Science and Engineering (CyberSEES), "CyberSEES: Type 2: Towards Sustainable Aquatic Ecosystems: A New Adaptive Sampling and Data-Enabled Monitoring and Modeling Framework", $800,000, 2013-2016.
3. National Science Foundation, "IHCS: Exploiting Mobility-Assisted Collaboration for Adaptive Aquatic Sensor Networks", National Science Foundation, $360,000, 2010-2013.

### **People**
Guoliang Xing (Professor, CUHK)<br>
Yu Wang (Ph.D 2015, currently with Samsung)<br>
Rui Tan (Postdoc, currently Assistant Professor at Nanyang Technological University, Singapore)<br>
Jinzhu Chen (Ph.D 2015, currently with GM Research)

### **Collaborators**
Xiaobo Tan (Professor, ECE, MSU)<br>
Elena Litchman (Professor, Ecology, MSU)<br>
Hayder Radha (Professor, ECE, MSU)<br>
Mantha Phanikumar (Professor, Civil and Environmental Engineering, MSU)<br>

### **Awards & Recognitions**
<li>Best Paper Finalist, “Aquatic Debris Monitoring Using Smartphone-Based Robotic Sensors”, the 13th ACM/IEEE Conference on Information Processing in Sensor Networks (IPSN), 2014.</li>
                                        

### **Publications**
1. Yu Wang, Rui Tan, Guoliang Xing, Jianxun Wang, Xiaobo Tan, Xiaoming Liu, and Xiangmao Chang, Aquatic Debris Monitoring Using Smartphone-Based Robotic Sensors, The 13th ACM/IEEE Conference on Information Processing in Sensor Networks (IPSN), 2014, acceptance ratio: 23/111=20.7% Runner-up for the Best Paper Award.

2. Yu Wang, Rui Tan, Guoliang Xing, Jianxun Wang, Xiaobo Tan, Xiaoming Liu, Samba: a smartphone-based robot system for energy-efficient aquatic environment monitoring, Proceedings of the 14th International Conference on Information Processing in Sensor Networks (IPSN), 2015, acceptance ratio: 27/111=24%.

3. Yu Wang, Rui Tan, Guoliang Xing, Jianxun Wang, Xiaobo Tan, Accuracy-Aware Aquatic Diffusion Process Profiling Using Robotic Sensor Networks, The 11th ACM/IEEE Conference on Information Processing in Sensor Networks (IPSN), April 16-20, 2012 Beijing, China, acceptance ratio: 22/147 = 14.9%.

4. Osama Ennasr, Guoliang Xing, Xiaobo Tan, Distributed time-difference-of-arrival (TDOA)-based localization of a moving target, IEEE 55th Conference on Decision and Control (CDC), 2016.

5. Yu Wang, Rui Tan, Guoliang Xing, Xiaobo Tan, Jianxun Wang, Ruogu Zhou, Spatiotemporal Aquatic Field Reconstruction Using Robotic Sensor Swarm, The 33st IEEE Real-Time Systems Symposium (RTSS), 2012, acceptance ratio: 35/157=22%.

6. Yu Wang, Rui Tan, Guoliang Xing, Jianxun Wang, Xiaobo Tan, Xiaoming Liu, Energy-Efficient Aquatic Environment Monitoring Using Smartphone-Based Robots, ACM Transactions on Sensor Networks (TOSN), vol. 12, No. 3, pp. 25:1-25:28, 2016.

7. Yu Wang; Rui Tan; Guoliang Xing; Jianxun Wang; Xiaobo Tan; X. Liu; Xiangmao Chang, Monitoring Aquatic Debris Using Smartphone-Based Robots, IEEE Transactions on Mobile Computing, vol. 15, No. 6, pp. 1412-1426, 2016.

8. Yu Wang, Rui Tan, Guoliang Xing, Xiaobo Tan, Jianxun Wang, and Ruogu Zhou. Spatiotemporal Aquatic Field Reconstruction Using Cyber-Physical Robotic Sensor Systems. ACM Transactions on Sensor Networks 10(4), June 2014, 27 pages.

9. Yu Wang, Rui Tan, Guoliang Xing, Jianping Wang and Xiaobo Tan, "Profiling Aquatic Diffusion Process Using Robotic Sensor Networks," in IEEE Transactions on Mobile Computing, vol. 13, no. 4, pp. 880-893, April 2014.

### **Research Thrusts**
1. Aquatic Debris Monitoring Using Smartphone-Based Robotic Sensors. Monitoring marine debris is of great interest to aquatic ecosystems, marine life, human health, and sea transport. We design and implement SOAR -- a surveillance robot system that integrates an off-the-shelf Android smartphone and a gliding robotic fish for marine debris monitoring. SOAR features real-time debris detection and capture-based rotation scheduling algorithms. In particular, our image-based debris detection algorithm is specifically designed to address the unique challenges in detecting marine debris, and the rotation scheduling algorithm can efficiently capture the sporadic debris arrivals despite the limited angular view of camera. Moreover, SOAR dynamically offloads the computation-intensive image processing tasks to the cloud via the smartphone for energy conservation. We have implemented a prototype of SOAR and conducted extensive experimental evaluation. The results show that SOAR can accurately detect debris objects in the presence of significant environment and system dynamics, and the rotation scheduling algorithm enables SOAR to effectively monitor debris arrivals with with reduced energy consumption.
![](/images/research/SOAR.png)

2. A Smartphone-Based Robot System for Energy-Efficient Aquatic Environment Monitoring. Monitoring aquatic environment is of great interest to the ecosystem, marine life, and human health. We design and implement Samba -- an aquatic surveillance robot that integrates an off-the-shelf Android smartphone and a robotic fish to monitor harmful aquatic processes such as oil spill and harmful algal blooms. Using the built-in camera of on-board smartphone, Samba can detect spatially dispersed aquatic processes in dynamic and complex environments. To reduce the excessive false alarms caused by the non-water area trees on the shore, Samba segments the captured images and performs target detection in the identified water area only. However, a major challenge in the design of Samba is the high energy consumption resulted from the continuous image segmentation. We propose a novel approach that leverages the power-efficient inertial sensors on smartphone to assist the image processing. In particular, based on the learned mapping models between inertial and visual features, Samba uses real-time inertial sensor readings to estimate the visual features that guide the image segmentation, significantly reducing energy consumption and computation overhead. Samba also features a set of lightweight and robust computer vision algorithms, which detect harmful aquatic processes based on their distinctive color features. Lastly, Samba employs a feedback-based rotation control algorithm to adapt to spatiotemporal evolution of the target aquatic process. We have implemented a Samba prototype and evaluated it through extensive field experiments, lab experiments, and trace-driven simulations. The results show that Samba can achieve 94% detection rate, 5% false alarm rate, and a lifetime up to nearly two months.
![](/images/research/SOAR-img1.png)

3. Accuracy-Aware Aquatic Diffusion Process Profiling Using Robotic Sensor Networks. Water resources and aquatic ecosystems are facing increasing threats from climate change, improper waste disposal, and oil spill incidents. It is of great interest to deploy mobile sensors to detect and monitor certain diffusion processes (e.g., chemical pollutants) that are harmful to aquatic environments. We propose an accuracy-aware diffusion process profiling approach using smart aquatic mobile sensors such as robotic fish. In our approach, the robotic sensors collaboratively profile the characteristics of a diffusion process including source location, discharged substance amount, and its evolution over time. In particular, the robotic sensors reposition themselves to progressively improve the profiling accuracy. We formulate a novel movement scheduling problem that aims to maximize the profiling accuracy subject to limited sensor mobility and energy budget. We develop an efficient greedy algorithm and a more complex near-optimal radial algorithm to solve the problem. We conduct extensive simulations based on real data traces of robotic fish movement and wireless communication. The results show that our approach can accurately profile dynamic diffusion processes under tight energy budgets. Moreover, a preliminary evaluation based on the implementation on TelosB motes validates the feasibility of deploying our movement scheduling algorithms on mote-class robotic sensor platforms.

4. Spatiotemporal Aquatic Field Reconstruction Using Cyber-Physical Robotic Sensor Systems. Monitoring important aquatic processes like harmful algal blooms is of increasing interest to public health, ecosystem sustainability, marine biology, and aquaculture industry. We develop a novel approach to spatiotemporal aquatic field reconstruction using inexpensive, low-power, mobile sensing platforms called robotic fish. Robotic fish networks are a typical example of Cyber-Physical Systems where the design of cyber components (sensing, communication, and information processing) must account for inherent physical dynamics of the robots and the aquatic environment. Our approach features a rendezvous-based mobility control scheme where robotic fish collaborate in the form of a swarm to sense the aquatic environment in a series of carefully chosen rendezvous regions. We design a novel feedback control algorithm that maintains the desirable level of wireless connectivity for a sensor swarm in the presence of significant environment and system dynamics. Information-theoretic analysis is used to guide the selection of rendezvous regions so that the spatiotemporal field reconstruction accuracy is maximized subject to the limited sensor mobility. The effectiveness of our approach is validated via implementation on sensor hardware and extensive simulations based on real data traces of water surface temperature field and on-water ZigBee wireless communication.