# Recommendations with IBM Project
Recommendations with IBM Project in Data Science Nano Degree

### Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## 1. Installation <a name="installation"></a>

To be able to run and view this project. It's recommended to have the latest versions of the followings:
* [Python 3](https://www.python.org/downloads/)
* [Pandas](https://pandas.pydata.org)
* [NumPy](https://numpy.org/)
* [plotly](https://pypi.org/project/plotly/)

you need to install Jupyter Notebook to run and execute an Jupyter Notebook

## 2. Project Motivation <a name="motivation"></a>

For this project, I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles that would they will like.

## 3. File Descriptions <a name="files"></a>

The project consist from 

    - data folder that contains the data set csv's files: 
        - user-item-interactions.csv file: contain the data about users and articles interactions.
        - articles_community.csv file: contain the data about articles.
    
    - Recommendations_with_IBM.ipynb file:
        Jupyter Notebook that carries projects parts:
        
            I. Exploratory Data Analysis:
                Where I explored the data I'm working with for the project.
                
            II. Rank Based Recommendations:
                Where I found the most popular articles simply based on the most interactions.
                
            III. User-User Based Collaborative Filtering:
                Looked at users that are similar in terms of the items they have interacted with and made recommendations based on this similarities.
                
            IV. Matrix Factorization:
                Used a machine learning approach to building recommendations. Using the user-item interactions build out a matrix decomposition. then used the decomposition to make perdiction about recommendations to users.
        
    - Recommendations_with_IBM.html file: an html version of Recommendations_with_IBM.ipynb file
        
    - project_tests.py file: python file that contains test carried in Recommendations_with_IBM.ipynb
    
    - top_5.p, top_10.p and top_20.p files: hold's data related to project_tests.py
    
    - user_item_matrix.p file: hold's user item interaction matrix loaded in Matrix Factorization part in Recommendations_with_IBM.ipynb.

 


## 4. Licensing, Authors, and Acknowledgements <a name="licensing"></a>

Credit given to Udacity courses for code ideas and motivation , and to IBM Watson Studio platform for the data.

