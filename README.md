# Tensorflow Beginner's Template

In this template we have provided a __sample project structure__, __sample machine learning project__, and a __project template__.

## Setting up a Machine Learning Project

To set up a machine learning project, you can clone this directory by using this command:

```bash
git clone https://github.com/LuisMav23/innolympics-tensorflow-template.git
```

This will clone the whole repository into your local machine. After that you will need to set up your __Virtual Environment__.

First, you must __change directory__ into the cloned repository. You will need to use this command:

```bash
cd innolympics-tensorflow-template
```

To set up a __Virtual Environment__ use this command:

```bash
python -m venv venv
```

This will create a virtual environment named __venv__.

The next step is to __activate__ the virtual environment you created. To activate the virtual environment you must activate a __shell script__ inside the venv folder:

```bash
venv/Scripts/activate
```

This will activate your virtual environment. 

Then you can start installing all your __dependencies__. To install the required dependencies, you can either install the requirements.txt:

```bash
pip install -r requirements.txt
```

or you could install the individual libraries by yourself:

```bash
pip install <pachakge name>
```

## Project Structure

A Machine Learning or Data Science project mostly follows a conventional __project structure__. Here is a sample project structure that you may follow:

```
project
   |- Data 
     |- Dataset.csv
     |- Train.csv
     |- Test.csv
   |- Models
     |- cnn-128-rgb.h5
     |- cnn-64-gray.h5
   |- Notebooks
     |- preprocessing
       |- data-extracttion.ipynb
     |- EDA
       |- data-visualization.ipynb
     |- modeling
       !- model-training.ipynb
       |- model-testing.ipynb
   |- Scripts
     |- network.py
     |- web-scraping.py
     |- image-processing.py
   |- venv
```

Above is a sample project structure of a simple data science and machine learning project.

## References

