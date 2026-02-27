# edge-ai-onnx
MobileNetV2 ONNX INT8 model for edge inference benchmarking
# Edge AI ONNX Model

## Framework
ONNX Runtime Mobile

## Model
MobileNetV2

## Quantization
Static INT8

## Calibration
50 shared calibration images

## Author
Shankari Sharath Kumar
## Setup (WSL / Linux)

```bash
git clone https://github.com/shankari1012-art/edge-ai-onnx.git
cd edge-ai-onnx

python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
