# Player Tracking and Re-identification using YOLOv11

This project tracks and re-identifies players in a football video using a fine-tuned YOLOv11 model. It ensures players who leave and re-enter the frame are assigned consistent identities.

## 📁 Files Required

- [`best.pt`](https://drive.google.com/file/d/1YABlQYon_EkCw10Sl08BfpBO4YUr_FZj/view?usp=drive_link): YOLOv11 model (stored on Google Drive)
- `15sec_input_720p.mp4`: Input video
- `player_tracking.ipynb`: Jupyter notebook file
- `requirements.txt`: Dependency list

## ⚙️ Set Up Environment

python -m venv venv
source venv/bin/activate # On Windows: venv\\Scripts\\activate
pip install -r requirements.txt

📓 Run Notebook
Open player_tracking_yolo11.ipynb using VS Code or Jupyter Lab.

Run all cells to process video and see player tracking output.
