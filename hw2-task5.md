Git Commands:

cd hw2-task5
git init
touch README.md
git add .
git commit -m "First commit with readme"
git remote add origin https://<my github auth token>@github.com/2020mkruppa/OOSE-HW2.git
git push --set-upstream origin master

git add .
git commit -m "Updated local README"
git push

git pull
(editted readme file)
git add README.md
git commit -m "Merged remote and local readmes"
git push

git branch feature1
git checkout feature1
touch FEATURE1.md
