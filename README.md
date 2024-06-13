# Jupyter Notebook Quick Starts
This is a collection of Jupyter Notebooks quick starts designed to run on [TIDE's JupyterHub instance](https://csu-tide-jupyterhub.nrp-nautilus.io/), or with slight modifications, any JupyterHub instance part of the [National Research Platform](https://nationalresearchplatform.org/). These quick starts are designed to get you started on a specific topic quickly, allowing you to modify and build on the quick start to suit your needs. The focus is primarily on data science, artificial intelligence (AI), and machine learning (ML).

### Why Jupyter Notebooks?
Jupyter Notebooks are an easy to use, web-based way to utilize advanced Cyberinfrastruucture (CI). Notebooks on TIDE's JupyterHub allow you to select from pre-created software images that make contain everything you need to get started, and make the experience similar for all users (great for teaching and learning!).

# Available Notebooks
The top part of the table consists of tools and methods developed at Bellingcat; the bottom part of community developed tools and methods.

| **Category** | **Level** | **Description** | **Software/Frameworks** | **Learning Objectives** | **Notebook** | 
| :----------: | --------- | --------------- | ----------------------- | ----------------------- | ------------ |
| Computer Vision | ![intermediate][intermediate-badge] | Fine tune an object detection model to track players in a pro pickleball match recording | - Python</br>- Wget</br>- YOLO</br>- OpenCV | 1. Grab an open-source dataset from Roboflow (API)</br> 2. Use Ultralytics' YOLOv8 library to train and test models</br> 3. Create a model fine-tuned on a dataset</br> 4. Test the fine-tuned model on an example video | [![Jupyter Notebook][jupyter-badge]](computer-vision/roboflow.ipynb.ipynb) |

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[easy-badge]: https://img.shields.io/badge/easy-%234CAF50?style=for-the-badge
[intermediate-badge]: https://img.shields.io/badge/intermediate-ed9121?style=for-the-badge
[advanced-badge]: https://img.shields.io/badge/advanced-%23F44336?style=for-the-badge
[jupyter-badge]: https://img.shields.io/badge/jupyter-.ipynb%20file-orange
