# WarpScreenRecordingPrespective

WarpScreenRecordingPrespective is a Python tool designed to warp the perspective of a screen recording, allowing it to be superimposed onto a dynamic video background. This tool is perfect for developers, marketers, and content creators looking for a unique way to showcase their screen recordings with different perspectives.

## Features

- Automated process: Provide the screen recording and the background video.
- Utilizes powerful Python libraries for video and image processing.

## Prerequisites

- Python
- `moviepy`: For video editing tasks.
- `opencv`: For image and video processing.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Cdaprod/WarpScreenRecordingPrespective.git
   ```

2. Navigate to the project directory:
   ```bash
   cd WarpScreenRecordingPrespective
   ```

3. Install the required libraries:
   ```bash
   pip install moviepy opencv-python
   ```

## Usage

1. Place your screen recording (`screen_recording.mp4`) and background video (`background_video.mp4`) in the project directory.
2. Run the script:
   ```bash
   python warp_perspective.py
   ```

3. The output video (`output.mp4`) with the warped perspective will be generated in the project directory.

## Customization

To adjust the transformation and positioning of the screen recording on the background video, modify the `transformation_matrix` in the `warp_perspective.py` script.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues](https://github.com/Cdaprod/WarpScreenRecordingPrespective/issues) page.

## License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.