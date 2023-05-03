Analysis of DDoS Attacks in SDN Environments
Course: SYSTEM ADMIN AND SECURITY
Course Code: 6240

Overview:

SDN:



Software-Defined Networking (SDN) is an emerging architecture that is dynamic, manageable, cost-effective, and adaptable, making it ideal for the high-bandwidth, dynamic nature of today’s applications. This architecture decouples the network control and forwarding functions enabling the network control to become directly programmable and the underlying infrastructure to be abstracted for applications and network services.




DDos:

A cyber-attack known as a Denial-of-Service (DoS) aims to render a computer or network resource inaccessible to its intended users by interrupting the services of a host connected to the internet. This is usually achieved by overwhelming the target with excessive requests in an effort to overload its systems. If the incoming traffic flooding the victim originates from many sources, it becomes a Distributed Denial-of-Service (DDoS) attack, which cannot be stopped by blocking a single source alone. In SDN environments, we have adopted two approaches to identify DDoS attacks.
    1) Sample Entropy: The utilization of Sample Entropy as a means of identifying DDoS attacks in SDN involves two crucial elements: window size and a threshold. The window size can either be determined by a specified time frame or by the number of packets. Within this window, entropy is computed to determine the level of uncertainty in the upcoming packets. To flag an attack, a threshold value is necessary. The detection process involves checking if the calculated entropy surpasses or falls below the threshold, depending on the particular scheme in use.
    2) Principle Component Analysis: A mathematical technique is utilized to convert a set of (potentially) interrelated variables into a (reduced) set of independent variables, known as principal components. The initial principal component explains the maximum amount of variability present in the data, while each ensuing component explains the maximum amount of remaining variability.
