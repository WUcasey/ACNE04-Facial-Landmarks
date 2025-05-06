# ACNE04-Facial-Landmarks

**Facial landmark annotations for ACNE04 dataset**
---

## 📂 Dataset Description

This repository contains **facial landmark annotations** and **facial mask** for facial images in the **ACNE04** dataset.  
The dataset was created to support **facial skin analysis**, and **medical image segmentation** tasks.

> ⚠️ **Note**: The original ACNE04 images are **not included** in this repository due to licensing restrictions.  
Please refer to the [original ACNE04 dataset paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Wu_Joint_Acne_Image_Grading_and_Counting_via_Label_Distribution_Learning_ICCV_2019_paper.html) and request access from the authors if needed.

### 📑 Label Categories

The annotations include the following facial components:

| Label     | Description             |
|-----------|-------------------------|
| `eye`     | Left and right eyes     |
| `lips`    | Upper and lower lips    |
| `eyebrow` | Left and right eyebrows |
| `glasses` | Eyeglasses (if present) |
| `logo`    | Brand logos (if visible on face) |
| `nostril` | Left and right nostrils |



## ⚙️ Usage

git clone https://github.com/YOUR_USERNAME/ACNE04-Facial-Landmarks.git
cd ACNE04-Facial-Landmarks

## 📖 Citation
@misc{acne04_facial_landmarks,
  author = {An-Chieh Wu},
  title = {Facial landmark annotations for ACNE04 dataset},
  year = {2025},
  publisher = {GitHub},
  howpublished = {\url{https://github.com/WUcasey/ACNE04-Facial-Landmarks}}
}

## 🙏 Acknowledgements

This project builds upon the **ACNE04 dataset**, originally created and published by:

> Wu, Xiaoping, Wen, Ni, Liang, Jie, Lai, Yu-Kun, She, Dongyu, Cheng, Ming-Ming, and Yang, Jufeng.  
> *Joint Acne Image Grading and Counting via Label Distribution Learning*.  
> In Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV), 2019, pp. 10642–10651.  
> [[Paper link](https://openaccess.thecvf.com/content_ICCV_2019/html/Wu_Joint_Acne_Image_Grading_and_Counting_via_Label_Distribution_Learning_ICCV_2019_paper.html)]  
> [[Original code repository](https://github.com/xpwu95/ldl)]

We acknowledge and thank the authors for making the ACNE04 dataset and source code publicly available, which enabled further research and annotation efforts in this repository.
