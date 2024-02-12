echo "# jenkinspipeline" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/zam5095/jenkinspipeline.git
git push -u origin main
