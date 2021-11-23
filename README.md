#Stocks and Cryptocurrency Price Web Application

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *base*
```
conda create -n base python=3.7.9
```
Secondly, we will login to the *base* environement
```
conda activate base
```
### Install prerequisite libraries

Download requirements.txt file
```
wget https://raw.githubusercontent.com/dataprofessor/stock-app/main/requirements.txt
```

Install libraries
```
pip install -r requirements.txt
```

### Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/stock-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.