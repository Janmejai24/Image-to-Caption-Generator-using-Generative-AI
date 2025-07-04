# Image-to-Caption-Generator-using-Generative-AI
Image Captioning with BLIP: Generating Descriptions for Your Images  A simple yet powerful Python script that leverages the Salesforce BLIP model to generate descriptive captions for images. Easily integrate image understanding into your projects.
# Image Captioning with BLIP

This repository contains a straightforward Python script that demonstrates how to generate descriptive captions for images using the **BLIP (Bootstrapping Language-Image Pre-training)** model from Salesforce. BLIP is a powerful multi-modal transformer model capable of understanding both visual and textual information, making it ideal for tasks like image captioning.

## Features

* **Easy Image Captioning:** Generate concise and relevant descriptions for your images.
* **Leverages Pre-trained BLIP Model:** Utilizes the robust `Salesforce/blip-image-captioning-base` model from Hugging Face Transformers.
* **Minimal Dependencies:** Requires `requests`, `Pillow (PIL)`, and `transformers`.
* **Simple to Use:** A few lines of code to get started with image understanding.

## Getting Started

### Prerequisites

Make sure you have Python installed (Python 3.7+ is recommended).
You'll need to install the following Python libraries:

```bash
pip install torch  # PyTorch is a core dependency for transformers
pip install transformers
pip install Pillow
pip install requests # Though not strictly used in your provided code, it's common for image fetching
