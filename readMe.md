# myFirstRepository: commands to create a new repository

echo "# myFirstRepository" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ParhaDebnath/myFirstRepository.git
git push -u origin main