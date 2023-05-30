---
title: "Smart Vehicular Systems"
weight: 4
type: docs
description: >
---

### **Smart Vehicular Systems: Wireless Networking and Driver Sensing**
Recent years have witnessed the emergence of networked vehicular systems. A recent report released by IEEE predicts that by 2025, 60% of the vehicles on the road will be Internet-ready and also connected with each other. Today's wireless technologies struggle to meet vehicular communication requirements, because of noise, interference, and fast-varying vehicular channel conditions. In [Mobisys13, Infocom14, Infocom15], we proposed a novel top-down cross-layer wireless design approach. While the traditional wisdom of cross-layer design is to exploit PHY/link layer information at upper-layers, our approach represents a paradigm shift in that it leverages signatures of upper-layer protocols and applications to improve PHY and link layer performance. Our approach can be easily integrated with the receiver of 802.11p used for vehicle-to-vehicle (V2V) network and LTE used for vehicle-to-infrastructure (V2I) communication. This project is supported by an NSF grant with total funding of USD $500K.

Internet of Things (IoT) holds the promise of significantly improving driving safety. For example, detecting and warning the unsafe driving behavior can improve the driver's self-alertness. We have developed SafeWatch [IoTDI17] -- a system based on smartwatches and smartphones, which detects the driver's unsafe driving behaviors in a real-time manner. SafeWatch addresses several key challenges such as impact from the vehicle's movement and the significant variation across different driving environments.



### **Funding**
National Science Foundation, "NeTS: Small: SOAR: Leveraging Traffic Signatures to Improve Performance of Vehicular Networks", PI, $499,999, 2014-2017.


### **People**
Guoliang Xing (Professor, CUHK)<br>
Jun Huang (Ph.D 2011, currently Assistant Professor at Peking University, China)<br>
Yu Wang (Ph.D 2015, currently with Samsung)<br>
Rui Tan (Postdoc, currently Assistant Professor at Nanyang Technological University, Singapore)<br>
Jinzhu Chen (Ph.D 2015, currently with GM Research)

### **Collaborators**
Xiaobo Tan (Professor, ECE, MSU)<br>
Elena Litchman (Professor, Ecology, MSU)<br>
Hayder Radha (Professor, ECE, MSU)<br>
Mantha Phanikumar (Professor, Civil and Environmental Engineering, MSU)<br>


### **Publications**
1. Jun Huang, Yu Wang, Guoliang Xing, LEAD: Leveraging Protocol Signatures for Improving Wireless Link Performance, The 10th International Conference on Mobile Systems, Applications, and Services (MobiSys), 2013, acceptance ratio: 33/210 = 15.7%.
2. Alireza Ameli Renani, Jun Huang, Abdol Esfahanian, Harnessing Hardware Defects for Improving Wireless Link Performance: Measurements and Applications, IEEE INFOCOM 2017, acceptance ratio: 292/1395=20.93%.
3. Chongguang Bi, Jun Huang, Guoliang Xing, Landu Jiang, Xue Liu, Minghua Chen, SafeWatch: A Wearable Hand Motion Tracking System for Improving Driving Safety, the 2nd IEEE International Conference on Internet-of-Things Design and Implementation (IoTDI), 2017, acceptance ratio: 15/51=29%.
4. Jun Huang, Guoliang Xing, CodeRepair: PHY-layer Partial Packet Recovery Without the Pain, IEEE INFOCOM 2015, acceptance ratio: 316/1640=19.3%.
5. Jun Huang, Guoliang Xing, Gang Zhou, TRACK: Unleash Exposed Terminals in Enterprise WLANs, The 33rd Annual IEEE International Conference on Computer Communications (INFOCOM), 2014, acceptance ratio: 320/1645=19.4%.

### **Research Thrusts**
1. SafeWatch: A Wearable Hand Motion Tracking System for Improving Driving Safety. Driving while distracted or losing alertness significantly increases the risk of the traffic accident. The emerging Internet of Things (IoT) systems for smart driving hold the promise of significantly reducing road accidents. In particular, Detecting the unsafe hand motions and warning the driver using smart sensors can improve the driver's self-alertness and the driving skill. However, due to the impact from the vehicle's movement and the significant variation across different driving environments, detecting the position of the driver's hand is challenging. We develop SafeWatch -- a system based on smartwatches and smartphones, which detects the driver's unsafe behaviors in a real-time manner. SafeWatch infers driver's hand motions based on several important features such as the posture of the driver's forearm and the vibration on the smartwatch. SafeWatch employs a novel adaptive training algorithm which keeps updating the training data set at runtime based on inferred hand positions in certain driving conditions. The evaluation with 75 real driving trips from 6 subjects shows that SafeWatch has a high accuracy over 97.0% for both recall and precision in detection of the unsafe hand positions when the condition lasts for more than 6s, as well as over 97.1% recall and over 91.0% precision in detection of the unsafe hand movements when it lasts for more than 2.5s.
![](/images/research/network_ve_img1.png)

2. LEAD: Leveraging Protocol Signatures for Improving Wireless Link Performance. Error correction is a fundamental problem in wireless system design as wireless links often suffer high bit error rate due to the effects of signal attenuation, multipath fading and interference. We propose a new cross-layer solution called LEAD to improve the performance of existing channel decoders. While the traditional wisdom of cross-layer design is to exploit physical layer information at upper-layers, LEAD represents a paradigm shift in that it leverages upper-layer protocol signatures to improve the performance of physical layer channel decoding. The approach of LEAD is motivated by two key insights. First, channel codes can correct more errors when the values of some bits, which we refer to as pilots, are known before decoding. Second, some header fields of upper-layer protocols are often fixed or highly biased toward certain values. These distinctive bit pattern signatures can thus be exploited as pilots to assist channel decoding. To realize this idea, we first characterize bit bias in real-life network traffic, and develop an efficient algorithm to extract pilot bits with assured prediction accuracy. We then propose a decoding framework to allow existing channel decoders to effectively exploit extracted pilots. We implement LEAD on GNURadio/USRP platform and evaluate its performance by replaying real-life packet traces on a testbed of 12 USRP links. Our results show that LEAD significantly improve wireless link performance, while incurring very low overhead. Specifically, LEAD reduces more than 90% bit errors for 48.9% packets, and improves the end-to-end link throughput by 1.43x to 1.93x over existing error correction schemes.
![](/images/research/network_ve_img2.png)

3. Harnessing Hardware Defects for Improving Wireless Link Performance: Measurements and Applications. The design trade-offs of transceiver hardware are crucial to the performance of wireless systems. In this paper, we present an in-depth study to characterize the surprisingly notable systemic impacts of low-pass filter (LPF) design, which is a small yet indispensable component used for shaping spectrum and rejecting interference. Using a bottom-up approach, we examine how signal-level distortions caused by the trade-off of LPF design propagate to the upper-layers of wireless communication, reshaping bit error patterns and degrading link performance of today’s 802.11 systems. Moreover, we propose a novel algorithm that harnesses LPF defects for improving video streaming, which substantially enhances video quality in mobile environments. In order to precisely understand the performance of today's wireless systems, we conduct an in-depth study to characterize the surprisingly notable systemic impacts of hardware defects caused by component-level design trade-offs. To this end, we take Low-Pass Filter (LPF) -- a small yet indispensable component used for shaping spectrum and rejecting interference -- as an example, and study the impacts of its defects on the performance of off-the-shelf 802.11 systems. Our contribution is three-folds: 1) measurement of signal-level distortions caused by LPF defects; 2) characterization of the impacts of LPF defects on link reliability using standard-compliant emulation tools on a software-defined radio we built; and 3) harnessing LPF defects for mobile video streaming.
![](/images/research/network_ve_img3.png)
Setup of over-cable measurements using an USRP and a 2×2 MIMO AR9285 chip (the AR9285 is connected to an Agilent 8494B attenuator through an RCA DH24SP 2-way signal splitter, and the signal was measured from the main antenna port) and the projected power losses on subcarrier 26 for different transmitter and receiver pairs.