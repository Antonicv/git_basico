# git basico

1 crear el git ignore y readme.md
2 iniciar proyecto : git init
3 Configuración
git config:[--global] user.name ("nombre")
git config:[--global] user.email ejemplo@gmail.com
git.config [--global] core.autocrlf windows true / linux input
git config --global core.editor "code --wait" (cambiar el editor de visual- wait es para que inicie y proboque errores)
git status comprobar el status del proyecto
pasar al stage: git add .gitignore README.md
 
 pasar al commit (version 1)
 git commit -m "README modificado" (texto descriptivo sobre lo que se ha hecho)
 git commit -a -m "README modificado"
 (puedes cambiar el nombre de la rama con git branch -m (nombre))
 