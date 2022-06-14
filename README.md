## Start Machine Learning project.
'''
## Software and account Requirement.
'''

1. [Github Account](https://github.com/)
2. [Heroku Account](https://dashboard.heroku.com/)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [Git Documentation](https://git-scm.com/docs/gittutorial)


# Creating conda environment
'''
conda create -p venv python==3.7 -y
'''

'''
conda activate venv/
'''
OR
'''
conda activate venv
'''

# To install flask
'''
pip install -r requirements.txt
'''

## Git and Github

# To clone git to vscode
git clone <url>
dir or ls #check #if it is cloned
cd <dir> #go to the dir
code . #open vscode

# To Add files to git
'''
git add .
'''
OR
'''
git add <file_name>
'''

# To ignore file or folder from git we can write name of file/folder in file
'''
.gitignore
'''

# To check the git status
'''
git status
'''

# To check all version maintained by git
'''
git log
'''

# To create version/commit all changes by git
'''
git commit -m "message"
'''

# To send version/changes to github
'''
git push origin main
'''

# To pull version/changes from github
'''
git pull origin main
'''

# To check remote url
'''
git remote -v
'''

## To setup CI/CD pipeline in heroku we need 3 information

HEROKU_EMAIL = subham.g.1995@gmail.com
HEROKU_API_KEY = 222aa3be-ab5b-4ea0-ad25-a330abc80c0a
HEROKU_APP_NAME = ml-regression-app0

## Docker
BUILD DOCKER IMAGE
docker build -t <image_name>:<tagname> .
Note: Image name for docker must be lowercase

To list docker image
docker images
Run docker image

docker run -p 5000:5000 -e PORT=5000 f8c749e73678
To check running container in docker

docker ps
Tos stop docker conatiner

docker stop <container_id>
