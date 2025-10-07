# Architecture Overview

## System Overview
The AI Family Robot consists of:
1. **Jetson-based edge system** for local inference.
2. **Python backend (FastAPI)** for control logic and communication.
3. **ML models** for speech, vision, and emotion detection.
4. **Optional cloud services** for MLOps and data storage.
5. **Dashboard or app interface** for user monitoring and control.

## Planned Technologies
- Jetson Nano / Orin
- FastAPI
- PyTorch
- OpenCV
- Hugging Face Transformers
- AWS SageMaker (optional)
