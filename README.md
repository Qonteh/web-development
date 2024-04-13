git clone https://github.com/Qonteh/web-development.git
cd web-development
git log --oneline
git diff HEAD^
git checkout -b resolution
git commit -m "Resolved conflicts"
git checkout main
git push origin main
cd touch index.html
