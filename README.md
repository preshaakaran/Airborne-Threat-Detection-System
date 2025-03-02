# Airborne Threat Detection System

A YOLO-based solution for detecting airborne threats using PyTorch. Supports both live webcam feed and video file analysis.

---

## 🛠️ Prerequisites
- [Anaconda/Miniconda](https://www.anaconda.com/download)
- NVIDIA GPU (recommended for CUDA acceleration)
- Python 3.10+

---

## 🚀 Quick Start

### 1. Clone & Navigate to Project
```cmd
cd C:\Users\<your_username>\Documents\volv_my_model
```

---

### 2. Create Conda Environment
```cmd
conda create -n volv-env1 python=3.10
conda activate volv-env1
```

---

### 3. Install Dependencies
```cmd
pip3 install --upgrade torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
```

---

## 💻 Usage

### Basic Command Structure
```cmd
python python_yolo_detect.py --model <MODEL_PATH> --source <INPUT_SOURCE> [--resolution <WxH>]
```

---

### Live Webcam Detection (1280x720)
```cmd
python python_yolo_detect.py --model my_model1.pt --source webcam --resolution 1280x720
```

**Expected Performance**: ~30 FPS

---

### Video File Detection
```cmd
python python_yolo_detect.py --model my_model1.pt --source candy_test1.mov
