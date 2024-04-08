# Face Detection using Color-Based Approach

This project is aimed at developing an application in Python utilizing OpenCV library to detect faces based on color. The detection will be performed in the BGR color space. The primary objective is to achieve real-time detection as the video stream is captured from the camera. The images processed within the application will be of size 260x300 pixels.

## Features

- **Color-Based Face Detection**: Utilizes color thresholds to identify skin tones within the BGR color space.
- **Real-Time Detection**: Achieves near real-time face detection by processing the video stream from the camera.
- **Face Localization**: Implements techniques to locate faces within the detected skin tone regions.
- **Adjustable Thresholds**: Allows users to adjust the threshold values empirically to suit different lighting conditions.
- **Robustness**: The application aims to be robust against variations in lighting and skin tones.

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/face-detection.git
    ```

2. Navigate to the project directory:

    ```bash
    cd face-detection
    ```

3. Ensure you have Python installed. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:

    ```bash
    python face_detection.py
    ```

## Customization

- **Threshold Adjustment**: Modify the threshold values in the `face_detection.py` file to adapt to different lighting conditions.
- **Region of Interest Size**: Change the size of the bounding box used for face localization as needed.

## Acknowledgments

- This project is inspired by the work in computer vision and face detection.
- Thanks to the OpenCV library for providing powerful tools for image processing and computer vision tasks.

