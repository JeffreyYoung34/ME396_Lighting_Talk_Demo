# ME396_Lighting_Talk_Demo
Repo for ME396 Group 10: Cognitive Coders Lighting Talk Demo Code 
Team 10 Team Members: Josh Haase, Dante Solano, Lawerence Gomez, Jeffrey Young
This Repo contains an iPython Notebook and the relevant training data set. Students 
can open and run the notebook using Jupyter Notebooks, VS Code, or any supported IDE. 
Students will need to import the Jupyter, Scipy, Matplotlib, and scikit-learn libraries to run this code 

### IMPORT LIBRARIES ###
pip install jupyter scipy matplotlib scikit-learn

### FILES ### 
Lightning_Talk.ipynb - iPython Notebook containing demo code 
chinese_characters.tar.gz - Learning Data set of Chinese Characters

### EXTRACTING DATA SET ### 
run command $ tar -xzvf chinese_characters.tar.gz $ to unzip the file and access the data set 


### RUNNING ### 
To run this iPython Notebook, remove the google cloud mount section: 

from google.colab import drive
drive.mount('/content/drive')

and add in the local path to the data chinese characters data set in this line 
$ dfdigit = pd.read_csv('YOUR_PATH') $
where YOUR_PATH is the custom path to the data set, e.g YOUR_PATH = /home/user/custom_user_demo_dir/chineseMNIST.csv 
