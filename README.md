# AthleteRise-AI-Powered-Cricket-Analytics
Assignment: Real-Time Cover Drive Analysis from Full Video

# Setup & Run Instructions

Install dependencies:
textpip install -r requirements.txt

Run the script:
textpython cover_drive_analysis_realtime.py


The script will download the video if not present, process it, and generate:

output/annotated_video.mp4: Annotated video with pose skeleton, metrics, and feedback overlays.
output/evaluation.json: JSON file with category scores, feedback, skill grade, and smoothness metrics.
output/elbow_angle_plot.png: Plot of elbow angle over time.

# Notes on Assumptions/Limitations

Bonus features implemented: Temporal smoothness (variance & plot), Real-time performance (FPS logging), Skill grade prediction.
