# README for Billboard Advertisement Replacement Application

## Overview

The Billboard Advertisement Replacement Application is a computer vision tool that allows users to replace detected billboards in video frames with custom advertisement images. Utilizing the YOLO (You Only Look Once) model for real-time object detection, this application provides a user-friendly interface built with Tkinter for selecting images and videos.

## Features

- Detects billboards in video frames using the YOLO model.
- Overlays a selected advertisement image onto detected billboard areas.
- Simple GUI for easy user interaction.
- Real-time processing of video frames.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Ultralytics YOLO
- Tkinter (comes pre-installed with Python)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/billboard-ad-replacement.git
   cd billboard-ad-replacement
   ```

2. **Install required packages:**

   You can install the necessary Python packages using pip:

   ```bash
   pip install opencv-python numpy ultralytics
   ```

3. **Download YOLO Model:**

   Make sure you have the YOLO model file (`YOLO.pt`) in the same directory as your script. You can download it from [Ultralytics YOLO](https://github.com/ultralytics/yolov5/releases).

## Usage

1. Run the application:

   ```bash
   python app.py
   ```

2. In the GUI:
   - Click on **"Select Ad Image"** to choose an advertisement image (JPEG or PNG).
   - Click on **"Select Billboard Video"** to choose a video file (MP4 or AVI).
   - Click on **"Run Program"** to start processing the video.

3. The output window will display both the original and edited video frames side by side.

4. Press `q` to exit the video playback window.


## Future Enhancements

- Add options for saving edited videos.
- Implement additional filters or effects on the advertisement overlay.
- Enhance performance by optimizing frame processing times or incorporating multi-threading.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Ultralytics YOLO](https://github.com/ultralytics/yolov5) for providing a powerful object detection framework.
- OpenCV for its extensive computer vision capabilities.

---

