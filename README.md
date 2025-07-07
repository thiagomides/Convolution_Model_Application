# 🧠 Convolution Model - Application

This project implements the forward and backward passes of a Convolutional Neural Network (CNN) **from scratch using NumPy**. It is based on an assignment from the Deep Learning Specialization by Andrew Ng (Coursera - Week 1 of the Convolutional Neural Networks course).

---

## 🚀 Project Overview

- **Binary Classification Task (TensorFlow):**  
  Build and train a ConvNet that classifies images of people's faces to determine if they are smiling or not. Only smiling people get to enter the house!

- **Multiclass Classification Task (TensorFlow):**  
  Build and train a ConvNet to differentiate between 6 sign language digits.

---

## 📌 Highlights

- Manual implementation of CNN components:
  - Zero-padding
  - Convolution (single and multi-channel)
  - Pooling (max and average)
  - Forward and backward propagation
- Uses helper functions from `cnn_utils.py` and `test_utils.py`
- Processes real image data from the `datasets/` folder
- Visual outputs stored in `images/`

---

## 📓 Notebook Contents

The notebook (`Convolution_model_Application.ipynb`) guides you through:

1. **Zero Padding**  
   Implementing padding manually and verifying output shapes.

2. **Single Convolution Step**  
   Applying a filter to a small region of input data.

3. **Full Convolution Forward Pass**  
   Convolving across the height and width of the input.

4. **Pooling Layer**  
   Performing max or average pooling.

5. **Full Forward Pass**  
   Assembling convolution and pooling layers into a full model.

6. **Backward Propagation**  
   Deriving gradients of convolution and pooling operations.

---

## 📁 Project Structure

```

Convolution\_model\_Application/
├── Convolution\_model\_Application.ipynb     # Main notebook
├── cnn\_utils.py                            # CNN helper functions (initialization, activation, reshaping)
├── test\_utils.py                           # Test functions for validating layers
├── datasets/                               # Input dataset (images in .h5 or .jpg format)
├── images/                                 # Output visualizations
└── README.md                               # Project documentation

````

---

## 🧑‍💻 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Convolution_model_Application.git
cd Convolution_model_Application
````

### 2. Install dependencies

This project only requires basic scientific Python libraries:

```bash
pip install numpy h5py matplotlib notebook
```

### 3. Launch the notebook

```bash
jupyter notebook Convolution_model_Application.ipynb
```

---

## 🎯 Requirements

* Python 3.6+
* NumPy
* h5py
* Matplotlib
* Jupyter Notebook

---

## 🧠 Educational Value

This project is focused on learning and implementing the core ideas of CNNs using **no deep learning frameworks**. Ideal for:

* Students in machine learning courses
* Learners who want to understand CNN internals
* Anyone preparing for deep learning interviews or exams

---

## 📚 Reference

This work is based on the assignment:

* [Convolution model - Application - v1.ipynb](https://www.coursera.org/learn/convolutional-neural-networks/programming/7Bfm2/convolution-model-application)
* From Andrew Ng's Deep Learning Specialization (Coursera)

---

