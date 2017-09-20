echo "# projectname.git " >> README.md
git init
git add test.fie
git commit -m "your edit message" test.file
git remote add origin https://github.com/username/projectname.git
git push -u origin master
