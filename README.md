<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2ecc71,100:27ae60&height=200&section=header&text=SortEase&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Where%20Biomedical%20Waste%20Finds%20Its%20Place&descSize=20&descAlignY=55" width="100%"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI%20Powered-Biomedical%20Waste%20Sorting-2ecc71?style=for-the-badge" alt="AI Powered"/>
  <img src="https://img.shields.io/badge/Accuracy-93%25-27ae60?style=for-the-badge" alt="Accuracy"/>
  <img src="https://img.shields.io/badge/AIIMS%20Pulse-Hackathon%20Project-e74c3c?style=for-the-badge" alt="AIIMS Pulse"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black" alt="YOLOv8"/>
</p>

<p align="center">
  <a href="https://zenodo.org/badge/latestdoi/691037981">
    <img src="https://zenodo.org/badge/691037981.svg" alt="DOI"/>
  </a>
</p>

---

## Video Demonstration

<p align="center">
  <a href="https://drive.google.com/file/d/1HTSh1ZXPxuSx9p0cGADI5bKpb235OGjg/view?usp=drivesdk">
    <img src="https://img.shields.io/badge/▶%20WATCH%20DEMO-Click%20to%20Play-FF0000?style=for-the-badge&logo=youtube&logoColor=white&labelColor=FF0000" alt="Watch Demo" width="300"/>
  </a>
</p>

<p align="center">
  <a href="https://drive.google.com/file/d/1HTSh1ZXPxuSx9p0cGADI5bKpb235OGjg/view?usp=drivesdk">
    <img src="https://drive.google.com/thumbnail?id=1HTSh1ZXPxuSx9p0cGADI5bKpb235OGjg&sz=w1000" alt="SortEase Demo Video Thumbnail" width="600"/>
  </a>
</p>

<p align="center"><i>Click the image above to watch SortEase in action</i></p>

---

## The Problem

Biomedical waste facilities face critical challenges due to improper segregation at the source (hospitals, clinics). This happens due to:

- **Human Error:** Illiteracy, misinformation, and time constraints
- **Safety Hazards:** Manual sorting by workers is dangerous and inefficient
- **Health Risks:** Exposure to injuries from contaminated needles and sharp objects
- **Disease Transmission:** Increased risk of chronic infectious diseases like AIDS and Hepatitis

**Current Reality:** Workers manually pick and sort biomedical waste, exposing themselves to life-threatening hazards daily.

---

## The Solution: SortEase AI

SortEase replaces the human factor with a **Convolutional Neural Network (CNN)** that autonomously identifies and sorts biomedical waste.

<p align="center">
  <img src="https://github.com/ProxyAyush/SortEase/assets/65772478/c45e9c29-96fe-4250-ab78-bda55fb891e5" alt="Training Graphs" width="600"/>
</p>

### How It Works
┌─────────────┐    ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│   Waste     │───▶│   Camera    │───▶│  AI Model   │───▶│  Robotic    │
│  Conveyor   │    │  Detection  │    │  Processing │    │    Arm      │
└─────────────┘    └─────────────┘    └─────────────┘    └─────────────┘
│
▼
┌────────────────────────────┐
│  Sorted Bins: Plastic,     │
│  Rubber, Sharps, etc.      │
└────────────────────────────┘
1. Waste is loaded onto a **conveyor belt**
2. A **camera detects** materials in real-time
3. The **AI processes** images and classifies waste
4. A **robotic arm** sorts waste into appropriate bins

---

## Technical Specifications

| Specification | Details |
|---------------|---------|
| **Framework** | YOLOv8s (targeting FastVit for production) |
| **Accuracy** | ~93% detection accuracy |
| **Dataset** | Custom, production-quality labeled dataset |
| **Source** | KGMU Biomedical Waste Facility |
| **Sharps Detection** | 7 distinct categories |

### Detectable Sharps Categories

| Category | Type |
|----------|------|
| Blades | Sharp |
| Cannula with Cap | Sharp |
| Glass | Sharp |
| Instruments | Sharp |
| Needles | Sharp |
| Needle with Cap | Sharp |
| Syringes | Alert |

---

## Key Differentiators

| Feature | SortEase | Academic Models |
|---------|----------|-----------------|
| **Dataset** | Production-quality custom data from actual facility | Standard image libraries |
| **Real-world Testing** | Tested with actual biomedical waste | Lab conditions only |
| **Continuous Learning** | Self-improves with more data | Static |
| **Speed** | Faster than manual processing | N/A |

### Competitive Advantages

- **Operational Efficiency:** Faster than manual processing, reducing bottlenecks
- **Cost Reduction:** Automation reduces labor costs and liability
- **Safety Enhancement:** Eliminates worker exposure to hazardous materials
- **Environmental Compliance:** Ensures proper segregation as per regulations
- **Self-Learning:** Creates a competitive moat as the AI improves over time

---

## Business Model

SortEase operates on a **B2B subscription model** targeting Common Bio-medical Waste Treatment Facilities (CBWTFs).

| Revenue Stream | Details |
|----------------|---------|
| **Primary** | Monthly subscription: Rs 1,00,000/month |
| **Secondary** | Tiered pricing for advanced features |
| **Support** | Premium support packages |

**Operational Strategy:** Software solution company with outsourced hardware manufacturing.

---

## Getting Started

### Prerequisites

- Python 3.8+
- Visual Studio Code
- Webcam

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/ProxyAyush/SortEase.git
cd SortEase
Install dependencies
pip install ultralytics
pip install opencv-python
Configure the model path
Edit liveinference.py line 10:
model = YOLO("YOUR PATH TO best.pt")
Run the inference
python liveinference.py
A webcam window will open with real-time detection.
AIIMS Pulse Hackathon
This project was pitched at the AIIMS Pulse Hackathon, showcasing the potential of AI in healthcare waste management.
�
￼ 


Impact
Worker Safety: Eliminates exposure to hazardous biomedical waste
Disease Prevention: Reduces risk of AIDS, Hepatitis, and other infections
Operational Efficiency: Faster processing with fewer bottlenecks
Environmental Compliance: Proper segregation at the source
Scalable Solution: Ready for deployment across India and internationally
Connect
�
￼ ￼ 


Acknowledgments
King George's Medical University Environment Department for dataset access
Data collected with all necessary permissions under controlled conditions
AIIMS Pulse Hackathon for the platform to showcase this innovation
�
￼ 


�
Made with dedication by Dr. Ayush Yadav 

```