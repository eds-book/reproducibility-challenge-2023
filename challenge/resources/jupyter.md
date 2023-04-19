(resources-jupyter)=

# Project Jupyter

[Project Jupyter](https://jupyter.org/) encompasses a wide range of tools (including Jupyter Notebooks, JupyterHub, and JupyterLab, among others) for interactive computing across all programming languages. 

We present below the relevant Jupyter technologies for the Reproducibility challenge.

## JupyterHub

JupyterHub is a multi-user server for Jupyter notebooks. 
It allows multiple users to access Jupyter notebooks through a web browser. 

JupyterHub provides a shared platform for participants to run their code and reproduce the original study's results. 
By using JupyterHub, participants can access a shared computing environment that is pre-configured with the necessary dependencies and software needed to run the code. 
This can help reduce the time and effort required to set up the reproduction environment, and ensure that all participants are using the same computing environment.

JupyterHub can also be used to facilitate collaboration between participants, as they can work together in the same computing environment and share their notebooks and code with each other. 
This can help foster a sense of community and encourage participants to learn from each other and share best practices.

In addition, JupyterHub can be used to provide a platform for reviewers and judges to evaluate the submissions. 
Reviewers and judges can access the notebooks and code in JupyterHub and run the code to reproduce the original study's results. 
This can help ensure that the submissions are evaluated in a consistent and transparent manner.

Here's a general overview of how to use cloud EGI JupyterHub:

* **Start JupyterHub:** Once you have configured your EGI account, you can use cloud EGI JupyterHub in [this link](https://repro-challenge.vm.fedcloud.eu/).
* **Access Jupyter notebooks:** Users can access Jupyter notebooks by navigating to the JupyterHub URL in their web browser and logging in with their user account.
* **Create and run Jupyter notebooks:** Users can create and run Jupyter notebooks just like they would on their local machine. They can create new notebooks, open existing notebooks, and run code cells.
* **Collaborate with others:** JupyterHub allows multiple users to work on the same notebook simultaneously. Users can share notebooks with each other and collaborate on projects.
* **Shut down JupyterHub:** When you're done using JupyterHub, you can shut it down by stopping the server process.

## Jupyter Notebook

Jupyter Notebook is an open-source web application that allows users to create and share documents that contain live code, equations, visualizations, and narrative text. 

In the reproducibility challenge, notebooks will be use to share and evaluate the reproduction process. The main highlights as follows:

* **Sharing code:** Notebooks can be used to share the code used to reproduce the original study's results. This can include the code used to generate figures, analyze data, or run simulations.
* **Providing documentation:** Notebooks can include text descriptions of the reproduction process, including any modifications or adaptations made to the original study's methods. This can help reviewers and judges understand the reproduction process and assess the accuracy of the results.
* **Facilitating evaluation:** Notebooks can be used as a platform for reviewers and judges to evaluate the submissions. They can easily run and modify the code, and see the results in real-time.
* **Encouraging transparency:** Notebooks can help promote transparency by allowing reviewers and judges to see exactly how the reproduction was conducted. This can help ensure that the reproduction process was conducted in a rigorous and transparent manner.
* **Improving reproducibility:** Notebooks can be used to highlight areas of the reproduction process where improvements can be made to increase reproducibility. This can include identifying areas where the original study's methods were unclear or where the data or code were not well-documented.

Here's a general overview of how to use Jupyter Notebook within the cloud EGI JupyterHub and locally:

* **Create a new notebook**: To create a new notebook, click on the "New" button in the top right corner of the JupyterHub homepage and select the Kernel (programming language and version) you want to use.
* **Write code:** You can write code in the code cells of your notebook. To execute a code cell, you can either click the "Run" button in the toolbar or press "Shift+Enter".
* **Add text and equations:** You can add text and equations to your notebook using Markdown. Markdown is a lightweight markup language that allows you to format text, create headings, and add links and images. To add an equation, you can use LaTeX syntax.
* **Save and share your notebook:** Once you have created your notebook, you can save it by clicking the "Save" button in the toolbar. You can also download your notebook as a PDF, HTML, or Markdown file. To share your notebook with others, you can upload it to GitHub or share it on nbviewer.