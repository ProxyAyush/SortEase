![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) 
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)
![Freelancer](https://img.shields.io/badge/Freelancer-29B2FE?style=for-the-badge&logo=Freelancer&logoColor=white)

<br>

[![DOI](https://zenodo.org/badge/691037981.svg)](https://zenodo.org/badge/latestdoi/691037981)

# SortEase
WHERE BIOMEDICAL WASTE FINDS ITS PLACE​

This Model is based on Yolov8s and trained using a custom image dataset from King George's Medical University's Biomedical Waste Facility, Data of Biomedical Waste was collected with all necessary permissions from University Environment Department, and was taken in controlled manner with appropriate protection.<br>

This is not production Quality AI Model, rather a proof of concept and It can detect Sharps which unfortunately come in Red Dustbins in Hospitals.<br> 7 types of sharps it detects are "Blades-Sharp-", "Cannula_with_Cap -Sharp-", "Glass -Sharp-", "Instrument-Sharp-", "Needle -Sharp-", "Needle_with_Cap -Sharp-", "Syringes -Alert-". <br>One can use this for their testing on their PC, the following instructions guide you how to do that.

# Download and Install Vscode(Visual Studio)

Download Link- https://code.visualstudio.com/download
<br>
  Meanwhile Vscode is downloading, create an empty folder on your Desktop with any name you want. <br>
  Install Vscode after it downloads<br>
  After installing Vscode, Run it.<br>
  You'll see a 'Open Folder' option, select the empty folder you just created and Open it<br>
  <br>
  Also install the python interpreter in vscode, on how to do that see this
  <br>  https://code.visualstudio.com/docs/python/python-tutorial
# Download Model and Inference file
Download the best.pt file <br>
Download the liveinference.py<br>
and place both these files in the empty folder you made earlier.

# Installation of Libraries

We open the liveinference.py in Vscode(it shows in the folder panel), and on the upper right corner click the terminal button to open the terminal with code in Vscode
<br>
We install the Ultralytics Library in the terminal
```
py -m pip install ultralytics
```
then we will install the opencv library

```
py -m pip install opencv-python
```

# Specifying the path in Inference file
In the Liveinference.py file opened in Vscode, check the model path in line number 10, change it to the path of best.pt file which you placed in your folder.
```
model = YOLO("YOUR PATH TO best.pt")
```

*there is already a path in liveinference.py, make sure to copy your path in the same way, or it'll give UNICODE escape error.

# Running the Program
On the upper right side of Vscode there is a play button, click it and it will run the program with formation of a Webcam window.
<br>
Make sure you have Webcam enabled in your settings.

<br>

These are the training graphs of model:

![download](https://github.com/ProxyAyush/SortEase/assets/65772478/d5d32aaf-f1e9-474a-9ab3-8f1ec5b242ab)


# Follow My Work on Linkedin 
![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)
<br>
https://www.linkedin.com/in/ayush-yadav-kgmu/?originalSubdomain=in
<br>
<br>

This project was made using the below resources: <br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) 
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Windows 11](https://img.shields.io/badge/Windows%2011-%230079d5.svg?style=for-the-badge&logo=Windows%2011&logoColor=white)
![Freelancer](https://img.shields.io/badge/Freelancer-29B2FE?style=for-the-badge&logo=Freelancer&logoColor=white)

