echo "# jar" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin http://localhost/TvBox/jar.git
git push -u origin main
