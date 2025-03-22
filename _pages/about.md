---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
# Homepage

I received my Ph.D degree in Traffic Information Engineering and Control from <a href="https://www.shmtu.edu.cn/">Shanghai Maritime University</a> in 2023. From 2021 to 2022, I was a visiting Ph.D. Student in Electrical and Computer Engineering with the <a href="https://www.uvic.ca/">University of Victoria</a>, Canada. I am currently a lecturer with the School of Computer and Information Engineering, <a href="https://www.czu.cn/">Changzhou Institute of Technology</a>. I have published 20+ papers with 
 <a href='https://scholar.google.com.hk/citations?view_op=list_works&hl=zh-CN&hl=zh-CN&user=oZ7fkzcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

My research interest includes: 
- Wireless and Underwater Sensor Networks
- Target localization and tracking
- Wireless Communications, signal processing
- Deep Learning and Intelligent Optimization

# 📖 Work Experience

- 2023.5 - present,	Lecturer, Changzhou Institute of Technology

# 🎓 Educations 

- Ph.D. in Traffic Information Engineering and Control, Shanghai Maritime University, Apr. 2023 (Advisor: Prof. Huafeng Wu(<a href="https://baike.baidu.com/item/%E5%90%B4%E5%8D%8E%E9%94%8B/5136139">吴华锋教授</a>)
- Visiting Ph.D. in the Electrical and Computer Engineering, University of Victoria, Victoria, Canada, Sep. 2021 - Sep. 2022 (Advisor: Prof. <a href="https://www.uvic.ca/ecs/ece/faculty-and-staff/home/faculty/gullivert.-aaron.php">T. Aaron Gulliver</a>)
- M.S. in Traffic Information Engineering and Control, Shanghai Maritime University, Sep. 2023 (Advisor: Prof. Huafeng Wu(<a href="https://baike.baidu.com/item/%E5%90%B4%E5%8D%8E%E9%94%8B/5136139">吴华锋教授</a>)

# 📝 Publications 

### Journal publications
---
- Y. Zhang, J. Li, T. A. Gulliver, H. Wu, G. Xie, X. Mei, J. Xian, W. Wang, L. Liang, "<b>Metaheuristic Optimization for Robust RSSD-Based UAV Localization with Position Uncertainty<\b>, " Drones, vol. 9, no. 2, p. 147, 2025. (SCI，JCR Q1，IF： 4.4)[[HTML]](https://doi.org/10.3390/drones9020147) 
- Y. Zhang, T. A. Gulliver, H. Wu, X. Mei, J. Li, F. Lu, W. Wang, "An Efficient Estimator for Source Localization in WSNs using RSSD and TDOA Measurements, " Pervasive and Mobile Computing, vol. 102, art. 101936, 2024. (SCI，JCR Q2，IF： 4.3)
- Y. Zhang, H. Wu, T. A. Gulliver, X. Li, J. Li, J. Xian, W. Wang, "Real-Time RSS-based Target Localization for UWSNs using an IDE-BP Neural Network," Journal of Supercomputing, vol. 80, pp.20150-20175, 2024. (SCI，JCR Q2，IF： 3.3)
- Y. Zhang, H. Wu, T. A. Gulliver, J. Xian, L. Liang, "Improved Differential Evolution for RSSD-Based Localization in Gaussian Mixture Noise," Computer Communications, vol. 206, pp. 51-59, 2023. (SCI，JCR Q1，IF：6.0)
- Y. Zhang, H. Wu, T. A. Gulliver, J. Xian, W. Wang, "Fast Multi-Target Localization of RSSD in Wireless Sensor Networks," Transactions of the Institute of Measurement and Control, 2023, doi: 10.1177/01423312221148787. (SCI，JCR Q3，IF：1.8)
- Y. Zhang, H. Wu, X. Mei, L. Liang, T. A. Gulliver, "Unknown Transmit Power RSSD Based Localization in a Gaussian Mixture Channel," IEEE Sensors Journal, vol. 22, no. 9, pp. 9114-9123, 2022. (SCI，JCR Q1，IF：4.3)
- Y. Zhang, H. Wu, X. Mei, J. Xian, W. Wang, Q. Zhang, L. Liang, "Two-Phase Robust Target Localization in Ocean Sensor Networks Using Received Signal Strength Measurements," Sensors, vol. 21, no. 5, p. 1724, 2021. (SCI，JCR Q2，IF：3.9)
-  Y. Zhang, H. Wu, J. Xian, and X. Mei, “Adaptive clustering algorithm in Ocean Wireless Sensor Network under double constraints,” Computer Engineering Application, vol. 19, no. 55, pp. 128–133, 2019. （EI）
-  H. Wu, Y. Zhang, J. Wang, W. Wang, J. Xian, J. Chen, X. Zhou, P. Mohapatra, "iOceanSee: A Novel Scheme for Ocean State Estimation Using 3D Mobile Convolutional Neural Network, " IEEE Access, vol. 8, pp. 153774-153786, 2020. (SCI，JCR Q2，IF：3.9)
-  J. Li, Y. Zhang, L. Shen, J. Cao, W. Xie, Y. Zheng, S. Liu, "An Efficient and Secure Authentication Scheme with Session Key Negotiation for Timely Application of WSNs," KSII Transactions on Internet and Information Systems, vol. 18, no. 3, pp. 801-825, 2024. (SCI，JCR Q4，IF：1.5)
-  H. Wu, L. Liang, X. Mei, Y. Zhang, "A Convex Optimization Approach For NLOS Error Mitigation in TOA-Based Localization," IEEE Signal Processing Letters, vol. 29, pp. 677-681, 2022. (SCI，JCR Q2，IF：3.9)
-  W. Wang, H. Wu, X. Kong, Y. Zhang, Y. Ye, Z. Zeng, J. Cheng, Q. Zhang, "Reinforcement Learning-based Dynamic Position Control of Mobile Node for Ocean Sensor Networks," Transactions of the Institute of Measurement and Control, vol. 44, no. 4, pp. 926-940, 2022. (SCI，JCR Q3，IF：1.8)
-  J. Xian, H. Wu, X. Mei, Y. Zhang, X. Chen, Q. Zhang, L. Liang," Novel Energy-Efficient Opportunistic Routing Protocol for Marine Wireless Sensor Networks Based on Compressed Sensing and Power Control," Journal of Ocean University of China, vol. 21, no. 6, pp. 1504–1516, 2022. (SCI，JCR Q3，IF：1.6)
-  J. Xian, H. Wu, X. Mei, Y. Zhang, H. Chen, J. Wang, "NMTLAT: A New robust mobile Multi-Target Localization and Tracking Scheme in marine search and rescue wireless sensor networks under Byzantine attack," Computer Communications, vol. 160, pp. 623–635, 2020. (SCI，JCR Q1，IF：6.0)
-  H. Wu, J. Xian, X. Mei, Y. Zhang, J. Wang, J. Cao, and P. Mohapatra, "Efficient target detection in maritime search and rescue wireless sensor network using data fusion," Computer Communications, vol. 136, pp. 53–62, 2019. (SCI，JCR Q1，IF：6.0)
-  J. Ma, J. Xian, H. Wu, Y. Yang, X. Mei, Y. Zhang, X. Chen, C. Zhou, "Novel High-Precision and High-Robustness Localization Algorithm for Underwater-Environment-Monitoring Wireless Sensor Networks," Journal of Marine Science and Engineering, vol. 11, no. 9, p. 1713, 2023. (SCI，JCR Q1，IF：2.7)
-  Q. Zhang, H. Wu, L. Liang, X. Mei, J. Xian, Y. Zhang, "A Robust Sparse Sensor Placement Strategy Based on Indicators of Noise for Ocean Monitoring," Journal of Marine Science and Engineering, vol. 12, no. 7, p. 1220, 2024. (SCI，JCR Q1，IF：2.7)
-  X. Mei, F. Miao, W. Wang, H. Wu, B. Han, Z. Wu, X. Chen, J. Xian, Y. Zhang, Y. Zang, "Enhanced Target Localization in the Internet of Underwater Things through Quantum-Behaved Metaheuristic Optimization with Multi-Strategy Integration," Journal of Marine Science and Engineering, vol. 12, no. 6, p. 1024, 2024. (SCI，JCR Q1，IF：2.7) 
-	J. Xian, J. Ma, H. Wu, X. Mei, F. Tan, Y. Zhang, X. Chen, W. Wang, "Coarse-to-Fine Localization Method for UASNs under Unknown Multi-Parameters, " Control and Decision, 2024, doi: 10.13195/j.kzyjc.2024.0521. （EI）
-	J. Xian; Z. Li; H. Wu, W. Wang, X. Chen, X. Mei, Y. Zhang, B. Han; J. Ma, "Novel Polarization Construction Method and Synchronization Algorithm for Underwater Acoustic Channel under T-distribution Noise Environment," Journal of Marine Science and Engineering, vol. 13, no. 2, p. 362, 2025. (SCI，JCR Q1，IF：2.7) 

### Conference publications
---
- J. Xian, Z. Li, H. Wu, X. Mei, X. Chen, Y. Zhang, L. Liang, Qi. Zhang, and W. Wang "A novel polar codes construction method for OFDM hydroacoustic communication system under t-distribution noise", Proc. SPIE 13542, Fourth International Computational Imaging Conference (CITA 2024), 135423S (25 February 2025).
- X. Mei, H. Wu, J. Xian, H. Zhang, and Y. Zhang, “A Robust Localization with Outlier Measurements in Underwater Sensor Networks”, Proceedings of the 2019 Academic Conference of the Chinese Acoustics Society Hydroacoustic Branch, Nanjing, China.

### Submitted/prepared papers
---
-	Y. Zhang, T. A. Gulliver, H. Wu, J. Li, X. Mei, J. Xian, K.-C. Li, “3-D RSSD Localization under Mixed Gaussian Noise and NLOS environments in UWSNs,” IEEE Internet of Things Journal, 2025.（under review）(SCI，JCR Q1，IF：8.2)
-	L. Liang, H. Wu, X. Mei, Q. Zhang, Y. Zhang, J. Xian, K.-C. Li, "Robust 3D Target Localization in WSNs: A RotQCP Approach for NLOS Mitigation ” IEEE Internet of Things Journal, 2025.（under review）(SCI，JCR Q1，IF：8.2)
-	Y. Zhang, G. Xie, T. A. Gulliver, H. Wu, X. Mei, “Bias Mitigation for RSSD-Based Localization under Byzantine Attacks,” Electronics Letters, 2024.（under review）
-	Y. Zhang, et. al, “Maximum Correntropy Criterion Based Target tracking in NLOS UWSNs” (In preparation)
-	Y. Zhang, et. al, “RSSD Based 3-D Localization under Spoofing Attacks for Internet of Underwater Things” (In preparation)

# 🎖 Honors and Awards
- *2023* Win the Outstanding Research Award.
- *2022* Win the Outstanding Research Award.
- *2021* Win the National Study Abroad Fund(Awarded by China Scholarship Council (CSC)).
- *2020* Win the Principal Scholarship(Awarded by Shanghai Maritime University, Office of Graduate Studies).

# 💬 Projects
### Principle Investigator
---
- Research on Key Technologies of Localization and Tracking in Ocean Sensor Networks, Grant No. CJ20240068 (Sponsored by Changzhou Science and Technology Committee)
-	Application of Underwater Acoustics and Wireless Sensor Network in Transportation, Grant No. 202108310196 (Sponsored by China Scholarship Council)

### Participation
---
- Theory and Key Technologies for Optimal Dynamic Deployment of Polar Situational Awareness Cluster System, Grant No. 52331012 (Sponsored by Natural Science Foundation of China)
-	Research on Key Technologies and System Development of Communication and Navigation Support in the Arctic waterway, Grant No.2021YFC2801002 (Sponsored by National Ministry of Science and Technology)
-	Dynamic Self-adaptive Clustering Based Intelligent Data Prediction and Reconstruction in Ocean Sensor Networks, Grant No. 52071200 (Sponsored by Natural Science Foundation of China)
-	Research on Key Technologies of Distributed Estimation and Optimization of Marine Intelligent Clustered Sensor Networks Based on Deep reinforcement learning, Grant No. 23010502000 (Sponsored by Shanghai Science and Technology Committee)
-	Three-Dimensional Dynamic Cooperative Localization Mechanism of Marine Sensor Networks Based on Wave Shadowing Effect Model, Grant No. 51579143 (Sponsored by Natural Science Foundation of China)
-	Coastal Meteorological Monitoring and Warning System Based on Buoy Internet of Things and Its Navigation Aid Application, Grant No. 18040501700 (Sponsored by Shanghai Science and Technology Committee)
 
# 🏭 Acitivies
- China Computer Federation Member
- China Highway& Transportation Society Member
- Reviewer of IEEE Transactions on Signal and Information Processing over Networks
- Reviewer of IEEE Transactions on Vehicular Technology
- Reviewer of IEEE Signal Processing Letters
- Reviewer of Journal of Supercomputing
-	Reviewer of Concurrency and Computation: Practice and Experience
-	Reviewer of IEEE Sensors Letters
-	Reviewer of Sensors 
-	Reviewer of Electronics

# 📚 Teaching
- Literature Retrieval and Scientific Paper Writing, 2024-2025-2
- Basics of Computer Circuits, 2024-2025-2
- Digital Logic System Course Design, 2023-2024-1/2024-2025-1
- Digital Logic and Digital System Design, 2023-2024-1/2024-2025-1

# 🔥 News 
-
