# 🛏️ Real-Time Hospital Bed Monitoring System using YOLOv4

## 📌 Objective
To detect and monitor hospital bed occupancy in real-time using YOLOv4, OpenCV, and Python. Beds are identified frame-by-frame in a hospital ward video to support efficient healthcare resource tracking.

---

## 📂 Project Files

| File                          | Description                                      |
|-------------------------------|--------------------------------------------------|
| `Real_Time_Hospital_Bed_Monitoring_.ipynb` | Main Jupyter Notebook used in Google Colab |
| `output_detected.mp4`         | Output video with bounding boxes for beds       |
| `bed_detection_log.txt`       | Frame-by-frame detection log                    |
| `bed_occupancy_report.csv`    | CSV summary of bed occupancy per frame          |

---

## 🧠 Technologies Used

- Python
- OpenCV
- YOLOv4 (via Darknet)
- Google Colab

---

## 🧪 How It Works

1. The input video (`ward.mp4`) is processed frame-by-frame.
2. YOLOv4 is used to detect beds (represented by the 'chair' class).
3. Bounding boxes are drawn for detected beds in each frame.
4. Occupancy data is logged in `bed_detection_log.txt`.
5. Frame-wise summary is saved in `bed_occupancy_report.csv`.
6. Annotated video is saved as `output_detected.mp4`.

---

## 📊 Sample Output

📋 Log Analysis Report
🔢 Total Frames Detected: 254
🛏️ Bed Occupancy Per Frame (showing first 5):
Frame 0: 0 bed(s)
Frame 1: 1 bed(s)
Frame 2: 1 bed(s)
Frame 3: 1 bed(s)
Frame 4: 1 bed(s)
