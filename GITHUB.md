## GitHub Setup Test
git init
echo "# my-react-app" >> README.md
git add README.md
git add GITHUB.md
git config --global user.email support@infoquick.com
git config --global user.name "InfoQuick Digital Support"
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/infoquick-digital/my-react-app.git
git push -u origin main