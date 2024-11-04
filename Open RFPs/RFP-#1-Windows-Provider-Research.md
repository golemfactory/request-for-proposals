# RFP #1: Research for Golem Provider Support on Windows Platform


**Published by:** Golem Factory  
**Funding Source:** Golem Network Ecosystem Fund  
**Status:** Open  
**Funding Amount:** TBA

---

## Overview

The Golem Network currently supports providers on Linux-based systems, utilizing the KVM (Kernel-based Virtual Machine) module to securely create virtual machines (VMs) where tasks are executed. This security layer is critical to the integrity of the Golem Network, as it ensures that computational tasks are isolated, protecting both the provider and the requestor. However, as Windows remains a widely-used platform, expanding provider support to Windows could significantly enhance network accessibility and broaden Golem’s user base.

This RFP seeks to fund research that explores the feasibility, challenges, and security implications of developing a Golem provider on the Windows platform. The primary focus is to identify secure, effective methods within the Windows environment that replicate the isolation and security provided by KVM on Linux.

## Scope of Research

The research should cover:

1. **Security Requirements**  
   - Outline the essential security criteria needed to maintain isolation and protection on the Windows platform, equivalent to the standards met by KVM on Linux.

2. **Windows-based Virtualization Alternatives**  
   - Investigate viable Windows virtualization technologies (e.g., Hyper-V, Docker for Windows, WSL2) and assess their suitability for task isolation within a decentralized compute network.

3. **Comparative Analysis and Recommendations**  
   - Compare potential Windows solutions with the current Linux-based approach, identifying benefits, limitations, and potential security risks.
   - Provide recommendations on the best solution(s) for implementing Windows support.

4. **Implementation Roadmap**  
   - Propose a high-level roadmap detailing the steps required to bring Windows-based providers to the Golem Network, including required tools or modifications.

## Deliverables

1. **Research Report**  
   - A comprehensive document detailing findings in each area above, including technology comparisons, security assessments, and recommended solutions.

2. **Security and Feasibility Assessment**  
   - A summary assessing the feasibility of secure Windows support, highlighting any identified risks or challenges.

3. **Implementation Roadmap**  
   - A suggested roadmap for integrating the recommended Windows solution into the Golem Network, with estimated development requirements.

---

## Submission Instructions

Please submit your proposal via our [ecosystem page](https://ecosystem.golem.network/). Ensure that your proposal follows the guidelines and requirements listed at the bottom of the ecosystem fund page. When submitting, reference **RFP #1: Windows Provider Research** to help us categorize your application.

---

This RFP is an opportunity to contribute to expanding Golem Network's infrastructure and accessibility. We look forward to proposals that bring secure, reliable provider support to the Windows platform.
