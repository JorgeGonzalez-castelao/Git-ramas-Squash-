git init
git add .
git commit -m "primer commit"
git remote add origin https://github.com/JorgeGonzalez-castelao/Git-ramas-Squash-
cambios main
git add .
Git commit -m "segundo commit"
git push -u origin main
git branch lider
git checkout lider
codigo en la rama lider
git add .
git commit -m "primer commit lider"
cambios clase main
git add .
git commit -m "segundo commit lider"
cambios clase git add .
git commit -m "tercer commit lider"
Hice cambios:
git branch colaborador
git checkout colaborador
codigo en la rama colaborador
git add .
git commit -m "primer commit colaborador"
cambios clase main
git add .
git commit -m "segundo commit colaborador"
cambios clase git add .
git commit -m "tercer commit colaborador"
git checkout main
en IntelliJ merge—squash colaborador
git commit -m "squash colaborador"
en IntelliJ merge—squash lider
git commit -m "squash lider"
git push -u origin main
touch readme.md
git add readme.md git commit -m "readme añadido" git push