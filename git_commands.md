# config & sys commands :smile:

git config --global user.name "asnyk33"
git config --global user.email "asnyk33"

# basics
clear

# init
git init

# file & dir
pwd
mkdir dir1
rm plik1.txt
rm -r dir1
mv dir1/plik1 dir2/plik1
mv dir1/plik1 dir2/plik1_new
cp dir1/plik1 dir2/plik1

# commit
git commit -m "Komentarz"

# push
git push origin master

# staging

git add *
git add plik.txt
git add folder/
git restore --staged *
git restore --staged plik.txt
git restore --staged folder/


# remote
git remote -v
git remote add origin https://github.com/asnyk33/project1.git