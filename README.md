# ME396 Group 10: Cognitive Coders Lighting Talk Demo

**Team Members:**  
Josh Haase  
Dante Solano  
Lawerence Gomez  
Jeffrey Young  

## Files
- `Lightning_Talk.ipynb` – iPython Notebook containing demo code  
- `chinese_characters.tar.gz` – Learning Data set of Chinese Characters  

## Setup
```bash
pip install jupyter scipy matplotlib scikit-learn
tar -xzvf chinese_characters.tar.gz
User must remove:  

from google.colab import drive
drive.mount('/content/drive')

And edit  
dfdigit = pd.read_csv('YOUR_PATH')  
where 'YOUR_PATH' = /home/user/custom_user_demo_dir/chineseMNIST.csv # Path to ChineseMNIST.csv