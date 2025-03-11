Here’s the complete `README.md` file for your project, including all sections, formatted properly for GitHub.  

---

```markdown
# ⚽ Football Analysis Using YOLOv5  

## Introduction  
This project focuses on detecting and tracking football players, referees, and the ball in videos using **YOLOv5**, one of the most powerful AI object detection models. We fine-tune the model to improve performance and accuracy. Additionally, we classify players into teams based on jersey colors using **K-means clustering** for pixel segmentation.  

By leveraging this data, we analyze **ball possession** percentages during a match. We utilize **optical flow** to track camera movement between frames, ensuring precise player motion analysis. **Perspective transformation** helps represent scene depth, allowing movement measurement in meters instead of pixels. Finally, we compute **player speed and total distance covered**.  

This project integrates multiple **computer vision** and **AI techniques**, making it useful for both beginners and experienced machine learning engineers.  

📌 Inspired by: [AI Sports Analytics - Football Player & Ball Tracking](https://www.youtube.com/watch?v=neBZ6huolkg)  

---

## 🚀 Features  
✔ **Player & Ball Detection** – Detects players, referees, and the ball using fine-tuned **YOLOv5**.  
✔ **Team Classification** – Uses **K-means clustering** to classify players based on jersey colors (pixel-based).  
✔ **Tracking & Motion Analysis** – Utilizes **ByteTrack** for multi-object tracking.  
✔ **Ball Possession Estimation** – Determines possession based on player proximity to the ball.  
✔ **Speed & Distance Measurement** – Calculates movement in **meters** using perspective transformation.  
✔ **Optical Flow & Perspective Calibration** – Ensures accurate tracking and position mapping.  

---

## 📊 How It Works  
1️⃣ **Object Detection**: **YOLOv5** detects players, referees, and the ball.  
2️⃣ **Team Classification**: **K-means clustering** assigns players to teams based on jersey colors.  
3️⃣ **Tracking**: **ByteTrack** maintains identity consistency over frames.  
4️⃣ **Motion & Distance Analysis**: Measures player **speed** and movement in **meters**.  
5️⃣ **Ball Possession**: Determines which team controls the ball using **proximity tracking**.  

---

## 🛠 Technical Details  
- **Model**: YOLOv5 (fine-tuned for football tracking)  
- **Tracking Algorithm**: ByteTrack  
- **Team Classification**: K-means clustering on jersey colors  
- **Distance Measurement**: Absolute (meters) using perspective transformation  
- **Input**: Pre-recorded football match videos  

---

## 📷 Model Predictions  
Here are some sample predictions from our fine-tuned YOLOv5 model:  

![players](https://github.com/user-attachments/assets/6c803cb7-4703-40d9-af14-e01904fdf512)

---

## 📈 Training Metrics  

### ✅ Validation Precision
![download (12)](https://github.com/user-attachments/assets/6e029353-0151-48f4-bbc1-f1392a9faf72)

### ✅ Validation Recall
![download (13)](https://github.com/user-attachments/assets/a62b8f82-b404-4c4c-a50e-9d26d360a1e4)

### ✅ Training and Validation Loss
![download (14)](https://github.com/user-attachments/assets/682750b0-cdc7-4b31-8239-9c189969a70b)


### ✅ Validation mAP Metrics
![download (11)](https://github.com/user-attachments/assets/25103bbd-afcf-49b5-95f2-e49baa83fd89)


### ✅ Confusion Matrix  
![confusion matrix](https://github.com/user-attachments/assets/6b4e15c5-ea3f-4419-aee5-c6ae59123fc1)


---

## 📌 Installation  

To set up the project, follow these steps:  
```
1️⃣ **Clone the repository:**  
```bash
git clone https://github.com/ahmedali610/Football_Analysis_using_YOLOv5.git
cd Football-Analysis-YOLOv5
```

2️⃣ **Install dependencies:**  
```bash
pip install -r requirements.txt
```

3️⃣ Run the analysis on a video

```bash
python main.py
```
---


