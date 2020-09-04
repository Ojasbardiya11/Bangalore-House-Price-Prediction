## Bangalore-House-Price-Prediction ##
Used pandas, matplotlib, numpy, and sklearn in python 3.7 to generate a MLR (Multi Linear Regression) model to predict house prices in Bangalore with 91.88% accuracy based on the following parameters - location, BHK size, number of baths and number of balconies.

### Input ###
* Bengaluru_House_Data.csv
  
  The main dataset is available at https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data

### Setup ###

* Windows

     * Python install
     
        Download latest from following URL https://www.python.org/downloads/
        
        Add python path to **environment variable**.
 
        
    * pip install
    
        Follow instructions in https://phoenixnap.com/kb/install-pip-windows
        Add path to Environment variable.
        Goto project folder and enter following command 
        
            pip install -r requirements.txt
        
* Ubuntu
    * Python install
    
            sudo apt install python3.7
        
            python3.7 --version
  
        **Sample Path**
        
            /usr/bin/ffmpeg
      
        
* The steps to install Jupyter notebook can be downloaded from here: https://jupyter.org/install

### Folders ###

The Data_filtering.png file in this repository depicts the process of filtering the data and setting up the final predictor and response variable(s) via a flowchart.

The Bangalore_house_predictor.ipynb file shows the cumulative process of extracting, filtering and analyzing the data to create the final MLR model.

### Command to Run ###

Download as .py file and run the following on the command line
            python Bangalore_house_predictor.py


**Versions used**:
Python 3.7
Jupyter notebook 6.0

