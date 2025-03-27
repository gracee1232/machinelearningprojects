# Eye Tracking with OpenCV & MediaPipe
A Python-based eye-tracking system that uses OpenCV, MediaPipe, and PyAutoGUI to track eye movements and potentially control the mouse cursor.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
This project utilizes a webcam feed to track facial landmarks, specifically focusing on eye movements. Using MediaPipe's FaceMesh model, it detects and processes eye movement data in real-time. The script can potentially be used for hands-free cursor control or accessibility applications.

## Features
- Real-time face and eye tracking using MediaPipe.
- Webcam-based tracking with OpenCV.
- Cursor control with PyAutoGUI based on eye movement.
- Hands-free navigation potential.

## Installation
### Prerequisites
Ensure you have Python installed. Then, install the required dependencies:
```sh
pip install opencv-python mediapipe pyautogui
```

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/eye-tracking.git
   ```
2. Navigate to the project directory:
   ```sh
   cd eye-tracking
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
To start the eye-tracking system, run:
```sh
python eye.py
```
Make sure your webcam is connected and functioning properly. The script will track eye movements and may control the cursor accordingly.

## Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
Specify the license under which the project is distributed.

## Contact
For inquiries, reach out via GitHub or LinkedIn.

