# Installation of Open-CV in Windows
## Introduction
This guide walks you through the installation of OpenCV in Windows using Anaconda. OpenCV is an open-source computer vision and machine learning software library. Anaconda is a popular distribution platform that simplifies Python package management and deployment.
## Steps to Install OpenCV
### Step 1: Install Anaconda

1)What is Anaconda? Anaconda is a distribution of Python and R programming languages used for scientific computing, data science, and machine learning. It provides package management and virtual environment capabilities.

2)Open the [official Anaconda website](https://www.anaconda.com/).

3)On the top right corner, click Free Download.

4)Provide your email address when prompted and click Submit.

5)You will receive an email with a link to download the installation file. Click the link to download the file.

### Step 2: Install Anaconda

1)Locate the downloaded file and double-click it to start the installation.

2)Follow the installation instructions provided in the setup.

3)During the Advanced Installation Options, make sure to check the box "Add Anaconda3 to my PATH environment variable".

### Step 3: Create a Virtual Environment for OpenCV
1)Open Command Prompt.

2)Create a new virtual environment by typing:
```bash
conda create --name opencv-env
```

3)Press y when prompted and hit Enter.

4)Activate the virtual environment by typing:
```bash
conda activate opencv-env
```
### Step 4: Install OpenCV

1)Install OpenCV in your virtual environment by typing:

```bash
conda install -c conda-forge opencv
```

2)Press y when prompted and hit Enter.

### Step 5: Verify OpenCV Installation

1)Open Python within your virtual environment by typing:

```bash
python
```

2)Import OpenCV and check its version:

```bash
import cv2 as cv
print(cv.__version__)
```

3)If a version number is displayed, the installation was successful.

4)Exit Python by typing:

```bash
exit()
```













