# This is sample dockerize python web app with flask

This sample contain k8s deployment sample (deploy.yml)

Usage:
To run this sample before dockerize > python index.py
To build this docker sample > docker build --tag python-flask-sample .
To trial run dockerize sample locally > docker run --name python-flask-sample -p 5000:5000 python-flask-sample
To give a tag to docker image before docker push > docker tag python-flask-sample easonlai/python-flask-sample
To push image to docker hub > docker push easonlai/python-flask-sample
To create new deployment in K8S cluster > kubectl create -f deploy.yml
To delete deployment in K8S cluster > kubectl delete -f deploy.yml


