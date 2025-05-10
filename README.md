# VisionAid - AI-Driven Diabetic Retinopathy Detection
#This is for SJIM Healthcare Hackathon
VisionAid is a scalable, AI-powered diagnostic solution designed to automate and enhance the detection of Diabetic Retinopathy (DR). Leveraging advanced machine learning models and Intel's cutting-edge technologies, VisionAid aims to provide early, accurate, and accessible DR diagnosis, particularly in underserved regions.

---

## Table of Contents

1. [Problem Statement](#problem-statement)  
2. [Motivation and Statistics](#motivation-and-statistics)  
3. [Proposed Solution](#proposed-solution)  
4. [Architecture Overview](#architecture-overview)  
5. [Tech Stack](#tech-stack)  
6. [Novelty and Expected Results](#novelty-and-expected-results)  
7. [Setup and Installation](#setup-and-installation)  
8. [Usage](#usage)  
9. [Team Members](#team-members)  

---

## Problem Statement

Diabetic Retinopathy (DR) is a leading cause of preventable blindness among diabetic patients. However, early detection methods are inaccessible in many underserved areas due to:

- Dependency on specialized expertise.  
- Slow and error-prone traditional diagnostic methods.  
- Limited availability of trained ophthalmologists.  

---

## Motivation and Statistics

### Motivation  
- Early detection can prevent severe vision impairment.  
- AI solutions can offer fast, accurate, and scalable diagnostic support.  

### Statistics  
- Around 30% of diabetic patients develop DR, risking severe vision impairment if undiagnosed.  
- 70% of DR cases in rural areas remain undetected due to limited facilities.  

---

## Proposed Solution

VisionAid utilizes deep learning models to classify DR stages with high accuracy. The solution incorporates Intel's AI technologies for optimized performance and deployment.  

### Key Features  
- **Automated DR Detection:** AI models classify DR stages.  
- **Optimized Performance:** Powered by Intel's NPU and OpenVINO Toolkit.  
- **Real-Time Diagnostics:** Deployed on edge devices for remote areas.  

---

## Architecture Overview

### Diagram  
![Architecture Diagram](https://github.com/Krixna-Kant/VisionAid-intel/blob/main/VisionAid/images/image.png)  


### Components  
1. **AI Model**: ResNet50 trained on Kaggle’s DR dataset.  
2. **Edge Deployment**: Real-time inference with Intel hardware accelerators.  
3. **Telemedicine Integration**: Enables remote diagnostic workflows.  

---

## Tech Stack

### Hardware  
- Intel AI PC with NPU  
- Intel® Arc™ GPU  

### Software & Frameworks  
- PyTorch  
- OpenVINO™ Toolkit  
- Intel Extension for PyTorch  

### Optimization Libraries  
- Intel® Neural Compressor  
- Intel® AI Analytics Toolkit  

### Development Tools  
- Jupyter Notebooks  
- Visual Studio Code  
- Docker  

---

## Novelty and Expected Results

### Novelty  
- Optimized real-time DR detection using Intel's AI Stack.  
- Deployment on edge devices to overcome resource constraints.  

### Expected Results  
- **Model Accuracy:** 79%+ after optimization.  
- **Diagnostic Speed:** 10x faster than manual screening.  
- **Accessibility:** Improved healthcare outcomes in underserved areas.  

---

## Setup and Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/VisionAid.git

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt

3. Run the application:
   ```bash
   python app.py

---

## Usage

1. Upload retinal images for diagnosis.  
2. The AI model analyzes and classifies the DR stage.  
3. View results through the user interface or telemedicine platform.  

---

## Team Members

**Team Name**: Squirtles  

- **Ashish K Choudhary**  
- **Krishna**  

