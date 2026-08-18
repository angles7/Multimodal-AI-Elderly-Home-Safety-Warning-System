# Multimodal-AI-Elderly-Home-Safety-Warning-System

Multimodal‑AI‑Elderly‑Home‑Safety‑Warning‑System

Project Introduction
Facing China's moderate aging society and the mainstream home‑based elderly care scenario, this project builds an integrated home elderly monitoring and early warning system based on the Ezviz Open Platform. The system includes three core functions: physical health risk prediction, real‑time mental emotion detection, and fraud risk identification for the elderly.

Different from traditional monitoring devices which only give alarms after falls happen, this project uses multimodal fusion artificial intelligence technology. Combining visual human pose data, physiological sensor readings, voice emotion features and mobile phone interaction data, the system realizes pre‑event prediction, in‑event warning and post‑event closed‑loop intervention for three types of risks including physical injury, psychological depression and property fraud.

Core Capabilities
1. Physical Health Risk Detection
Predict fall risk caused by abnormal gait, monitor sleep and activity rhythm. Track physiological indicators such as blood pressure and heart rate. Support three‑level risk warning including low risk, medium risk and high risk.

2. Real‑time Mental‑Emotion Monitoring
Classify user emotions into calm, pleasant, low‑spirited, irritable and lonely silent status through voice information. Complete long‑term trend analysis to screen early depression and loneliness risks. Send psychological care reminders to family members.

3. Anti‑Fraud Risk Identification
Identify high‑risk calls and suspicious visitor interactions with multimodal joint judgment. Play real‑time voice anti‑fraud reminders during risky calls. Save risk evidence and notify family contacts.

4. Auxiliary Functions
Support multi‑terminal message push for elderly voice terminal, family application and community management backend. Generate periodic comprehensive reports covering health, emotion and security status. Complete data desensitization on edge devices. Users can turn monitoring modules on or off manually.

System Architecture
The system adopts four‑layer structure: Perception Acquisition Layer, Multimodal Data Middle Platform, AI Risk Inference Layer, Early‑warning and Intervention Application Layer.

Perception Acquisition Layer: Visual cameras, physiological sensors, authorized mobile phone interaction data.
Multimodal Data Middle Platform: Ezviz open application programming interface, data encryption and standardized feature output.
AI Risk Inference Layer: Lightweight multi‑task Transformer fusion model, output risk score ranging from 0 to 100.
Early‑warning and Intervention Application Layer: Hierarchical warning push, report generation, linkage intervention for family and community.

Performance Indicators
Physical Health Detection: accuracy 95.1%, false‑alarm rate 4.2%
Emotion Real‑time Recognition: accuracy 90.7%, false‑alarm rate 4.8%
Anti‑Fraud Risk Identification: accuracy 94.2%, false‑alarm rate 3.7%

The overall system false‑alarm rate is controlled within 5 percent. Local edge inference ensures basic detection functions work under offline conditions.

Obtain Compiled Installation Package
Binary installation packages are released on GitHub Releases page.
This repository does not provide complete source code. Only documents and demo materials are stored here.

Deployment Guide
Please read Deployment_Instruction.md for complete deployment steps.

Privacy and Compliance
All sensing data is processed with desensitization on edge side. The system complies with Personal Information Protection Law of China. Users can enable or disable each monitoring module. Sensitive biometric information will not be collected without permission.

Project Background
This work is a research result for elderly‑care scenario competition. It solves three major problems of home‑dwelling elderly: fall risk, mental health problems, telecom and door‑to‑door fraud threats.

Future Optimization Directions
1. Expand sample library for wheelchair users and mildly disabled elderly people.
2. Connect community senior service platform application programming interface to realize automatic work order dispatch.
3. Support more brands of physiological monitoring hardware.
4. Build lightweight mini‑program for family members.

Intellectual Property Statement
All algorithm designs and system architecture belong to the development team. Please contact the team for commercial cooperation and intellectual property negotiation.

Disclaimer
This system serves as auxiliary early‑warning tool only. It cannot replace professional medical diagnosis or police law enforcement operations.
