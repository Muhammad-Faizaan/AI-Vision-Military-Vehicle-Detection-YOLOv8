# AI-Vision-Military-Vehicle-Detection-YOLOv8

https://github.com/user-attachments/assets/70800a84-d738-47c4-b971-c381ff8b54ec


  
## 🔹 About
This project implements **enhanced small object detection using YOLOv8**, targeting objects smaller than 32x32 pixels.  
It provides **training, validation, and CLI-based inference scripts** along with a **sample video** to test the model.

**Goal:** Improve detection accuracy for tiny objects in real-world or simulated environments.

---

## 🔹 Key Features
- 🎯 **SmallObjectLoss Function**: Optimized loss for tiny object detection  
- ⚡ **Customized YOLOv8 model**: Adjustable thresholds and dynamic scaling  
- 🧪 **CLI Testing**: Run inference on images or videos easily  
- 📊 **Validation metrics**: Evaluate precision, recall, and detection performance  
- 📹 Includes `test_video.mp4` for demo purposes  

---

## 🔹 Repository Structure
```

AI-Vision-Military-Vehicle-Detection-YOLOv8/
│
├── README.md
├── .gitignore
├── .gitattributes
├── train.py          # Train YOLOv8 model
├── validation.py     # Evaluate model performance
├── cli_tester.py     # Run inference on images/videos
└── test_video.mp4    # Sample video for testing

````

---

## 🔹 Installation
```bash
git clone https://github.com/Muhammad-Faizaan/AI-Vision-Military-Vehicle-Detection-YOLOv8.git
cd AI-Vision-Military-Vehicle-Detection-YOLOv8
pip install -r requirements.txt
````

> Python 3.9+ recommended

---

## 🔹 Usage

### 1. Train Model

Prepare your dataset in YOLO format, then run:

```bash
python train.py
```

### 2. Validate Model

Check performance metrics:

```bash
python validation.py
```

### 3. Test / Inference

Run detection on sample or custom video/image:

```bash
python cli_tester.py --source test_video.mp4
```

> Replace `test_video.mp4` with your own file if needed.

---

## 🔹 Notes

* **No full dataset included** — users must provide their own for training.
* `test_video.mp4` is included **for demonstration only**.

---

## 🔹 Requirements

```txt
torch>=2.0.0
ultralytics>=8.0.0
opencv-python
numpy
matplotlib
pyyaml
```

---

## 🔹 GitHub Topics

`yolov8` · `small-object-detection` · `computer-vision` · `object-detection` ·
`deep-learning` · `pytorch` · `AI-research` · `real-time-detection`

---

## 🔹 License

MIT License © Muhammad Faizaan

```

