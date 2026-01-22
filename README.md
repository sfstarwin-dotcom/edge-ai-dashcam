<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Edge AI Dashcam Anomaly Detector</h1>

<p>Build an edge AI application on Raspberry Pi that processes dashcam footage in real-time to detect and log road anomalies such as potholes and unexpected obstacles.</p>

<h2>Project Description</h2>

<p>Students will choose a lightweight object detector (e.g., MobileNet-SSD, YOLOv5s), convert it to an edge-optimized format (TensorFlow Lite / ONNX Runtime), and integrate it with an OpenCV video pipeline. Detected anomalies should trigger timestamped logs or saved clips.</p>

<h2>Key Requirements</h2>

<h3>Hardware</h3>
<ul>
    <li>Raspberry Pi 4 with proper cooling</li>
    <li>Raspberry Pi Camera Module v2 or USB webcam</li>
    <li>High-write-speed microSD card</li>
</ul>

<h3>Software</h3>
<ul>
    <li>Raspberry Pi OS</li>
    <li>Python, OpenCV</li>
    <li>TensorFlow Lite / ONNX Runtime with a pre-trained, quantized detection model</li>
</ul>

<h2>Performance Targets</h2>
<ul>
    <li>&ge;5 FPS near-real-time inference</li>
    <li>High precision to reduce false positives in logging</li>
    <li>Robust under varying lighting conditions</li>
</ul>

<h2>Deliverables</h2>
<ul>
    <li>Source code for video processing and inference pipeline</li>
    <li>Optimized deployed model file (.tflite / .onnx)</li>
    <li>Demo video with anomaly detection on sample footage</li>
    <li>Report on model choice, optimization and performance</li>
</ul>

<h2>Learning Outcomes</h2>
<ul>
    <li>Optimizing and deploying neural networks for edge video analytics</li>
    <li>Experience with embedded vision pipelines</li>
    <li>Understanding accuracy vs speed vs compute trade-offs on Arm platforms</li>
</ul>

<h2>Project Phases</h2>

<h3>Phase 1: Environment Setup & Model Selection (Week 1)</h3>
<ul>
    <li>Install Raspberry Pi OS and dependencies</li>
    <li>Select and benchmark lightweight detection models</li>
    <li><strong>Deliverable</strong>: Working environment, model comparison table</li>
</ul>

<h3>Phase 2: Model Optimization (Week 2)</h3>
<ul>
    <li>Convert selected model to TFLite/ONNX</li>
    <li>Quantize model for edge deployment</li>
    <li>Benchmark inference speed on RPi</li>
    <li><strong>Deliverable</strong>: Optimized .tflite/.onnx model file</li>
</ul>

<h3>Phase 3: Video Pipeline Development (Week 3)</h3>
<ul>
    <li>Build OpenCV camera pipeline</li>
    <li>Integrate model inference</li>
    <li>Implement anomaly detection logic</li>
    <li><strong>Deliverable</strong>: Basic detection prototype</li>
</ul>

<h3>Phase 4: Logging & Alert System (Week 4)</h3>
<ul>
    <li>Add timestamped logging for detections</li>
    <li>Implement clip saving on anomalies</li>
    <li>Optimize for &ge;5 FPS performance</li>
    <li><strong>Deliverable</strong>: Complete working application</li>
</ul>

<h3>Phase 5: Testing & Demo (Week 5)</h3>
<ul>
    <li>Test under varying lighting conditions</li>
    <li>Record demo video</li>
    <li>Write final report</li>
    <li><strong>Deliverable</strong>: Demo video, final report, source code</li>
</ul>

<h2>Installation & Setup</h2>

<pre><code># Clone repository
git clone &lt;your-repo&gt;
cd edge-ai-dashcam

# Install dependencies
pip install -r requirements.txt

# Download optimized model
# model.tflite should be in models/ directory
</code></pre>

<h3>Usage</h3>

<pre><code>python main.py --model models/yolov5s.tflite --camera 0
</code></pre>

<h2>File Structure</h2>

<pre><code>├── models/
│   └── yolov5s.tflite
├── src/
│   ├── detector.py
│   ├── pipeline.py
│   └── logger.py
├── logs/
├── clips/
├── requirements.txt
└── main.py
</code></pre>

</body>
</html>
