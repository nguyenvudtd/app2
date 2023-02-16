…or create a new repository on the command line
echo "# app2" >> README.md
git init

git add README.md
git commit -m "first commit"
git branch -M main
git remote remove origin
git remote add origin https://github.com/nguyenvudtd/app2.git
git push -u origin main

https://fullstack.edu.vn/blog/cach-dua-code-len-github-va-tao-github-pages.html
https://www.freecodecamp.org/news/git-push-local-branch-to-remote-how-to-publish-a-new-branch-in-git/

git add.
git commit -m 'commit message'
git push -u origin bug-fixes

rm -f .git/index.lock
git reset

Khi update
git reset

git add .
git commit -am "Commit message"
git push origin main
