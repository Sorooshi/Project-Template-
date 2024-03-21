# Project-Template-
This is a generic template for the projects.


- The project description, including the title and its brief overview, should be described here.

- In principle one should be able to run your code and pass the necessary arguments using the following command:

``` python main.py --arguments=*** ```

- Define the dependencies (requirements) of your project/package in "requirement.txt" file. 
So that later one can install them using ```pip install -r requirements.txt```.

- Do NOT push in the main branch.


- The project structure is as follows:

project_name/
|__ src/
|    |__ common/
|    |    |__ util.py,
|    |    |__ metrics.py, 
|    |    |__ # etc.
|    |
|    |__ models/ 
|    |    |__ models.py  
|    |    |__ classification.py
|    |    |__ # etc.
|    |
|    |__ data/
|    |    |__ data_loader.py
|    |    |__ # etc.
|    |
|    |__ train/  
|    |   |__ # optional
|    |
|
|__ data/
|   |__ blah_blah.csv
|   |__ # etc.
|
|__ config\
|   |__*.yaml


