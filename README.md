# MachineLearning1106
This is First Machine Learning Project 


creating conda environment 
````

conda create -p venv python==3.7 -y
````

''' cond activate venv/
'''

'''
pip install -r requirements.txt

'''

To Add all files to git 
```
git add . 
```

or 

git add <file_name>

Note : To ignore file or folder from git we can write name of file/folder in .gitignore file 

to check the git status

``` git status 
``` 

to check all version maintained by git 

git log 

to create version/commit all changes by git 

git commit -m "message" 

To send version/changes to github 

git push origin main 


To  check remote url 

git remote -v 


To set up CI/CD pipeline in Heroku following details are required 

1. Heroku_Email = sumitbharti93@gmail.com
2. Heroku_API_KEY = b1ec752c-4428-4e14-a60d-c3692f89d688
3.Heroku_App_Name = mlearn-regression-app


Build docker Image 

''' docker build -t <image_name>:<tagname> . '''

Note: Image name for docker must be lowercase 

To list docker image 
''' docker image ''''

Run docker image 

''' docker run -p 5000:5000 -e PORT=5000 
