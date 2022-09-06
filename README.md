# Multi-level-de-duplication app


# 1. Obtain the AssemblyAI API key

Obtain your free [AssemblyAI API key](https://www.assemblyai.com/?utm_source=youtube&utm_medium=social&utm_campaign=dataprofessor).

# 2. Running transcriber as command line tool

Firstly, copy and paste the AssemblyAI API key into the `api.txt` file (you can replace the text `replace_with_your_AssemblyAI_API_key` with your own API key).

Secondly, install prerequisite `pytube` library by typing the following:
```
pip3 install pytube
```


# 3. Running Streamlit app
To recreate this web app on your own computer, do the following.

### Create conda environment (Optional)
Firstly, we will create a conda environment called *env_name*
```
conda create -n env_name python=3.7.9
```
Secondly, we will login to the *env_name* environment
```
conda activate env_name
```

###  Download GitHub repo

```
git clone https://github.com/mandyq1000/multi-level-de-duplication
```

###  Pip install libraries
```
pip install -r requirements.txt
```

###  Launch the app

```
streamlit run app.py
```
"# multi-level-de-duplication" 
