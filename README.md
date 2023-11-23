# ImageAI Computer Vision Flask Apps

```markdown
[![GitHub](https://badgen.net/badge/icon/GitHub?icon=github&color=black&label)](https://github.com/MaxineXiong)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Python](https://img.shields.io/badge/Python->=3.6-blue?logo=python&logoColor=white)](https://www.python.org)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://www.css3.com/)
[![ImageAI](https://img.shields.io/badge/ImageAI-5C3EE8?logo=OpenCV)](https://github.com/OlafenwaMoses/ImageAI)

# ImageAI Computer Vision Flask Apps

## Project Description

This project consists of two Flask applications that leverage ImageAI's image prediction algorithms and object detection models for object recognition and analysis in images and videos. The apps, Image Object Recognition Flask Application and Video Object Detection Flask Application, provide an intuitive platform for users to explore, analyze, and extract information from visual content.

## Features

- **Image Object Recognition Flask Application:**
  - Upload and predict objects in images.
  - Display predicted objects with confidence scores.

- **Video Object Detection Flask Application:**
  - Upload and detect objects in a video.
  - Generate a raw dataset of detected objects in CSV format (downloadable).
  - Generate an output video with detected objects highlighted (downloadable).
  - Perform data analysis on detected objects, including:
    - Average number of unique objects per frame.
    - Average number of unique objects per second (conditions apply).
    - Average number of unique objects per minute (conditions apply).
    - Average number of unique objects per hour (conditions apply).
    - Total number of unique objects in the entire video.

## Repository Structure

```
ImageAI-Flask-Apps/
├── ImageAI-web-app.py
├── image_recognizer.py
├── video_object_detector.py
├── templates/
│   ├── index.html
│   ├── image-prediction.html
│   └── video-object-detection.html
├── static/
│   ├── main.css
│   ├── images/
│   │   ├── demo-image-recognizer.gif
│   │   ├── demo-video-object-detector.gif
│   │   └── web-icon.ico
├── models/
│   ├── image-prediction-models/
│   └── video-object-detection-models/
├── files_for_testing/
├── requirements.txt
├── README.md
└── LICENSE
```

## Usage

### Prerequisites

- Python 3.x
- Machine learning libraries (specified in requirements.txt)
- Jupyter Notebook (optional, for running example notebooks)

1. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Download ImageAI models as per instructions in the README of the 'models' folder.

3. Run the Flask apps:

    ```bash
    python ImageAI-web-app.py
    ```

4. Access the apps at [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your web browser.

## Contribution

Contributions are welcome. If you encounter issues or have suggestions, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```



## Acknowledgement

I would like to thank the [**creator of ImageAI**](https://github.com/OlafenwaMoses) for providing the image prediction and object detection algorithms used in this project. His contributions have been instrumental in the development of these Flask applications. To delve deeper into the computer vision algorithms and models developed by [**ImageAI**](https://github.com/OlafenwaMoses/ImageAI), I encourage you to visit the [**ImageAI GitHub Page**](https://github.com/OlafenwaMoses/ImageAI) or explore its [**official documentation**](https://imageai.readthedocs.io/en/latest/).
