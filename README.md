## DOWNLOAD 

# Roop-Un5.1.1 - This project has been discontinued

[Disclaimer](#Disclaimer) • [Terms](#Terms) • [Usage](#usage) • [Google-Colab](#Google-Colab)


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
- Live Fake Cam using your webcam
- Extras Tab for cutting videos etc.
- Settings - storing configuration for next session
- Theme Support


### Disclaimer


This project is for technical and academic use only. Use This Code for Ai Deep learning and Ai Coding i.e just to learn How Ai Works?. Users of this software are expected to use this software responsibly while abiding the local law. If a face of a real person is being used, users are suggested to get consent from the concerned person whom real face is being used in the videos or photos and clearly mention that it is a Ai Generated photo or video and do not use this software to create deepfakes. Use of this tool to create non-consensual, defamatory, political, celebrity, or pornographic content is strictly prohibited and illegal under local or international laws. The developers are not responsible for misuse. Developers of this software will not be responsible for actions of end-users. Please do not apply it to illegal and unethical scenarios. do not use this software for illigal purpose.

**This Tool is intended for Technical, Academic, Educational, Ethical, Research and Learning Purpose Use only.**

In the event of violation of the legal and ethical requirements of the user's country or region, this code repository is exempt from liability.


### Terms

By using this tool, you acknowledge and agree to the following:
    
You have obtained explicit, informed consent from any individuals depicted in any media you upload.
You will not use this tool to create or distribute content that is:

1. Non-consensual
2. Sexually explicit or pornographic
3. Defamatory, harassing, or invasive of privacy
4. Politically manipulative or misleading
5. Impersonating public figures or private individuals

You are solely responsible for all content you generate or distribute using this tool.
The developers, maintainers, and providers of this application do not assume any liability for misuse or consequences arising from content generated using this tool.
Misuse of AI-generated media may violate local, national, or international laws. You are responsible for complying with all applicable regulations in your jurisdiction. Violators may face civil or criminal penalties.

This software must NOT be used from or within countries with strict regulations on synthetic or manipulated media, including but not limited to:

- 🇺🇸 United States
- 🇬🇧 United Kingdom
- 🇮🇳 India
- 🇦🇪 United Arab Emirates
- 🇨🇳 China
- 🇰🇷 South Korea
- 🇦🇺 Australia
- 🇩🇪 Germany
- 🇫🇷 France
- 🇸🇬 Singapore
- 🇯🇵 Japan
- 🇨🇦 Canada

IF YOU DO NOT FULLY AGREE WITH THESE TERMS, DO NOT USE THIS AI TOOL & APP.
  
### Usage

- Windows: run the `windows_run.bat` from the Installer.
- Linux: `python run.py`


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
1. download Roop-Un5.1.1.iypnb

Local Machine ( 50 series )
0. git clone https://github.com/deepfakeapp/Roop-Un5.1.1
1. cd Roop-Un5.1.1
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

0. git clone https://github.com/deepfakeapp/Roop-Un5.1.1
1. cd Roop-Un5.1.1
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



### Usage

- Windows: Activate the virtual environment and run python run.py

  

