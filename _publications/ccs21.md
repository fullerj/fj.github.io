---
title: "C3PO: Large-Scale Study Of Covert Monitoring of C&C Servers via Over-Permissioned Protocol Infiltration"
collection: publications
permalink: /publications/ccs21
citation: '<b>J. Fuller</b>, R. Kasturi, A. Sikder, B. Arik, H. Xu, V. Verma, E. Asdar, and B. Saltaformaggio, “C3PO: Large-Scale Study Of Covert Monitoring of C&C Servers via Over-Permissioned Protocol Infiltration," <i>In Proceedings of the 28rd ACM Conference on Computer and Communications Security (CCS)</i>, Seoul, South Korea, 2021.'
---
[//]: [[PDF]](https://fullerj.github.io/)

(To Appear)

## Abstract
Current techniques to monitor botnets towards disruption or take down are likely to result in inaccurate data gathered about the botnet or be detected by C&C orchestrators. Seeking a covert and scalable solution, we look to an evolving pattern in modern malware that integrates standardized over-permissioned protocols, exposing privileged access to C&C servers. We implement techniques to detect and exploit these protocols from over-permissioned bots toward covert C&C server monitoring. Our empirical study of 200k malware captured since 2006 revealed 62,202 over-permissioned bots (nearly 1 in 3) and 443,905 C&C monitoring capabilities, with a steady increase of over-permissioned protocol use over the last 15 years. Due to their ubiquity, we conclude that even though over-permissioned protocols allow for C&C server infiltration, the efficiency and ease of use they provide continue to make them prevalent in the malware operational landscape. This paper presents C3PO, a pipeline that enables our study and empowers incident responders to automatically identify over-permissioned protocols, infiltration vectors to spoof bot-to-C&C communication, and C&C monitoring capabilities that guide covert monitoring post infiltration. Our findings suggest the over-permissioned protocol weakness provides a scalable approach to covertly monitor C&C servers, which is a fundamental enabler of botnet disruptions and takedowns.
