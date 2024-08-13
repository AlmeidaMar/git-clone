# git-clone
echo "# git-clone" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AlmeidaMar/git-clone.git
git push -u origin main
