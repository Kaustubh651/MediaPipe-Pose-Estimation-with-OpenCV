**MediaPipe Pose Estimation with OpenCV**

![MediaPipe Pose Estimation](https://github.com/your-username/mediapipe-pose-estimation/blob/main/assets/mediapipe-pose-estimation.png)

**Description:**
This repository contains Python scripts demonstrating pose estimation using MediaPipe and OpenCV. It provides functionality for processing static images as well as live webcam input, annotating detected poses in real-time.

**Features:**
- Process static images for pose estimation.
- Perform real-time pose estimation using webcam input.
- Annotate detected poses on images or video streams.
- Easy-to-use scripts with minimal setup.

**Installation:**
1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/mediapipe-pose-estimation.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

**Usage:**
1. **Static Image Pose Estimation:**
   - Modify the `IMAGE_FILES` list in `static_image_pose_estimation.py` to specify the paths of the images you want to process.
   - Run the script:

```bash
python static_image_pose_estimation.py
```

2. **Webcam Pose Estimation:**
   - Run the script:

```bash
python webcam_pose_estimation.py
```

**File Structure:**
- `static_image_pose_estimation.py`: Python script for processing static images.
- `webcam_pose_estimation.py`: Python script for real-time pose estimation using webcam input.
- `requirements.txt`: File containing required Python packages.
- `assets/`: Directory containing images and other assets.

**Contributing:**
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a new Pull Request.

**Credits:**
- This project utilizes the MediaPipe library for pose estimation.
- OpenCV is used for image processing and webcam input.

**License:**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Contact:**
For any inquiries or suggestions, please contact [your-email@example.com](mailto:your-email@example.com).

Feel free to contribute, report issues, or provide feedback. Thank you for using MediaPipe Pose Estimation with OpenCV!
