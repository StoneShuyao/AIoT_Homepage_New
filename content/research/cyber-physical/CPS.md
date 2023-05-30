---
title: "CPS Platforms"
weight: 5
type: docs
description: >
---

### **CPS Platforms and Performance Control Frameworks**
We have developed new platforms and performance control frameworks, which address critical system issues of CPS including programmability, data fidelity, measurement, and real-time assurance [RTSS10, TPDS12, IPSN13, IPSN15, IPSN14].

First, we developed a smartphone-based platform called ORBIT, which leverages salient features of modern smartphones including multicore processors and versatile network interfaces and sensors, while addressing key challenges when used for data-intensive cyber-physical applications, such as high power consumption. ORBIT provides a profile-based task partitioner that intelligently dispatches compute tasks between local and the cloud tiers to minimize the power consumption, a multi-thread data partitioner to optimize quality/delay trade-off, and an annotation-based API for simplifying application development. ORBIT has been adopted in several large-scale volcano-monitoring sensor systems and aquatic robotic systems.

Second, we developed a framework for data fidelity and real-time assurance by integrating data fusion, calibration, and real-time scheduling algorithms. Our solution provides a systematic design methodology for data-intensive CPS such as real-time video surveillance and safety-critical autonomous driving, whose operations are subject to highly dynamic compute workloads and significant uncertainties from physical environments.

Third, we developed Nemo – a novel practical in situ power metering system for CPS platforms. Energy-efficiency is one of the most important design objectives of embedded CPS because of limited energy resource while it remains challenging to validate the energy-efficiency claims of existing solutions, largely due to the lack of ability to track the real-time system power consumption at runtime. In addition, real-time power usage is also vital for a system to modify its behavior and adapt to dynamic physical environment. Nemo features new circuit designs that can achieve high real-time measurement accuracy. Moreover, the measurement data is transmitted to the host node solely through the power line, leading to a noninvasive, plug and play design that allows Nemo to be easily installed on existing aftermarket platforms without physical wiring or soldering.

### **Funding**
1. National Science Foundation, "CAREER: Design and Analysis of Performance-Critical Wireless Sensor Networks: A Fusion-Centric Approach", PI, $424,673, 2010-2016.
2. National Science Foundation, "CSR: Collaborative Research: Integrated Control of Fidelity and Real-Time Performance in Networked Sensing Systems", PI, $230,000, 2012-2015.

### **People**
Guoliang Xing (Professor, CUHK)<br>
Yu Wang (Ph.D 2015, currently with Samsung)<br>
Rui Tan (Postdoc, currently Assistant Professor at Nanyang Technological University, Singapore)<br>
Jinzhu Chen (Ph.D 2015, currently with GM Research)<br>
Dennis Phillips (Ph.D candidate, MSU)<br>
Mohammad-Mahdi Moazzami (Ph.D candidate, MSU)

### **Collaborators**
Xiaorui Wang (Associate Professor, ECE, Ohio State University)

### **Awards & Recognitions**
<li>Best Paper Award, “Nemo: A High-fidelity Noninvasive Power Meter System for Wireless Sensor Networks”, Tools and Design Methods (SPOTS) Track, the 12th ACM/IEEE Conference on Information Processing in Sensor Networks (IPSN), 2013.</li>
                                        

### **Publications**
1. Mohammad-Mahdi Moazzami, Dennis Phillips, Rui Tan, Guoliang Xing, ORBIT: a Smartphone-based Platform for Data-intensive Embedded Sensing Applications, Proceedings of the 14th International Conference on Information Processing in Sensor Networks (IPSN), 2015, acceptance ratio: 27/111=24%.
2. Ruogu Zhou, Guoliang Xing, Nemo: A High-fidelity Noninvasive Power Meter System for Wireless Sensor Networks, The 12th ACM/IEEE Conference on Information Processing in Sensor Networks (IPSN), 2013, acceptance ratio: 24/115=21%, SPOTS Best Paper Award.
3. Rui Tan, Guoliang Xing, Xue Liu, Jianguo Yao, Zhaohui Yuan, Adaptive Calibration for Fusion-based Wireless Sensor Networks, The 29th Conference on Computer Communications (INFOCOM), March 15-19, 2010, San Diego, CA, USA, acceptance ratio: 276/1575=17.5%.
4. Rui Tan, Guoliang Xing, Zhaohui Yuan, Xue Liu, Jianguo Yao, System-level Calibration for Fusion-based Wireless Sensor Networks, The 31st IEEE Real-Time Systems Symposium (RTSS), November 30 - December 3, 2010, San Diego, CA, USA.
5. Jinzhu Chen, Rui Tan, Guoliang Xing, Xiaorui Wang, Xing Fu, Fidelity-Aware Utilization Control for Cyber-Physical Surveillance Systems, The 31st IEEE Real-Time Systems Symposium (RTSS), November 30 - December 3, 2010, San Diego, CA, USA.
6. Rui Tan, Guoliang Xing, Benyuan Liu, Jianping Wang, Impact of Data Fusion on Real-Time Detection in Sensor Networks, The 30th IEEE Real-Time Systems Symposium (RTSS), December 1-4, 2009, Washington, D.C.
7. Rui Tan, Guoliang Xing, Zhaohui Yuan, Xue Liu, Jianguo Yao, "System-level Calibration for Data Fusion in Wireless Sensor Networks", ACM Transactions on Sensor Networks (TOSN), 9(3), May 2013.
8. Rui Tan, Guoliang Xing, Jinzhu Chen, Wen-Zhan Song, Renjie Huang, "Fusion-based Volcanic Earthquake Detection and Timing in Wireless Sensor Networks", ACM Transactions on Sensor Networks (TOSN), 9(2), 17:1-25, Mar 2013.
9. Rui Tan, Guoliang Xing, Xue Liu, Jianguo Yao, Zhaohui Yuan, "Adaptive Calibration for Fusion-based Cyber-Physical Systems", ACM Transactions on Embedded Computing Systems (TECS), 11(4), 1539-9087, 2012.
10. Jinzhu Chen, Rui Tan, Guoliang Xing, Xiaorui Wang, Xing Fu, "Fidelity-Aware Utilization Control for Cyber-Physical Surveillance Systems", IEEE Transactions on Parallel and Distributed Systems (TPDS), 23(12):1-14, December 2012.
11. Rui Tan, Guoliang Xing, Benyuan Liu, Jianping Wang, Xiaohua Jia, "Exploiting Data Fusion to Improve the Coverage of Wireless Sensor Networks", IEEE/ACM Transactions on Networking, vol.20, no.2, pp.450-462, April 2012.
12. Rui Tan, Guoliang Xing, Jianping Wang, Benyuan Liu, "Performance Analysis of Real-Time Detection in Fusion-Based Sensor Networks", IEEE Transactions on Parallel and Distributed Systems (TPDS), Volume 22, Issue 9, Pages:1564-1577, 2011.

### **Research Thrusts**
1. ORBIT: A Smartphone-Based Platform for Data-Intensive Embedded Sensing Applications. Owing to the rich processing, multi-modal sensing, and versatile networking capabilities, smartphones are increasingly used to build data-intensive embedded sensing applications. However, various challenges must be systematically addressed before smartphones can be used as a generic embedded sensing platform, including high power consumption, lack of real-time functionality and user-friendly embedded programming support. We develop ORBIT, a smartphone-based platform for data-intensive embedded sensing applications. ORBIT features a tiered architecture, in which a smartphone can interface to an energy-efficient peripheral board and/or a cloud service. ORBIT as a platform addresses the shortcomings of current smartphones while utilizing their strengths. ORBIT provides a profile-based task partitioning allowing it to intelligently dispatch the processing tasks among the tiers to minimize the system power consumption. ORBIT also provides a data processing library that includes two mechanisms namely adaptive delay/quality trade-off and data partitioning via multi-threading to optimize resource usage. Moreover, ORBIT supplies an annotation based programming API for developers that significantly simplifies the application development and provides programming flexibility. Extensive microbenchmark evaluation and two case studies including seismic sensing and multi-camera 3D reconstruction, validate the generic design of ORBIT.
![](/images/research/cps_img1.png)

2. Nemo: A High-fidelity Noninvasive Power Meter System for Wireless Sensor Networks. We design and implement Nemo -- a practical in situ power metering system for wireless sensor networks. Nemo features a new circuit design called shunt resistor switch that can dynamically adjust the resistance of shunt resistors based on the current load. This allows Nemo to achieve a wide dynamic current range and high measurement accuracy. Nemo transmits real-time power measurements to the host node solely through the power line, by modulating the current load and the supply voltage. This feature leads to a noninvasive, plug & play design that allows Nemo to be easily installed on existing mote platforms without physical wiring or soldering. We have implemented a prototype of Nemo and conducted extensive experimental evaluation. Our results show that Nemo can transmit high-throughput measurement data to the host through voltage/current load modulation. Moreover, it has satisfactory measurement fidelity over a wide range of operating conditions. In particular, Nemo yields a dynamic measurement range of 250,000:1, which is 2.5X and 7X that of two state-of-the-art sensor network power meter systems, while only incurring an average measurement error of 1.34%. We also use a case study to demonstrate that Nemo is able to track the highly dynamic sleep current consumption of TelosB motes, which has important implications for the design of low duty-cycle sensor networks that operate in dynamic environments.
![](/images/research/cps_img2.png)

3. Fidelity-Aware Utilization Control for Cyber-Physical Surveillance Systems. Recent years have seen the growing deployments of Cyber-Physical Systems (CPSs) in many mission-critical applications such as security, civil infrastructure, and transportation. These applications often impose stringent requirements on system sensing fidelity and timeliness. However, existing approaches treat these two concerns in isolation and hence are not suitable for CPSs where system fidelity and timeliness are dependent of each other due to the tight integration of computational and physical resources. We propose a holistic approach called Fidelity-Aware Utilization Controller (FAUC) for wireless cyber-physical surveillance (WCS) systems that combine low-end sensors with cameras for large-scale ad hoc surveillance in unplanned environments. By integrating data fusion with feedback control, FAUC can enforce a CPU utilization upper bound to ensure the system's real-time schedulability although CPU workloads vary significantly at runtime due to stochastic detection results. At the same time, FAUC optimizes system fidelity and adjusts the control objective of CPU utilization adaptively in the presence of variations of target/noise characteristics. We have implemented FAUC on a small-scale WCS testbed consisting of TelosB/Iris motes and cameras. Our extensive experiments on light and acoustic target detection show that FAUC can achieve robust fidelity and real-time guarantees in dynamic environments.
![](/images/research/cps_img3.png)