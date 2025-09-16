### Boston House Pricing Prediction

### Software And Tools Requirements

1. [Github account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment  
In Anaconda Prompt,

```
conda create -n venv python==3.7 -y

conda activate venv/
```

Create a requirements.txt file and add these packages

```
Flask
scikit-learn
pandas
numpy
matplotlib
```

Install the packages in the requirements.txt file

```
pip install -r requirements.txt
```

Configure the git

```
git config --global user.name "Satya Prakash Sahoo"
git config --global user.email "mynameissatyaprakashsahoo@gmail.com"
```

Add the files using git to staging area

```
git add requirements.txt README.md (if you want to add only a single or selected no of files)
git add . (if you want to add all the files, we will use this one)
```

Check the status of the files

```
git status
```

Commit the files in the staging

```
git commit -m
```
