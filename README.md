**Hello Solar Panel Data Analyzers**

Looks like you've stumbled across the Solar Panel Data Analysis Git Repository. It contains irradiance, capacity, and panel temperature data, as well as a python notebook to interpret all of that information. The end goal here is to determine what variables are the most indicative of power output. This will make it so I can adjust my irradiance, temperature, and alternating current variables within my machine learning model according to real world associations.

**Setup**

There are two ways to use the tutorial above. One is using your local machine, and assumes you have many libraries such as Numpy and Matplotlib installed. The alternative way involves making a copy of the attached Python Notebook file that you can adjust as necessary.

*Option 1 (Google Colab) **Recommended***

Although this method requires the use of online software which can be considered intimidating at first, in the end it is the easier option. Not only does it come with all libraries preinstalled and ready to go, but it also has flexible capacity which can be expanded to make your code run faster.

1. You will first want to clone the above repository on to your computer. This can be done by typing git clone into the command line while you are in a valid repository. More details [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).
3. Find the cloned project on your GitHub page. Click on the "Code" button, and then "Download as Zip"![image](https://user-images.githubusercontent.com/70772760/234469995-7a979c34-58ab-4e86-975e-95c5c7a5459b.png)
4. Click on the .ipynb file, and then "Open in Google Colab"![image](https://user-images.githubusercontent.com/70772760/234482018-0c3f2482-4fef-4477-963f-b6af45443eb4.png)
5. Sign into your Google account. If you don't have one, you will not be able to save your work.
6. You should see all the data and outputs! Unfortunately, it won't work yet, as the data involving irradiance and AC input is zipped. In order to make it accessible to the program at large, you will use Linux commands through the versatile Colab interface. 
    1. Go to the top of your notebook and click on (+ Code). 
    2. Drag the zipped folder into the Google Colab instance. It should show up if you click the folder icon on the side.
    3. Run the cell that starts with ```!unzip kaggle.zip``` using the shortcut Ctrl+Enter. 
    4. Comment out that cell, to avoid an annoying text box prompt. You will need to use that code again whenever you restart the instance (or the instance is                restarted for you)
    5. Activate the rest of the notebook. You can do this by going to Runtime -> Run all

Now, you should be able to modify and add code to the repository, with standard Git knowledge!

*Option 2 (Jupyter Notebooks)*

1. Clone the repository, as before
2. Then, search online for how to use and get the following libraries on your PC (if they are not already installed):
    1. Matplotlib
    2. Seaborn
    3. StatsModels
    4. SciPy
    5. HoloViews (Extension Bokeh)
    6. Cufflinks
    7. Jupyter Notebooks
3. Open the .ipynb in Jupyter Notebooks. For how to do that, visit [this Jupyter Notebooks tutorial](https://docs.jupyter.org/en/latest/running.html). 
4. Run the code. If it's your first time using Jupyter, you can run the notebook using [this](https://docs.qubole.com/en/latest/user-guide/notebooks-and-dashboards/notebooks/jupyter-notebooks/running-jupy-notebooks.html) series of commands - Run, and then Run All. You should see the same results, graphs, files etc pop up as was saved in the notebook, but now you can adapt the Python file to fit your needs. Running any block can be done with shift enter
    
Great work! Now scroll through the tutorial and enjoy learning about the correlation of variables relating to local panel aggregation!
