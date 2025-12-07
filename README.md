This project applies several spatial filtering techniques to reduce noise in images using **Python**, **OpenCV**, and **Jupyter Notebook**.

- `FINAL_IMAGE_DENOISING.ipynb` – Main notebook with all implementation steps.
- `imgNoise.jpg` – Noisy input image.
- `After Denoising.jpg` – Sample output after applying denoising filters.

---

##  Techniques Implemented

### 🔹 Gaussian Filter  
Smooths the image by averaging pixel values using a Gaussian kernel.

### 🔹 Median Filter  
Replaces each pixel with the median of its local neighborhood. Extremely useful for salt-and-pepper noise.

### 🔹 Bilateral Filter  
Smooths the image while preserving edges — ideal for detail-sensitive images.

### 🔹 Proposed Hybrid Filter  
A custom pipeline combining multiple filters to enhance denoising performance while maintaining edges.

---

##  Results
The notebook demonstrates visual comparisons of:
- Original noisy image  
- Gaussian filtered  
- Median filtered  
- Bilateral filtered  
- Proposed final output  

Screenshots of intermediate and final results are included in the notebook.

---

## ▶️ How to Run This Project

### 1️⃣ Install required libraries:
```bash
pip install opencv-python numpy matplotlib
