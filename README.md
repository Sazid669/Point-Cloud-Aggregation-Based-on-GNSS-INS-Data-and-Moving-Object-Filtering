
# 📌 Point Cloud Aggregation Based on GNSS-INS Data and Moving Object Filtering

This project demonstrates a method for aggregating point cloud data using GNSS-INS sensor fusion, while filtering out moving objects to improve mapping accuracy in dynamic environments.

---

## 📽️ Video Demonstration

👉 **[Watch the video demonstration](https://youtu.be/KxMVg1peoWc?si=NlbP4rB2Nu9TuvDi)**

---

## 📘 Project Overview

- **Objective**: Aggregate 3D point clouds accurately over time using GNSS-INS data while removing transient moving objects such as vehicles and pedestrians.
- **Motivation**: Point clouds generated in urban environments often suffer from noise and misalignments caused by dynamic obstacles. This project tackles the problem using sensor fusion and object filtering techniques.

---

## 🧠 Key Components

1. **GNSS-INS Data Fusion**  
   - Used for estimating the position and orientation of the LiDAR sensor.
   - Enables accurate alignment of point cloud frames across time.

2. **Point Cloud Accumulation**  
   - Multiple point clouds are transformed into a global frame using GNSS-INS poses.

3. **Moving Object Filtering**  
   - Dynamic objects (cars, people, etc.) are detected and removed to retain only the static map.
   - Improves the quality of maps for SLAM, localization, and 3D reconstruction.

---

## 📂 Files

- `Sazid_code_and_document.ipynb`: Contains full implementation and English explanation of the methodology.
- `Video_and_documentation_link.pdf`: Quick link to the video and documentation reference.

---

## 🛠️ Tools & Libraries

- Python
- NumPy
- Open3D
- Pandas
- Matplotlib
- Jupyter Notebook

---

> ⭐️ Found this helpful? Star the repo or share with your peers!
