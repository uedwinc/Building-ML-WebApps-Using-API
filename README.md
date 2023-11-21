# Building Machine Learning WebApps

## 1. Using FastAPI

### Requirements

1. Start up an EC2 instance on AWS

2. FastAPI requires Python 3.6 and above

3. Create a python virtual environment (For Ubuntu)

> Update Packages
```
sudo apt-get update
```

> Install
```
pip install virtualenv
```

> Create
```
python3 -m virtualenv fastapi-env
```

> Activate
```
source fastapi-env/bin/activate
```

![fastapi-env]()

### Installations

- Install packages in requirements.txt

```
pip install -r requirements.txt
```

- Install FastAPI and uvicorn, an Asynchronous Server Gateway Interface (ASGI) server, for production.

```
pip install fastapi uvicorn
```
- See all files

![tree]()

### Run the App

```
uvicorn loan_pred_app:app --reload
```

![app running]()


## 2. Using Streamlit

- Activate a virtual environment for streamlit

![streamlit-env]()

- Install streamlit
```
pip install streamlit
```

- To verify the installation, do
```
streamlit hello
```

- Create the application file for the ML-based application

[streamlit_app.py]()

- Run the app
```
streamlit run streamlit_app.py
```
OR
```
streamlit run streamlit_app.py &>/dev/null&
```

> To deploy your Streamlit app on the streamlit cloud, you can use Streamlit sharing. Upload your files with the requirements.txt file on GitHub. Create an account on their website at https://streamlit.io/cloud and then provide a GitHub link and streamlit app file. This will deploy your app on the streamlit cloud.

## 3. Using Flask