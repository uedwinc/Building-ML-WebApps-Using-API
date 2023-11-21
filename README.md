# Building Machine Learning WebApps

## Building Machine Learning WebApps using FastAPI

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


## Building Machine Learning WebApps using Streamlit