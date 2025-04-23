This project demonstrates techniques for deploying and optimizing Edge AI models for real-time inference with a focus on latency reduction.

## 📁 Project Structure
- `models/`: Pretrained and converted models.
- `scripts/`: Python scripts for detection, conversion, quantization, benchmarking.
- `notebooks/`: Jupyter notebooks for visualization.

## 🚀 Setup
```bash
git clone https://github.com/111221007/EdgeAI_TestCase1.git
cd edge-ai-latency-lab
pip install -r requirements.txt
```

## 📷 Real-Time Object Detection (YOLOv5)
```bash
python scripts/detect_yolov5.py --source 0
```

## 🔁 Convert to ONNX
```bash
python scripts/convert_to_onnx.py
```

## 📉 Quantize Model
```bash
python scripts/quantize_onnx.py
```

## 🧍 Activity Recognition (MobileNet + TFLite)
```bash
python scripts/activity_recognition.py
```

## 📊 Run Benchmark
```bash
python scripts/benchmark.py
```

## 📈 Jupyter Notebook
```bash
jupyter notebook notebooks/latency_vs_accuracy.ipynb
```

## 📜 License
MIT License
