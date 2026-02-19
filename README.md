# 책 부록 소스 프로젝트 입니다

- 직무 교육( OJT, On the job Training )을 위해서 생성.  
- 진행중( WIP, Work on Progress ).  
  + ...


## 책 관련 링크  

<img src="https://content.packt.com/_/image/original/B09431/cover_image.jpg" alt="" height="256px" align="right">


- [Tkinter GUI Application Development Blueprints, Second Edition [ 원서 ]](https://www.packtpub.com/en-us/product/tkinter-gui-application-development-blueprints-second-edition-9781788834452)  


- [Tkinter GUI Application Development Blueprints, Second Edition [ 번역서, 없음 ]](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=139236068)  


## 개발 환경 구축

- 파이썬 ( Python 3.12 )  

  - [Python Download](https://www.python.org/downloads/)  
    - [v3.12.0 for Windows](https://www.python.org/ftp/python/3.12.0/python-3.12.0-amd64.exe)  
    - [v3.11.9 for Windows](https://www.python.org/ftp/python/3.11.9/python-3.11.9-amd64.exe)  

- ...  


## 의존 패키지

```
$ (.venv) pip install ipykernel numpy matplotlib scipy
```

- numpy
  - [pypi](https://pypi.org/project/numpy/)  
    ```
    $ (.venv) pip install numpy
    ```
  - Fundamental Package for Array Computing in Python

- matplotlib
  - [pypi](https://pypi.org/project/matplotlib/)  
    ```
    $ (.venv) pip install matplotlib
    ```
  - Python Plotting Package

- scipy  
  - [pypi](https://pypi.org/project/scipy/)  
    ```
    $ (.venv) pip install scipy
    ```
  - Fundamental algorithms for scientific computing in Python

- scikit-learn
  - [pypi](https://pypi.org/project/scikit-learn/)  
    ```
    $ (.venv) pip install matplotlib
    ```
  - A set of python modules for machine learning and data mining

- ipykernel
  - [pypi](https://pypi.org/project/ipykernel/)  
    ```
    $ (.venv) pip install ipykernel
    ```
  - [ipykernel](https://github.com/ipython/ipykernel)  
  - IPython Kernel for Jupyter

- PyTorch
  - [pypi](https://pypi.org/project/torch/)  
    ```
    $ (.venv) pip install torch torchvision --index-url https://download.pytorch.org/whl/cu128
    ```
  - [PyTorch](https://pytorch.org/)  
  - Tensors and Dynamic neural networks in Python with strong GPU acceleration
  - nvidia-smi v531.15
  - cuda-toolkit v12.8

- ...
  - [pypi]()  
    ```
    $ (.venv) pip install ...
    ```
  - [...]()
  - ...  


## 기타

- ...  

- ...  



---
---
---



# Tkinter GUI Application Development Blueprints - Second Edition
This is the code repository for [Tkinter GUI Application Development Blueprints - Second Edition](https://www.packtpub.com/application-development/tkinter-gui-application-development-blueprints-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788837460), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
Tkinter is the built-in GUI package that comes with standard Python distributions. It is a cross-platform package, which means you build once and deploy everywhere. It is simple to use and intuitive in nature, making it suitable for programmers and non-programmers alike.

This book will help you master the art of GUI programming. It delivers the bigger picture of GUI programming by building real-world, productive, and fun applications such as a text editor, drum machine, game of chess, audio player, drawing application, piano tutor, chat application, screen saver, port scanner, and much more. In every project, you will build on the skills acquired in the previous project and gain more expertise. You will learn to write multithreaded programs, network programs, database-driven programs, asyncio based programming and more. You will also get to know the modern best practices involved in writing GUI apps.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

All chapters have code files placed in their respective folder.

The code will look like the following:
```
def toggle_play_button_state(self):
  if self.now_playing:
    self.play_button.config(state="disabled")
  else:
    self.play_button.config(state="normal")
```

We assume an introductory level familiarity with the basic constructs of Python
programming language. We use Python version 3.6 with Tkinter 8.6, and it is recommended
to stick to these exact versions to avoid compatibility issues.
The programs discussed in this book have been developed on the Linux Mint
platform. However, given the multiplatform abilities of Tkinter, you can easily work along
on other platforms such as Windows, Mac OS, and other distributions of Linux. The links to
download and install other project-specific modules and software are mentioned in the
respective chapters.

## Related Products
* [Tkinter GUI Application Development Projects [Video]](https://www.packtpub.com/application-development/tkinter-gui-application-development-projects-video?utm_source=github&utm_medium=repository&utm_campaign=9781787280151)

* [Tkinter GUI Application Development Blueprints](https://www.packtpub.com/application-development/tkinter-gui-application-development-blueprints?utm_source=github&utm_medium=repository&utm_campaign=9781785889738)

* [Tkinter GUI Application Development HOTSHOT](https://www.packtpub.com/application-development/tkinter-gui-application-development-hotshot?utm_source=github&utm_medium=repository&utm_campaign=9781849697941)


### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781788837460">https://packt.link/free-ebook/9781788837460 </a> </p>