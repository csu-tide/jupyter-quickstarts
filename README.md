# Quick Starts to Utilize GPU and CPU resources
This is a collection of Jupyter Notebooks quick starts designed to get you quickly running on the [TIDE's JupyterHub instance](https://csu-tide-jupyterhub.nrp-nautilus.io/), whether your program requires CPU or GPU hardware. These notebooks, with slight modifications, should run on any JupyterHub instance that is a part of the [National Research Platform](https://nationalresearchplatform.org/). You may modify and build on the quick starts to suit your needs, but the examples are utilizing TIDE's CPU and GPU resources primarily on data science, artificial intelligence (AI), and machine learning (ML).

### Why Jupyter Notebooks?
Jupyter Notebooks are an easy to use, web-based way to utilize advanced Cyberinfrastructure (CI). Notebooks on TIDE's JupyterHub allow you to select from pre-created software images that may contain everything you need to get started, and make the experience similar for all users (great for teaching and learning!).

## Using the Quick Starts

The quick starts are organized by hardware resource (CPU or GPU), learning topic, and the level of difficulity (easy, intermediate, advanced) as well as description, learning objectives and details you need to launch the notebook.

To use a quick start follow this workflow:

1. Download the Jupter Notebook file linked in the **Notebook** column below. Click the link and then click the **Download raw file** button. This will download a .ipynb file to your local computer.
2. Next, access the [TIDE JupyterHub instance](https://csu-tide-jupyterhub.nrp-nautilus.io/) and launch a new sever using the suggested **Image** and **Resources** recommendations listed in the table.
3. Once the server has launched and you're presented with the JupyterLab interface, use the upload button on the file explorer browser to upload the .ipynb file you downloaded in step 1. Once the file uploads, find it in the file browser and double click it.
4. With the notebook open, follow the instructions in the notebook to explore the quick start.

[![TIDE JupyterHub Quick Starts](http://img.youtube.com/vi/w6rRg17f0u0/0.jpg)](http://www.youtube.com/watch?v=w6rRg17f0u0 "TIDE JupyterHub Quick Starts")


# Available Quick Starts (Todo)

- [Getting Started](#getting-started)
- [Computer Vision](#computer-vision)
- [Data Science](#data-science)
- [Large Language Models](#large-language-models)

## Getting Started

| **Level** | **Description** | **Software** | **Notebook** | **Image/Resources** | **Time** |
| --------- | --------------- | ----------------------- | ------------ | --------- | -------- |
| ![easy][easy-badge] | Logging into JupyterHub and exploring the JupyterLab interface. Learn how to run code cells, use markdown, and run system commands from Notebooks. | JupyterLab</br>Python</br>Markdown | [![Jupyter Notebook][jupyter-badge]](getting-started/jupyter-getting-started.ipynb) | **Image**: Stack Minimal<br/>**Resources**: 0 GPU, 1 CPU cores, 1 GB RAM | 20 minutes | 


***
## Utilizing CPU Resources
### Data Science

| **Level** | **Description** | **Software** | **Notebook** | **Image/Resources** | **Time** |
| --------- | --------------- | ----------------------- | ------------ | --------- | -------- |
| ![easy][easy-badge] | This Jupyter notebook demonstrates a comprehensive data analysis on a wine dataset using three essential Python libraries such as Numpy, Pandas, and Matplotlib.| Python</br>Python Libraries (Numpy, Pandas, Matplotlib)|[![Jupyter Notebook][jupyter-badge]](data-science/datascience.ipynb) | **Image**: Stack Datascience Notebook<br/>**Resources**: 0 GPU, 1 CPU cores, 1 GB RAM | 20 minutes | 


## Utilizing a Single GPU
### Computer Vision

| **Level** | **Description** | **Software** | **Notebook** | **Image/Resources** | **Time** |
| --------- | --------------- | ----------------------- | ------------ | --------- | -------- |
| ![intermediate][intermediate-badge] | Fine tune an object detection model to track players in a pro pickleball match recording | Python</br>Wget</br>YOLO</br>OpenCV | [![Jupyter Notebook][jupyter-badge]](computer-vision/roboflow.ipynb) | **Image**: Stack PRP<br/>**Resources**: 1 L40 GPU, 2 CPU cores, 12 GB RAM | 25 minutes | 


### Large Language Models

| **Level** | **Description** | **Software** | **Notebook** | **Image/Resources** | **Time** |
| --------- | --------------- | ----------------------- | ------------ | --------- | -------- |
| ![][easy-badge] | Ollama is an open source tool for downloading and hosting large language models (LLMs). Use Ollama with Jupyter Notebook to easily query the LLMs using the OpenAI API library. | Python</br>Ollama</br>OpenAI API | [![Jupyter Notebook][jupyter-badge]](llms/ollama-llm-quick-start.ipynb) | **Image**: LLM Notebook<br/>**Resources**: 1 L40 GPU, 2 CPU cores, 4 GB RAM | 30 minutes | 

Learning Objectives:
1. Familiarize yourself with the Ollama tool
2. Download the llama3 8B model
3. Ask questions of llama3 using the OpenAI API library

## Utilizing Multiple GPUs (coming soon)
### Hosting Multiple LLM Models (To be Added soon)
| **Level** | **Description** | **Software** | **Notebook** | **Image/Resources** | **Time** |
| --------- | --------------- | ----------------------- | ------------ | --------- | -------- |
| ![intermediate][intermediate-badge] | Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. | Python</br>Ollama</br>OpenAI API | TBD | **Image**: LLM Notebook<br/>**Resources**: 2 L40 GPU, 2 CPU cores, 16 GB RAM | 30 minutes | 

***
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[easy-badge]: https://img.shields.io/badge/easy-%234CAF50?style=for-the-badge
[intermediate-badge]: https://img.shields.io/badge/intermediate-ed9121?style=for-the-badge
[advanced-badge]: https://img.shields.io/badge/advanced-%23F44336?style=for-the-badge
[jupyter-badge]: https://img.shields.io/badge/jupyter-.ipynb%20file-orange
