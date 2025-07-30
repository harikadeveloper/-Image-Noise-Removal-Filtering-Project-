🖼️ Image Noise Removal using Filters
This project demonstrates how to remove noise from images using traditional image filtering techniques in Python. Various filters such as Gaussian Blur, Median Filter, and Bilateral Filter are applied to denoise an image and visually compare their effectiveness.

🔍 Objective
To understand and implement different image denoising filters and compare how well they remove noise from a given image.

🛠️ Technologies Used
Python 🐍

OpenCV (cv2)

NumPy

Matplotlib (for visualization)

Jupyter Notebook

📂 Dataset
This project uses a manually added noisy image.
You can download the sample image from this link:
👉 Download noisy image here
(or use your own image by placing it in the project directory)

📈 Results
Original Image	Gaussian Filter	Median Filter	Bilateral Filter

📌 Replace the image links after uploading your outputs/ folder to GitHub.

🧪 Filters Overview
Gaussian Blur: Reduces image noise and detail using a Gaussian function.

Median Filter: Replaces each pixel with the median value of the neighboring pixels; effective against salt-and-pepper noise.

Bilateral Filter: Removes noise while preserving edges — useful in facial or object-based image smoothing.

📝 How to Run
Clone the repository

Install required libraries using:

bash
Copy
Edit
pip install opencv-python numpy matplotlib
Run the ImageNoiseRemoval.ipynb notebook in Jupyter or VS Code

View results in the outputs/ folder

💡 Use Cases
Pre-processing step in Computer Vision tasks

Noise reduction in medical imaging

Enhancing image quality in surveillance and remote sensing

📚 Learning Outcome
By doing this project, you’ll learn:

How various filters work for noise removal

Visual difference in filtered outputs

When to use which filter depending on noise type

