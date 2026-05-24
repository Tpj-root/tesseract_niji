---

## 🧠 Tesseract Niji — Tamil Handwriting OCR Model

**Tesseract Niji** is a custom OCR training project focused on recognizing **Tamil handwritten text**, specifically trained on real-world notes written by my brother. The goal is to bridge the gap between personal handwriting styles and accurate digital text extraction using Tesseract OCR.

### 🚀 Project Overview

Most OCR systems perform well on printed text but struggle with **handwritten Tamil scripts**, especially when the writing style is unique or informal. This project builds a **custom-trained model** using the Tesseract training pipeline to accurately recognize such handwriting.

### 🎯 Objectives

* Convert handwritten Tamil notes into editable digital text
* Train a personalized OCR model for a specific handwriting style
* Explore preprocessing techniques (thresholding, binarization, etc.)
* Improve accuracy through iterative training and dataset refinement

### 📂 Dataset Structure

The training dataset follows the standard Tesseract format:

```
tesstrain/data/my_handwriting-ground-truth/
├── note_001.png
├── note_001.gt.txt
├── note_002.png
└── note_002.gt.txt
```

* Each image contains a **single line of handwritten Tamil text**
* Corresponding `.gt.txt` file contains the **ground truth transcription**

### 🛠️ Tech Stack

* Tesseract OCR (LSTM training)
* Leptonica (image preprocessing)
* Bash / Python scripts for automation
* Image preprocessing (threshold variations, noise removal)

### 🔍 Key Features

* Custom Tamil handwriting recognition
* Dataset tailored for real handwritten notes
* Support for experimenting with multiple preprocessing techniques
* Modular training pipeline for easy improvements

### 🧪 Approach

1. Collect handwritten samples (line-by-line images)
2. Generate accurate ground truth text files
3. Apply preprocessing (thresholding, binarization)
4. Train using Tesseract LSTM engine
5. Evaluate and refine the model iteratively

### 📈 Future Improvements

* Expand dataset with multiple handwriting styles
* Add support for full-page OCR (not just line-level)
* Improve segmentation and layout detection
* Build a simple UI for uploading and recognizing notes

### 🤝 Contribution

Contributions are welcome! You can help by:

* Adding more Tamil handwriting samples
* Improving preprocessing scripts
* Enhancing model accuracy

---



