Git global setup

git config --global user.name "Name Surname"

git config --global user.email "name.surname@domain.com"

Create a new repository

git clone https://gitlab.xxx.xxxx/xxx/xxxx-test.git

cd xxxx-test

touch README.md

git add README.md

git commit -m "add README"


Push an existing folder

cd existing_folder

git init

git remote add origin https://gitlab.xxx.xxxx/xxx/xxxx-test.git

git add .

git commit -m "Initial commit"

Push an existing Git repository

cd existing_repo

git remote rename origin old-origin

git remote add origin https://gitlab.xxx.xxxx/xxx/xxxx-test.git



