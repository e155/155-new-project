mkdir new-project
cd new-project
git init
touch README.md
git add README.md
git commit -m "init"
git branch development
git checkout development
# Filling README.md 
git add README.md
git commit -m "Modified README.md"
git checkout main
git merge development
