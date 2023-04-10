# Ml_project

# Start ML Project

Software and account requirements

1. Github Account
2. Heroku Account
3. VS Code IDE
4. GIT CLI

## Creating conda env

```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```

```
pip install -r requirements.txt
```

To add files to git
git add .

Note: To ignore file or folder from git we can write name of file or folder in .gitignore file

To check git status:
git status

To check all version maintained by git
git log

To create version/commit all changes by git
git commit -m "message"

To check remote url
git remote -v

To send version/changes to github
git push origin main

To setup CI/CD pipeline in heroku we need 3 info

1. HEROKU_EMAIL = santumete01@gmail.com
2. HEROKU_API_KEY = 4ec2a03a-dd72-4447-b9d5-45cc36e2cbf3
3. HEROKU_APP_NAME = ml--app

BUILD DOCKER IMAGE

```
docker build -t <image_name>:<tagname> .
```

> Note: Image name for docker must be lowercase
> To list docker images

```
docker images
```

```
docker run -p 5000:5000 -e PORT=5000 5a46b68453ac

```

To check running container in docker

```
docker ps
```

To stop docker container

```
docker stop <container_id>
```

```
python setup.py install
```
