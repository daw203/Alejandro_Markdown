[comment]: <> (Alejandro Ceballos Callejo)

[comment]: <> (Comandos)

**git config --global user.email alejandro.ceballoscallejo@iesmiguelherrero.com**

**git config --global user.name "daw203"**

**git init**

**git clone https://github.com/daw203/Alejandro_Markdown.git**

**git add README.md**

**git status**

**git commit -m "Primer commit de Alejandro"**

**git push**

**git config --global core.excludesFile .gitignore**

**git tag v0.1**

**git add -A**

**git commit -m "Cambios de Alejandro"**

**git push**

Compañero | Enlace
:---- | :----
Raul Lavin | https://github.com/raullavin/RaulLavin_Markdown
Javier Sosa | https://github.com/JavierSosa1/Javier_markdown
Antonio Lopez | https://gitlab.com/antonioalopezfernandez/ANTONIOLOPEZ_Markdown

**git branch rama-ALEJANDRO**

**git checkout rama-ALEJANDRO**

**git add despliegue.md**

**git commit -m "Añadiendo el archivo despliegue.md en la rama-ALEJANDRO"**

**git push origin rama-ALEJANDRO**

**git checkout main**

**git merge rama-ALEJANDRO**

**git add -A**

**git commit -m "Añadida primera evaluacion Despliegue"**

**git checkout rama-ALEJANDRO**

**git add -A**

**git commit -m "Añadida tabla segunda evaluacion Despliegue"**

**git checkout main**

**git merge rama-ALEJANDRO**

**git add -A**

**git commit -m "Finalizado el conflicto de despliegue.md"**

**git merge rama-ALEJANDRO**

**git tag v0.2**

**git branch -d rama-ALEJANDRO**