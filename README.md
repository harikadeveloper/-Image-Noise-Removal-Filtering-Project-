# 🧹 Image Noise Removal using Filters

## 📝 Project Overview
This project demonstrates how to remove noise from images using image processing techniques in Python with OpenCV.

## 🎯 Objective
To denoise a noisy image using:
- Gaussian Blur
- Median Filter
- Bilateral Filter

## 🛠️ Technologies Used
- Python
- OpenCV (cv2)
- NumPy
- Matplotlib (for visualization)
- Jupyter Notebook

## 📂 Dataset
A noisy image is manually added for testing. You can replace it with your own image inside the `project/` folder.

## 📸 Output Comparisons
| Original Image | Gaussian Blur | Median Filter | Bilateral Filter |
|----------------|----------------|----------------|------------------|
| *(Upload image)* | *(Upload image)* | *(Upload image)* | *(Upload image)* |

## 🔍 Filter Descriptions
**Gaussian Blur**  
Smooths the image using a Gaussian kernel to reduce noise and detail.

**Median Filter**  
Replaces each pixel's value with the median of its neighborhood. Great for removing salt-and-pepper noise.

**Bilateral Filter**  
Preserves edges while reducing noise, making it suitable for detailed image tasks like facial image enhancement.

## 🚀 How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/ImageNoiseRemoval
    cd ImageNoiseRemoval
    ```

2. Install the required packages:
    ```bash
    pip install opencv-python numpy matplotlib
    ```

3. Open the Jupyter Notebook file and run all cells:
    ```bash
    jupyter notebook ImageNoiseRemoval.ipynb
    ```

## 💡 Applications
- Pre-processing in computer vision pipelines
- Medical imaging
- Surveillance and security
- Photography apps

## 📫 Contact
For questions or feedback, please reach out on [LinkedIn](#) or open an issue.

