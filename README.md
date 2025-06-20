# PCB-Defect-Detection-using-YOLOv8x
PCB- Defect Detection using YOLOv8x a Research Project
In this project, we designed and implemented YOLOv8x-HICAUps, a cutting-edge deep learning model aimed at automating the detection of surface defects in Printed Circuit Boards (PCBs) with high precision and efficiency. The model introduces several key innovations:

HorNet Backbone: Enhances feature extraction from high-density PCB layouts by capturing intricate textures and micro-patterns.

CBAM Attention Module: Improves focus on defect-relevant regions by combining spatial and channel attention, leading to more accurate detection of subtle anomalies like mouse bites, spurs, and pinholes.

Attention-Based Upsampling: Retains fine-grained details during the decoding phase to avoid blurring of small defects and ensures better boundary preservation.

Lightweight Detection Head: Tailored for real-time inference on embedded hardware and edge devices, balancing speed and accuracy.

The model was extensively evaluated on standard PCB defect datasets and achieved a detection accuracy of 98.3%, outperforming state-of-the-art approaches. Designed with deployment in mind, YOLOv8x-HICAUps bridges the gap between academic research and practical manufacturing applications, offering a scalable, low-complexity, and high-performance solution for smart electronics inspection.
