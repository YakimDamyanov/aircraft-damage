# Aircraft Damage Classification and Captioning

## Project Overview
This capstone project focuses on creating an automated model to **classify aircraft damage** based on visible defects. The model uses **VGG16** for feature extraction and a **Transformer-based BLIP model** for generating image captions and summaries. This project demonstrates practical applications in the aviation industry for detecting real-world aircraft damage.

## Features
- **Damage Classification:** Extracts image features with VGG16 and classifies aircraft damage.  
- **Captioning & Summarization:** Uses BLIP (Bootstrapped Language Image Pretraining) to generate meaningful captions and summaries for images.  
- **Keras Implementation:** All training and evaluation steps are implemented in Keras/TensorFlow.  

## Getting Started
### Prerequisites
- Python 3.8+
- TensorFlow 2.x
- Keras
- Pillow
- Matplotlib
- Transformers (for BLIP)

### Installation
```bash
pip install tensorflow keras pillow matplotlib transformers
