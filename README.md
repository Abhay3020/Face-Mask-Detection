# Face Mask Detection

This project implements a face mask detection system using deep learning techniques. It can detect whether a person in an image or video is wearing a face mask or not.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
  - [Detecting Masks in Images](#detecting-masks-in-images)
  - [Detecting Masks in Videos](#detecting-masks-in-videos)
- [Files](#files)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Abhay3020/Face-Mask-Detection.git
   cd Face-Mask-Detection
   ```

2. **Install the required dependencies:**

   Ensure you have Python installed. Then, install the necessary packages:

   ```bash
   pip install -r requirements.txt
   ```

   *Note: The `requirements.txt` file should list all the dependencies needed to run the project.*

## Usage

### Detecting Masks in Images

To detect face masks in images, use the `detect_mask_image_V3.py` script:

```bash
python detect_mask_image_V3.py --image path/to/your/image.jpg
```

Replace `path/to/your/image.jpg` with the path to the image you want to analyze.

### Detecting Masks in Videos

To detect face masks in videos or real-time webcam feed, use the `detect_mask_video_V3.py` script:

```bash
python detect_mask_video_V3.py --video path/to/your/video.mp4
```

Replace `path/to/your/video.mp4` with the path to your video file. If you want to use your webcam, omit the `--video` argument:

```bash
python detect_mask_video_V3.py
```

## Files

- `Mask_Detection.ipynb`: Jupyter Notebook containing the development and training process of the face mask detection model.
- `detect_mask_image_V3.py`: Script to detect face masks in static images.
- `detect_mask_video_V3.py`: Script to detect face masks in video files or webcam feed.
- `A2_mp_report.doc`: Project report detailing the methodology and results.
- `New Text Document.txt`: Placeholder text document (contents unspecified).

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.
