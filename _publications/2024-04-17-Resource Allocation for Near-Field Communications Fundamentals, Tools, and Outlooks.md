---
title: "Resource Allocation for Near-Field Communications: Fundamentals, Tools, and Outlooks"
excerpt: "We review the basic properties of near-field communications and focus on the corresponding “resource allocation” problems. First, we identify available resources in near-field communication systems and highlight their distinctions from far-field communications. Then, we summarize optimization tools, such as numerical techniques and machine learning methods, for addressing near-field resource allocation, emphasizing their strengths and limitations. Finally, several important research directions of near-field communications are pointed out for further investigation."
collection: publications
permalink: /publications/2024-04-17-Resource Allocation for Near-Field Communications Fundamentals, Tools, and Outlooks
date: 2024-04-17
venue: 'IEEE Wireless Communications'
paperurl: 'https://arxiv.org/pdf/2310.17868.pdf'
thumbnail: /images/Paper/Paper10/Fig3.png
citation: 'Bokai Xu, Jiayi Zhang, Hongyang Du, Zhe Wang, Yuanwei Liu, Dusit Niyato, Bo Ai, and Khaled B. Letaief, “Resource Allocation for Near-Field Communications: Fundamentals, Tools, and Outlooks,”  IEEE Wireless Communications, accepted, 2024.'
---


[Download paper here](https://zhewang77.github.io/files/Resource Allocation for Near-Field Communications Fundamentals, Tools, and Outlooks.pdf)

**Abstract**: Extremely large-scale multiple-input-multipleoutput (XL-MIMO) is a promising technology to achieve high spectral efficiency (SE) and energy efficiency (EE) in future wireless systems. The larger array aperture of XL-MIMO makes communication scenarios closer to the near-field region. Therefore, near-field resource allocation is essential in realizing the above key performance indicators (KPIs). Moreover, the overall performance of XL-MIMO systems heavily depends on the channel characteristics of the selected users, eliminating interference between users through beamforming, power control, etc. The above resource allocation issue constitutes a complex joint multi-objective optimization problem since many variables and parameters must be optimized, including the spatial degree of freedom, rate, power allocation, and transmission technique. In this article, we review the basic properties of near-field communications and focus on the corresponding “resource allocation” problems. First, we identify available resources in near-field communication systems and highlight their distinctions from far-field communications. Then, we summarize optimization tools, such as numerical techniques and machine learning methods, for addressing near-field resource allocation, emphasizing their strengths and limitations. Finally, several important research directions of near-field communications are pointed out for further investigation.

**Index Terms**: Near-field communications, XL-MIMO, resource allocation, optimization algorithm, machine learning


<br/><img src='/images/Paper/Paper10/Fig1.png' width = "900">

Fig. 1: The major differences in resource allocation between near and far-field include beamforming, power control, and channel estimation. We consider a communication system with a frequency of 28GHz and an array aperture of 1m. Accordingly, the Rayleigh distance is 187m, and users are more likely located in the near-field region. The major application scenarios for near-field resource allocation include XL-MIMO systems, RIS-aided communication systems, and cell-free communication systems.

<br/><img src='/images/Paper/Paper10/Fig2.png' width = "900">

Fig. 2: Comparison of near-field and far-field channel characteristics.


<br/><img src='/images/Paper/Paper10/Fig3.png' width = "900">

Fig. 3: At the base station, the signal arrives at the receiver through resource allocation strategies such as precoding and power control, passing through the near-field channel. At the receiver, user grouping and scheduling strategies improve efficiency. Besides, we introduce three major challenges and solutions for near-field resource allocation.



<br/><img src='/images/Paper/Paper10/Fig4.png' width = "900">

Fig. 4: Near-field resource allocation problems and corresponding optimization problems and tools.



<br/><img src='/images/Paper/Paper10/Table1.png' width = "900">

Table 1: The optimization tools for near-field resource allocation and solutions include numerical optimization, heuristic optimization, and machine learning.

<br/><img src='/images/Paper/Paper10/Fig5.png' width = "900">

Fig. 5: Scenario 1: Beamforming design in XL-MIMO systems. The BS has N = 128 antennas and the carrier frequency is f = 30 GHz. Scenario 2: Power control in cell-free communication systems. The number of access points is 9, serving 6 receivers. The communication bandwidth is 20 MHz and the noise power is σ2 = −69 dBm. All transmitters transmit with a transmission power of no more than 200 mW

