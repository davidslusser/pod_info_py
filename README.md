# pod_info_py
A simple Flask app for displaying information about a Kubernetes pod hosting the app

<br/>

### To setup your enviornment (for running locally)
```shell
python -m venv venv
source venv/bin/activate
pip install -r app/requirements.txt
```
<br/>

### To Run locally
```shell
cd app
python app.py
```
<br/>

### To build the Docker image
```shell
docker build . -t pod_info_py
```
<br/>

### To run the Docker image
```shell 
docker run -p 8080:8080 pod_info_py
```
