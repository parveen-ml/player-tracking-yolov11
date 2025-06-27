# 🧠 Player Tracking and Re-identification using YOLOv11

This project focuses on tracking and re-identifying football players in a video using a fine-tuned **YOLOv11** model. It ensures that players who leave and re-enter the frame retain consistent identities.

---

## 📁 Files Required

- [`best.pt`](https://drive.google.com/file/d/1YABlQYon_EkCw10Sl08BfpBO4YUr_FZj/view?usp=drive_link): Fine-tuned YOLOv11 model (Google Drive)
- `15sec_input_720p.mp4`: Input video file
- `player_tracking.ipynb`: Jupyter Notebook for running the model
- `requirements.txt`: List of Python dependencies

---

## ⚙️ Environment Setup

```bash
# Create a virtual environment
python -m venv venv

# Activate the environment
source venv/bin/activate      # For macOS/Linux
venv\Scripts\activate         # For Windows

# Install dependencies
pip install -r requirements.txt
```
