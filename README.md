# Jupyter Notebook Quick Starts
This is a collection of Jupyter Notebooks quick starts designed to run on [TIDE's JupyterHub instance](https://csu-tide-jupyterhub.nrp-nautilus.io/), or with slight modifications, any JupyterHub instance part of the [National Research Platform](https://nationalresearchplatform.org/). These quick starts are designed to get you started on a specific topic quickly, allowing you to modify and build on the quick start to suit your needs. The focus is primarily on data science, artificial intelligence (AI), and machine learning (ML).

### Why Jupyter Notebooks?
Jupyter Notebooks are an easy to use, web-based way to utilize advanced Cyberinfrastructure (CI). Notebooks on TIDE's JupyterHub allow you to select from pre-created software images that may contain everything you need to get started, and make the experience similar for all users (great for teaching and learning!).

## Using the Quick Starts

The quick starts are organized by topic along with details on the level (easy, intermediate, advanced) as well as desciption, learning objectives and detail you need to know to launch a notebook.

To use a quick start follow this workflow:

1. Download the Jupter Notebook file linked in the **Notebook** column below. Click the link and then click the **Download raw file** button. This will download a .ipynb file to your local computer.
2. Next, access the [TIDE JupyterHub instance](https://csu-tide-jupyterhub.nrp-nautilus.io/) and launch a new sever using the suggested **Image** and **Resources** recommendations listed in the table.
3. Once the server has launched and you're presented with the JupyterLab interface, use the upload button on the file explorer toolbar to upload the .ipynb file you downloaded in step 1. Once the file uploads, find it in the file explorer and double click it.
4. With the Notebook open, follow the instructions in the Notebook to explore the quick start.

[![TIDE JupyterHub Quick Starts](http://img.youtube.com/vi/w6rRg17f0u0/0.jpg)](http://www.youtube.com/watch?v=w6rRg17f0u0 "TIDE JupyterHub Quick Starts")


# Available Quick Starts

- [Getting Started](#getting-started)
- [Computer Vision](#computer-vision)

## Getting Started

| **Level** | **Description** | **Software** | **Notebook** | **Image/Resources** | **Time** |
| --------- | --------------- | ----------------------- | ------------ | --------- | -------- |
| ![easy][easy-badge] | Logging into JupyterHub and exploring the JupyterLab interface. Learn how to run code cells, use markdown, and run system commands from Notebooks. | JupyterLab</br>Python</br>Markdown | [![Jupyter Notebook][jupyter-badge]](getting-started/jupyter-getting-started.ipynb) | **Image**: Stack Minimal<br/>**Resources**: 0 GPU, 1 CPU cores, 1 GB RAM | 20 minutes | 

Learning Objectives:
1. Understand Jupyter Notebooks and their value
2. Use basic keyboard shortcuts
3. Use markdown cells
4. Use code cells
5. Use magic commands
6. Use Linux commands in code cells

***

## Computer Vision

| **Level** | **Description** | **Software** | **Notebook** | **Image/Resources** | **Time** |
| --------- | --------------- | ----------------------- | ------------ | --------- | -------- |
| ![intermediate][intermediate-badge] | Fine tune an object detection model to track players in a pro pickleball match recording | Python</br>Wget</br>YOLO</br>OpenCV | [![Jupyter Notebook][jupyter-badge]](computer-vision/roboflow.ipynb) | **Image**: Stack PRP<br/>**Resources**: 1 L40 GPU, 2 CPU cores, 12 GB RAM | 25 minutes | 

Learning Objectives:
1. Grab an open-source dataset from Roboflow (API)
2. Use Ultralytics' YOLOv8 library to train and test models
3. Create a model fine-tuned on a dataset
4. Test the fine-tuned model on an example video

***

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[easy-badge]: https://img.shields.io/badge/easy-%234CAF50?style=for-the-badge
[intermediate-badge]: https://img.shields.io/badge/intermediate-ed9121?style=for-the-badge
[advanced-badge]: https://img.shields.io/badge/advanced-%23F44336?style=for-the-badge
[jupyter-badge]: https://img.shields.io/badge/jupyter-.ipynb%20file-orange
