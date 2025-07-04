
# Multipurpose Agricultural Robotic System (MARS)

## Overview

India’s agricultural sector faces challenges such as labor scarcity, urban migration, and the need for sustainable farming practices. Traditional farming methods require intensive labor, while large machines cause soil compaction, reducing productivity. To address this, we developed the Multipurpose Agricultural Robotic System (MARS)—a lightweight, cost-effective robotic solution for small-scale farmers.

MARS performs key agricultural tasks including soil testing, sowing, weeding, and harvesting, while ensuring minimal impact on soil health.

## Project Objectives

- Automate core farming processes to reduce manual labor and operational costs.
- Avoid soil compaction by using a lightweight robotic platform.
- Integrate multiple agricultural functions into a single, modular robot.
- Make precision farming accessible to small and marginal farmers in India.

## Key Features

- Raspberry Pi 4B serves as the main microcontroller.
- DHT11 and EZO pH sensors for real-time soil and environment monitoring.
- MG996R servo motors for seed sowing, weeding tools, and gripper control.
- Parallel gripper mechanism for harvesting.
- Computer vision with OpenCV for weed detection and plant identification.
- Slider-crank mechanism for accurate seed spacing.
- Modular build allowing functions to be swapped or isolated.

## Implemented Functionalities

1. **Soil Testing**  
   Measures temperature, humidity, and pH to help determine suitable crops.

2. **Sowing**  
   Dispenses seeds with uniform spacing using servo-controlled mechanisms.

3. **Weeding**  
   Uses image processing and machine learning algorithms (SVM, K-means) to identify and remove weeds.

4. **Harvesting**  
   Employs a 3D-printed parallel gripper actuated by servo motors for safe crop collection.

## System Architecture

- **Microcontroller**: Raspberry Pi 4B  
- **Sensors**: DHT11 (temperature & humidity), EZO pH, soil moisture sensor  
- **Motors**: 12V DC gear motors (mobility), MG996R servo motors (task execution)  
- **Software Stack**: Python, OpenCV, Machine Learning (SVM, CNN), Tinkercad and MSC Adams (CAD)

## Results

- MARS was tested in real-world-like environments and successfully completed soil testing, sowing, weeding, and harvesting.
- The robot reduced seed wastage by ensuring precise placement.
- Its lightweight and energy-efficient design minimized environmental impact and power consumption.
- The system demonstrated potential for scalability and customization based on crop types and field size.

## Future Improvements

- Add AI-based crop monitoring using deep learning.
- Modularize the robot to allow farmers to use specific units (e.g., sowing or weeding) independently.
- Improve adaptability for various terrains and field conditions.

## Conclusion

MARS combines multiple agricultural processes into one integrated robotic system. Its compact design and automation capabilities make it a viable solution for sustainable and affordable agriculture, especially for small-scale farmers. The robot improves productivity, reduces manual labor, and supports precision agriculture practices.
