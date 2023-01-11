# gitinit
steps to deploy node app on heroku:
* installation:
1-/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2-brew tap heroku/brew && brew install heroku
3-check installation with:heroku --version

* create and pushing local repo"
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:username/repo'sname.git
git push -u origin main

*heroku login 
*heroku create -a example-app
*git push heroku main

live deploying https://examplesss.herokuapp.com/
