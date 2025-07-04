#  Cats vs Dogs Image Classification using CNN (Keras + TensorFlow)

##  Project Overview
This is a deep learning project that uses Convolutional Neural Networks (CNN) to classify images of **cats** and **dogs**. The model is built using **TensorFlow** and **Keras** and trained on augmented image data.

Developed under the guidance of **PrepInsta**, this project is a real-world application of computer vision that’s easy to understand and perfect for interview discussion.

---

##  How to Run the Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/dibyajitray/cats-vs-dogs-classifier.git
   cd cats-vs-dogs-classifier
   ```

2. **Install dependencies:**
   ```bash
   pip install tensorflow keras matplotlib numpy pillow
   ```

3. **Project Structure:**
   ```
   ├── datasets
   │   ├── dogs_cats
   │       ├── training_set
   │       └── test_set
   ├── cats_dogs_classifier.ipynb
   └── README.md
   ```

4. **Run the notebook:**
   Open the notebook file `cats_dogs_classifier.ipynb` using **Jupyter Notebook**, **Google Colab**, or any Python IDE to train and test the model.

---

##  Sample Image Prediction Output

```python
test_image = image.load_img('datasets/dogs_cats/test_set/dog/dog001.jpg', target_size=(64, 64))
```
 **Model Prediction: Dog**

The model predicts with good accuracy whether the input image is of a **cat** or a **dog** using a trained CNN.


---

## 🙋 Contact Info

**👨‍💻 Dibyajit Ray**  
📧 Email: raydibyo7@gmail.com  
🌐 GitHub: [https://github.com/dibyajitray](https://github.com/dibyajitray)  
🔗 LinkedIn: [https://linkedin.com/in/dibyajit-ray](https://linkedin.com/in/dibyajit-ray)

