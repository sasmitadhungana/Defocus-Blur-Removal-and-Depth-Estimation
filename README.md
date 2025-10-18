# 🖼️ Defocus Blur Removal and Depth Estimation from Stereo Images

This project focuses on estimating scene depth and removing defocus blur from stereo image pairs using **classical image processing**. It combines sharpness analysis, feature matching, and filtering techniques to reconstruct all-in-focus images and visualize depth.

---

## 🔧 Technologies Used
- Python  
- OpenCV  
- NumPy  
- Matplotlib  
- Scikit-Image  

---

## 🧩 Methodology
1. **Input:** Near-focused and far-focused images (stereo pair).  
2. **Feature Matching:** SIFT and FLANN to align stereo images.  
3. **Sharpness Estimation:** Laplacian operator to detect focused areas.  
4. **Depth Estimation:** Disparity-based depth computation.  
5. **Defocus Blur Removal:** Guided filtering and image fusion.  
6. **Evaluation:** RMSE and SSIM metrics.

---

## 📊 Results
- Generated relative depth maps visualized in color scale.  
- Reconstructed all-in-focus images using pixel fusion.  
- RMSE = 0.34 and SSIM = 0.59  

| Input Images | Depth Map | Reconstructed Image |
|---------------|------------|---------------------|
| ![Near](images/left.jpg) | ![Depth](results/depth_map.png) | ![Restored](results/result.png) |

---

📄 **Full Project Report:**  
[Click to View Project_Report.pdf](Project_Report.pdf)

---

## 👩‍💻 Author
**Sasmita Dhungana**  
Computer Engineering Student | AI & Computer Vision Enthusiast  
📍 Nepal  
🔗 [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/sasmitadhungana)
