# 📷 Camera Calibration using OpenCV

This project demonstrates camera calibration using computer vision techniques, primarily leveraging OpenCV. Calibration is essential for correcting lens distortions and accurately mapping real-world points to image coordinates, improving the precision of computer vision systems.

---

## 🎯 Project Objectives

- Estimate intrinsic and extrinsic parameters of the camera
- Compute distortion coefficients (radial and tangential)
- Visualize and correct distortion in images
- Understand the pinhole camera model and calibration matrix
- Practice using OpenCV calibration methods and checkerboard patterns

---

## 🔧 Technical Background

### 🔍 Why Camera Calibration?

Real-world lenses introduce distortions—especially radial distortion (e.g., fisheye effect)—which must be corrected to ensure accurate visual analysis. Calibration determines the transformation between 3D world coordinates and 2D image coordinates, critical for tasks like 3D reconstruction, AR, or robotics.

### 📌 Key Parameters

**Intrinsic Parameters**
- Focal length `f`
- Principal point `(cx, cy)`
- Distortion coefficients: `k1, k2, p1, p2, k3`

**Extrinsic Parameters**
- Rotation matrix (R)
- Translation vector (T)

**Camera Matrix**  
Derived using the pinhole model:
