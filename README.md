# Cement Bag Detection using YOLO
This project detects and counts cement bags in a video using a custom-trained YOLO model. It can track multiple objects, draw bounding boxes, and output a processed video with the count displayed.


## Features
- Detect cement bags in videos
- Track objects across frames
- Count bags crossing a vertical line
- Save output video with bounding boxes and count
  

## Demo / Output
<img width="536" height="921" alt="Screenshot (90)" src="https://github.com/user-![Uploading Screenshot (90).png…]()
attachments/assets/b17641d4-dd50-4b4a-ad8e-2767723dedb5" />


## Requirements
- Python 3.x
- [ultralytics](https://pypi.org/project/ultralytics/)
- [opencv-python](https://pypi.org/project/opencv-python/)
- Google Colab (optional, for easy execution)


## How to Use
-Upload your video when prompted.
-Ensure your custom trained weights are in the notebook path
-Run all cells in the notebook.
-The output video will be saved as final_output.mp4 and can be downloaded automatically.


## Model Info
Model: YOLO (Ultralytics)
Custom Dataset: Cement bags
Uses tracking IDs to count objects crossing a line 
