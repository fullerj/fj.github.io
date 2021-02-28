---
title: "Wireless Intrusion Detection of Covert Channel Attacks in ITU-T G.9959-based Networks"
collection: publications
permalink: /publications/iccws15
citation: '<b>J. Fuller</b>, B. Ramsey, J. Pecarina, and M. Rice, “Wireless Intrusion Detection of Covert Channel Attacks in ITU-T G.9959-based Networks," <i>11th International Conference on Cyber Warfare and Security (ICCWS)</i>, pp 137-145, 2015.'
---
[[PDF]](https://fullerj.github.io/files/iccws15.pdf)


## Abstract
We introduce herein an information hiding technique for injecting manipulated packets into wireless sensor networks (WSNs). We exhibit how an attacker can apply information hiding as a type of covert channel attack over radio frequency transmissions into the WSN. The feasibility of our injection method is demonstrated through an attack on the most common implementation of the ITU-T G.9959 recommendation, commercially known as Z-Wave. More specifically, we illustrate that after accessing a Z-Wave gateway controller through compromising the WLAN backbone, the attacker has the ability to install malware. The malware scans incoming Z-Wave packets for information hidden in Media Access Control (MAC) frames received by the Z-Wave controller. Upon identification of hidden information, a Reverse Secure Shell is initiated through the WLAN back to the attacker. The outcomes of this attack include control of the Z-Wave network and access to the networked devices on the target WLAN from any Internet connected device. Given this new application of information hiding techniques to Z-Wave networks, we recognize the need for countermeasures. We therefore offer an effective Misuse-based Intrusion Detection System (MBIDS) capable of distinguishing between manipulated and correctly formed packets. A Universal Software Radio Peripheral (USRP) Software-Defined Radio (SDR) is used in conjunction with a packet monitoring tool capturing incoming transmissions and inspecting them for any violations of the ITU-T G.9959 MAC specification. We then analytically and experimentally estimate the efficacy of the USRP as a packet capture device in a realistic test setup, and then evaluate the total efficiency of our MBIDS solution. By employing the MBIDS in the Z-Wave network, we show the MBIDS is capable of detecting packet manipulation attacks with 92% mean accuracy.