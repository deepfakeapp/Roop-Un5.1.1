## DOWNLOAD 

# Roop-Un4.4.1 - This project has been discontinued

[Disclaimer](#Disclaimer) • [Usage](#usage) • [Google-Colab](#Google-Colab)


images and videos without training and an easy-to-use GUI.

![Screen](https://github.com/C0untFloyd/roop-unleashed/assets/131583554/6ee6860d-efbe-4337-8c62-a67598863637)


### Features

- Platform-independant Browser GUI
- Selection of multiple input/output faces in one go
- Many different swapping modes, first detected, face selections, by gender
- Batch processing of images/videos
- Masking of face occluders using text prompts or automatically
- Optional Face Upscaler/Restoration using different enhancers
- Preview swapping from different video frames
- Live FakCam using your webcam
- Extras Tab for cutting videos etc.
- Settings - storing configuration for next session
- Theme Support


### Disclaimer


This project is for technical and academic use only. Use This Code for Ai Deep learning and Ai Coding i.e just to learn How Ai Works?. Users of this software are expected to use this software responsibly while abiding the local law. If a face of a real person is being used, users are suggested to get consent from the concerned person whom real face is being used in the videos or photos and clearly mention that it is a Ai Generated photo or video and do not use this software to create deepfakes. Developers of this software will not be responsible for actions of end-users. Please do not apply it to illegal and unethical scenarios. do not use this software for illigal purpose.

**Only for Technical, Academic and Learning Purpose Use**

In the event of violation of the legal and ethical requirements of the user's country or region, this code repository is exempt from liability

### Usage

- Windows: run the `windows_run.bat` from the Installer.
- Linux: `python run.py`
- Dockerfile - `docker build -t roop-unleashed .`

### Google-Colab

<a target="_blank" href="https://colab.research.google.com/drive/1nWUy-dG9POCSjU3s-83-PHDXUB-90Zfk">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

### Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

- Steps to Contribute
- Fork the repository.
- Create a new branch for your feature or fix.
- Make your changes.
- Commit your changes with a clear message.
- Push to your forked repository.
- Create a pull request.

### Installation
Google Colab by
1. download Roop-Un4.4.1.iypnb

Local Machine ( 50 series )
0. git clone https://github.com/deepfakeapp/Roop-Un4.4.1
1. cd Roop-Un4.4.1
2. python -m venv venv && call venv/scripts/activate

pip install uv

uv pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128

uv pip install numpy

uv pip install opencv-python-headless

uv pip install onnx

uv pip install insightface

uv pip install albucore

uv pip install psutil

uv pip install onnxruntime

uv pip install onnxruntime-silicon

uv pip install onnxruntime-gpu

uv pip install tqdm

uv pip install ftfy

uv pip install regex

uv pip install pyvirtualcam

pip install --force-reinstall pydantic==2.10.6

pip install --upgrade gradio==5.13.0


Local Machine (30 / 40 Series )

0. git clone https://github.com/deepfakeapp/Roop-Un4.4.1
1. cd Roop-Un4.4.1
2. python -m venv venv && call venv/scripts/activate
3. (FOR NVIDIA) conda install -c nvidia cudatoolkit=11.8 -y
3. (FOR AMD) pip install onnxruntime-directml
4. pip install -r requirementspip install 
onnxruntime-directml.txt

5. pip install --upgrade gradio --force
6. pip install --upgrade fastapi pydantic
7. pip install "numpy<2.0" 
8. python run.py

NOTE: This installation assumes a proper installation of your system. Including python, miniconda, git, ffmpeg, VSBuildTools2019

 *A free system checker can be found here*: https://www.patreon.com/posts/automated-system-117200313

*An AI System Setup Script can be acquired here*: https://www.patreon.com/posts/117210030


### Usage

- Windows: Activate the virtual environment and run python run.py

  

