git config --global user.name VanMungTran
git config --global user.email tranvanmungbkdn@gmail.com

git config --list

<!-- create Repo -->
git init

…or create a new repository on the command line
echo "# DataSience-TranMung" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/VanMungTran/DataSience-TranMung.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/VanMungTran/DataSience-TranMung.git
git branch -M main
git push -u origin main