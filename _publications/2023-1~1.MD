---
title: "Cell-Free XL-MIMO Meets Multi-Agent Reinforcement Learning: Architectures, Challenges, and Future Directions"
excerpt: "In this article, we first review the essential opportunities and challenges induced by XL-MIMO systems. We then propose the enhanced paradigm of cell-free XL-MIMO, which incorporates multi-agent reinforcement learning (MARL) to provide a distributed strategy for tackling the problem of high-dimension signal processing and costly energy consumption."
permalink: /publications/2023-10-03-Paper-title-Cell-free XL-MIMO meets multi-agent reinforcement learning Architectures, challenges, and future directions
date: 2023-10-03
venue: 'IEEE Wireless Communications'
paperurl: 'https://arxiv.org/pdf/2307.02827.pdf'
thumbnail: /images/Paper/Paper7/Fig1.png
citation: 'Zhilong Liu, Jiayi Zhang, Ziheng Liu, Hongyang Du, Zhe Wang, Dusit Niyato, Mohsen Guizani, and Bo Ai, "Cell-Free XL-MIMO Meets Multi-Agent Reinforcement Learning: Architectures, Challenges, and Future Directions," IEEE Wireless Communications, accepted, 2023.'
---


[Download paper here](https://zhewang77.github.io/files/Cell-free XL-MIMO meets multi-agent reinforcement learning Architectures, challenges, and future directions.pdf)


**Abstract**: Cell-free massive multiple-input multiple-output (mMIMO) and extremely large-scale MIMO (XL-MIMO) are regarded as promising innovations for the forthcoming generation of wireless communication systems. Their significant advantages in augmenting the number of degrees of freedom have garnered considerable interest. In this article, we first review the essential opportunities and challenges induced by
XL-MIMO systems. We then propose the enhanced paradigm of cell-free XL-MIMO, which incorporates multi-agent reinforcement learning (MARL) to provide a distributed strategy for tackling the problem of high-dimension signal processing and costly energy consumption. Based on the unique near-field characteristics in XL-MIMO systems, we propose two categories of the low-complexity algorithm design, i.e., antenna selection and power control, to adapt to different cell-free XL-MIMO scenarios and meet the increasing data rate requirement. For inspiration, several critical future research directions pertaining to green cell-free XL-MIMO systems are presented.


**Index Terms**: Antenna selection, multi-agent reinforcement learning, power control, spectral efficiency, XL-MIMO

<br/><img src='/images/Paper/Paper7/Fig1.png' width = "700">

Fig. 1: System architecture and application scenarios of cell-free XL-MIMO systems around NFC. The BSs are equipped with XL-MIMO panels, and the user equipments are equipped with different numbers of antennas, from single to hundreds. BSs
and users are distributed in the service area. The BSs are connected to a CPU with a high computation processing ability via fronthaul links. The communication regions are divided into reactive near-field, radiative near-field, and far-field [4]. In XLMIMO
systems, the communication focuses on the radiative near-field. The boundary between radiative near-field and far-field is decided by the Rayleigh distance [7], [8], and visibility regions (VRs) induced by the non-stationary channel are illustrated since sheltering from different buildings and obstacles. In 2019, Ericsson proposed radio stripes, the prototype of cell-free mMIMO systems, which is an ideal deployment solution for outdoor and indoor areas such as shopping malls, stadiums, smart factories, and other scenarios [1].

<br/><img src='/images/Paper/Paper7/Fig2.png' width = "700">

Fig. 2: Summary of mainstream MARL technical frameworks, including Decentralized Training and Decentralized Execution (DTDE) and Centralized Training and Decentralized Execution (CTDE), algorithm categories, and applications in the existing literatures [7]-[10].

<br/><img src='/images/Paper/Paper7/Fig3.png' width = "700">

Fig. 3: The basic scheme of CTDE-based MADDPG algorithm interacting with cell-free XL-MIMO systems.

<br/><img src='/images/Paper/Paper7/Fig4.png' width = "700">

Fig. 4: The antenna selection of the BS that is equipped with a planar XL-MIMO. A BS simultaneously serves four UEs with different antennas, and different antennas serve different UEs without reuse. The different AS strategies depend on various criteria, e.g., maximizing the received signal power (criterion 1 and criterion 2), minimizing the inter-user interference (criterion 3) and so on.

<br/><img src='/images/Paper/Paper7/Fig5.png' width = "700">

Fig. 5: Boxplot of sum uplink SE and average EE of a cell-free XL-MIMO system under three circumstances: no selection (with all antennas of XL-MIMO panel activated), optimal channel selection based on the large-scale fading coefficients, and MADDPG-based selection. In the simulation, we consider the LSFD architecture [13] with single BS and multiple UEs. All BS and UEs are equipped with XL-MIMO panels.

<br/><img src='/images/Paper/Paper7/Fig6.png' width = "700">

Fig. 6: Sum uplink SE of cell-free XL-MIMO systems with different power control algorithms: the equal power method, MADDPG strategy, and D-MADDPG under different BS number M and XL-MIMO antennas number N. In the D-MADDPG architecture, we model the power control problem as the MARL framework with two layers. In the first layer, each agent corresponds to a BS in the cell-free XL-MIMO system, and the objective is to optimize its transmit power level to maximize system performance while taking into account interference from other agents. Then, with the constraint of BS power obtained in the first layer, the second layer is responsible for the allocation of each antenna of XL-MIMO panels. The simulation parameters are the same with Fig. 5.




