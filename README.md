# 🏭 Industrial Surface Defect Detection (YOLOv8)

A Computer Vision system designed for automated Quality Control (QC) in manufacturing lines to detect steel surface defects.

## 🎯 Objective
In mass production, manual inspection is slow and error-prone. This project utilizes state-of-the-art Object Detection (**YOLOv8**) to identify and localize defects on metal surfaces in real-time.

## ⚙️ QC Logic (Automation)
The system acts as a smart inspector:
- **IF** defect is found -> Output: **REJECT** & Stop Line.
- **IF** surface is clean -> Output: **PASS**.

## 🛠️ Tech Stack
- **Framework:** Ultralytics YOLOv8.
- **Dataset:** NEU-DET (Steel Surface Defects).
- **Environment:** Google Colab (T4 GPU).

## 🚀 How to Run
1. Open the notebook in Google Colab.
2. Run the training cell (it auto-downloads the data).
3. Run the "QC Simulation" cell to see the result.

---
*By [لينا محمد هاني علي] - Mechatronics Engineer*
