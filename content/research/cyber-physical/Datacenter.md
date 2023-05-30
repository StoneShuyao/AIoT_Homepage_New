---
title: "Datacenter"
weight: 3
type: docs
description: >
---

### **Datacenter and Residential Energy Management**
Data centers have become a critical infrastructure in the era of cloud computing. More than 23% of data center outages are caused by servers’ overheating-induced shutdowns. The common practice to prevent overheating is to overcool the server rooms, resulting in excessive Computer Room Air Conditioning (CRAC) power consumption (up to 50% of the total consumption) in many data centers. We have developed a novel cyber-physical approach, which integrates Computational Fluid Dynamics (CFD) modeling, in situ wireless sensing, and data-driven prediction and control, to significantly reduce the cooling energy [ICDCS11, IGCC12, RTSS12, RTSS14, TPDS12, TOSN15]. First, we developed offline CFD modeling and real-time data-driven prediction algorithms to predict the ambient temperatures in a data center, and proposed an adaptive training mechanism to address the data and variable dimension exploration problem. We integrated the temperature prediction algorithm with a predictive CRAC control algorithm to form a closed-loop thermal management solution for large-scale data centers.

In 2015, about 40% of total U.S. energy consumption was attributed to residential and commercial buildings. Research has shown that giving users fine-grained information about their energy usage fosters conservation. We developed the first practical ad hoc sensor system that can accurately monitor appliance power usage without supervised training. Based on a smart meter and inexpensive light and acoustic sensors, the system utilizes multi-sensor fusion and advanced unsupervised learning algorithms to analyze the signal signatures of different appliances and autonomously associates the classified events with the appliances.

### **Funding**
1. National Science Foundation, "CSR: Collaborative Research: Integrated Control of Fidelity and Real-Time Performance in Networked Sensing Systems", PI, $230,000, 2012-2015.
2. National Science Foundation, "CAREER: Design and Analysis of Performance-Critical Wireless Sensor Networks: A Fusion-Centric Approach", PI, $424,673, 2010-2016.

### **People**
Guoliang Xing (Professor, CUHK)<br>
Yu Wang (Ph.D 2015, currently with Samsung)<br>
Rui Tan (Postdoc, currently Assistant Professor at Nanyang Technological University, Singapore)<br>
Jinzhu Chen (Ph.D 2015, currently with GM Research)

### **Collaborators**
Xiaorui Wang (Associate Professor, ECE, Ohio State University)<br>
Chengxian Lin (Associate Professor, Mechanical and Materials Engineering, Florida International University)

### **Awards & Recognitions**
<li>Mark Weiser Best Paper Award Runner-up, “Supero: A Sensor System for Unsupervised Residential Power Usage Monitoring”, the 11th IEEE International Conference on Pervasive Computing and Communications (PerCom), 2013</li>
                                        

### **Publications**
1. Jinzhu Chen, Rui Tan, Guoliang Xing, Xiaorui Wang, PTEC: A System for Predictive Thermal and Energy Control in Data Centers, IEEE Real-Time Systems Symposium (RTSS), 2014, acceptance ratio: ~25%.
2. Dennis E. Phillips, Rui Tan, Mohammad-Mahdi Moazzami, Guoliang Xing, Jinzhu Chen, David K. Y. Yau, Supero: A Sensor System for Unsupervised Residential Power Usage Monitoring, The 11th IEEE International Conference on Pervasive Computing and Communications (PerCom), 2013, acceptance ratio: 18 full papers out of 170 submissions = 10.6%, Mark Weiser Best Paper Award Runner-Up.
3. Jinzhu Chen, Rui Tan, Yu Wang, Guoliang Xing, Xiaorui Wang, Xiaodong Wang, Bill Punch, Dirk Colbry, A High-Fidelity Temperature Distribution Forecasting System for Data Centers, The 33st IEEE Real-Time Systems Symposium (RTSS), 2012, acceptance ratio: 35/157=22%.
4. Xiaodong Wang, Xiaorui Wang, Guoliang Xing, and Cheng-Xian Lin, Leveraging Thermal Dynamics in Sensor Placement for Overheating Server Component Detection, The third IEEE International Green Computing Conference (IGCC), San Jose, California, June 2012, acceptance rate: 18/60 = 30%.
5. Jinzhu Chen, Rui Tan, Yu Wang, Guoliang Xing, Xiaorui Wang, Xiaodong Wang, Bill Punch, and Dirk Colbry. A Sensor System for High-Fidelity Temperature Distribution Forecasting in Data Centers, ACM Transactions on Sensor Networks (TOSN), Vol. 11(2), February 2015
6. Xiaodong Wang, Xiaorui Wang, Liu Liu, and Guoliang Xing, DutyCon: A dynamic duty-cycle control approach to end-to-end delay guarantees in wireless sensor networks, ACM Transactions on Sensor Networks 9 (4), July 2013
7. Xiaodong Wang, Xiaorui Wang, Guoliang Xing, Cheng-Xian Lin, Maximizing the detection probability of overheating server components with sensor placement based on thermal dynamics, Sustainable Computing: Informatics and Systems, Volume 3, Issue 3, September 2013, Pages 148-160.

### **Research Thrusts**
1. PTEC: A System for Predictive Thermal and Energy Control in Data Centers. Current data centers often adopt conservative and static settings for cooling and air circulation systems, leading to excessive energy consumption. We design and implement PTEC -- a system for predictive thermal and energy control in data centers. PTEC leverages the server built-in sensors and monitoring utilities, as well as a wireless sensor network, to monitor both the cyber and physical status of a data center. By predicting the temperature evolution of a data center in real time, PTEC finds the temperature setpoints, the cold air supply rates, and the speeds of server internal fans to minimize the expected total energy consumption of cooling and circulation systems. Moreover, PTEC enforces the upper bounds on server inlet temperatures and their temporal variations to prevent server overheating and reduce server hardware failure rate. We evaluated PTEC on a hardware testbed consisting of 15 servers and a total of 23 temperature and power sensors, as well as through Computational Fluid Dynamics (CFD) simulations based on real data traces collected from a data center with 229 servers. The experimental results show that PTEC can reduce the cooling and circulation energy consumption by more than 30%, compared with baseline thermal control strategies.
![](/images/research/dc_img1.png)

2. A High-Fidelity Temperature Distribution Forecasting System for Data Centers. Data centers have become a critical computing infrastructure in the era of cloud computing. Temperature monitoring and forecasting are essential for preventing server shutdowns because of overheating and improving a data center's energy efficiency. We propose a novel cyber-physical approach for temperature forecasting in data centers, which integrates Computational Fluid Dynamics (CFD) modeling, in situ wireless sensing, and real-time data-driven prediction. To ensure the forecasting fidelity, we leverage the realistic physical thermodynamic models of CFD to generate transient temperature distribution and calibrate it using sensor feedback. Both simulated temperature distribution and sensor measurements are then used to train a real-time prediction algorithm. As a result, our approach reduces not only the computational complexity of online temperature modeling and prediction, but also the number of deployed sensors, which enables a portable, noninvasive thermal monitoring solution that does not rely on the infrastructure of monitored data center. We extensively evaluated the proposed system on a rack of 15 servers and a testbed of five racks and 229 servers in a production data center. Our results show that our system can predict the temperature evolution of servers with highly dynamic workloads at an average error of 0.52 C, within a duration up to 10 minutes. Moreover, our approach can reduce the required number of sensors by 67% while maintaining desirable prediction fidelity.
![](/images/research/dc_img2.png)

3. Supero: A Sensor System for Unsupervised Residential Power Usage Monitoring. As a key technology of home area networks in smart grids, fine-grained power usage monitoring may help conserve electricity. Research has shown that providing users fine-grained information concerning their power usage in the home fosters conservation. Several existing systems achieve this goal by exploiting appliances' power usage signatures identified in labor-intensive in situ training processes. Recent work shows that autonomous power usage monitoring can be achieved by supplementing a smart meter with distributed sensors that detect the working states of appliances. However, sensors must be carefully installed for each appliance, resulting in high installation cost. We develop Supero -- the first ad hoc sensor system that can monitor appliance power usage without supervised training. By exploiting multi-sensor fusion and unsupervised machine learning algorithms, Supero can classify the appliance events of interest and autonomously associate measured power usage with the respective appliances. We evaluated Supero in two real deployments, a small apartment and a large multi-bedroom home, with 10 sensors. The results show that Supero estimates the energy consumption with errors less than 7.5% in the two deployments.
![](/images/research/dc_img3.png)
![](/images/research/dc_img4.png)