# Face Censoring Tool for Image Processing Class

## Introduction

This is a simple tool for censoring faces in images. It is written in Python and uses facenet for Face Detection, PIL for image I/O, and our own mosaic, brightening, blur function.


## How to Use

### install requirements
```shell
python -m venv venv

source venv/Scripts/activate

pip install requirements.txt
```

### Run
```shell
python sources/app.py
```
you can see that server is running on http://localhost:5000.

## Demo
### 1. First Input Image.
![image](https://github.com/easyhak/IP-final-project/assets/48908552/0fd19de8-3105-41a9-914c-940ba52a4577)

### 2. For example Input 서울의 봄 movie poster.
![image](https://github.com/easyhak/IP-final-project/assets/48908552/66241d80-046e-424d-a563-447d83853c7b)

### 3. Submit an image, it recognizes a person's face on the screen, draws a square, and gives a number.
![image](https://github.com/easyhak/IP-final-project/assets/48908552/ca1e17cf-54d3-4b92-a681-3af9f31ceb16)

### 4. Laughing at number 0 and giving blur option at number 1.
![image](https://github.com/easyhak/IP-final-project/assets/48908552/a8984ad5-bd66-4afd-bc8e-dac6acc9990d)

### 5. Result
![image](https://github.com/easyhak/IP-final-project/assets/48908552/f357f7c7-50ca-4a07-adfb-e7ef981c6c64)



## You can see front-end source code in here!

<a href="https://github.com/spearStr/Image-Processing-web">image processing web</a>



