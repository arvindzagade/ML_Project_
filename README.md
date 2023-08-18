## ML_Project1-FSDS
Machine Learning Project E2E in the FSDS batch with docker

### software and account Requirement:

1. [GitHub Account](https://github.com)
2. [Heroku Account](https://id.heroku.com/login)
3. [Vs Code Online](https://code.visualstudio.com/download)
4. [Git Cli](https://git-scm.com/downloads)
5. [Git Documentation](https://git-scm.com/docs/gittutorial)


Creating conda enviornment
```
conda create -p venv python==3.7 -y
```
```
conda activate venv/
```
OR
```
condata activate venv
```
```
pip  install -r requirements.txt
```
To Add files to git
```
git add .
```
OR 
```
git add <filename>
```
> Note: To ignore file or folder from git we can write name  of file /folder in .gitignore file

To check the git status
```
git status
```
To check all version mentained by git
```
git log
```
To create version/commit all changes by git
```
git commit -m "message"
```
To send version/changes to github
```
git push -u origin main(branch name)
```

To check remote Url
```
git remote -v
```
To setup CI/CD Pipeline in heroku we need 3 information
1. HEROKU_EMAIL = 'XYZ'
2. HEROKU_API_KEY = 
3. HEROKU_APP_NAME =

Build Docker Image
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be in  lowercase

To list docker image
```
docker images
```
Run docker Image
```
docker run -p 5000:5000 -e PORT=5000 <ImageID>
```
To check running containers in docker
```
docker ps
```
To stop docker container
```
docker stop <container_id>
```