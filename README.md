# Car-object-detection-with-YOLO-World

# YOLO-World: Efficient Zero-Shot Object Detection

YOLO-World is a state-of-the-art object detection model that tackles a critical limitation of existing zero-shot object detection architectures: **speed**. While many contemporary models utilize powerful but slower Transformer-based architectures, YOLO-World employs the faster and more efficient Convolutional Neural Network (CNN)-based YOLO (You Only Look Once) architecture. This allows YOLO-World to achieve high detection accuracy with significantly higher frames per second (FPS) compared to Transformer-based models.

## Key Features

- **Speed:** YOLO-World is designed to prioritize speed while maintaining high accuracy. By using a CNN-based architecture, YOLO-World performs object detection faster than Transformer-based models, making it suitable for real-time applications.
- **Zero-Shot Learning:** Like other state-of-the-art zero-shot object detection models, YOLO-World can detect and recognize objects that it hasn't seen during training, making it highly versatile in various scenarios.
- **Scalable Versions:** YOLO-World comes in different versions, optimized for various hardware configurations and performance requirements.

## Performance

YOLO-World delivers impressive results in terms of both accuracy and speed. According to the paper, the performance metrics for the model are as follows:

- **YOLO-World Large:**
  - **Average Precision (AP):** 35.4
  - **Frames Per Second (FPS):** 52.0
- **YOLO-World Small:**
  - **Average Precision (AP):** 26.2
  - **Frames Per Second (FPS):** 74.1

These results were obtained using an NVIDIA V100 GPU, which is a powerful device. Achieving such high FPS on any device is impressive, particularly for a model focused on zero-shot object detection.

## Architecture

YOLO-World uses the well-known YOLO architecture, which is based on Convolutional Neural Networks (CNNs). This architecture is favored for its balance of speed and accuracy. YOLO-World's implementation has been optimized to handle the demands of zero-shot object detection efficiently, outperforming traditional Transformer-based models in speed while still providing competitive accuracy.

## Visualization Results: Referring Object Detection

YOLO-World also excels in referring object detection tasks. Referring object detection involves detecting objects that are described in natural language. YOLO-World's efficient architecture makes it possible to handle these complex tasks quickly, offering real-time visualization results.

For example, given a phrase like "the red car on the left," YOLO-World can identify and locate the referred object with both speed and accuracy, making it ideal for applications that require real-time interaction, such as robotics and augmented reality.

![image](https://github.com/user-attachments/assets/7b2a1dce-bfee-48a0-8ca2-eb953b6375a4)


## Getting Started
Notebook settings -> Hardware accelerator, set it to GPU, and then click Save.
