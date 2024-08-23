<h1>GITHUB COMMANDS</h1>
<p>CONFIGURAR
git config --global user.name "Emma Paris"
git config --global user.email "eparis@atlassian.com"
git config --list

Una vez te posicionas en la carpeta que quieras usar para descargar los archivos github usas:

git clone <URL>

Para ver el historial de todos los commits se usa el:

git log

o tambien puedes usar el 
git log --oneline

STATUS,ADD,COMMIT,PUSH

git pull = sirve para ver si esta actualizado tu trabajo en el area local

git status = para ver el estado de nuestro proyecto (antes de subir)

git add . = para subir todos los archivos 

git status = para confirmar lo que se subira

git commit -m "mensaje" = para agregar el commit y lo que se subira como comentario

git push = envia los archivos creados.
RESTORE

git log --online

copias el hash del commit que se quiere restorar

git restore --source <hash> <nombre del archivo>

despues ya haces dnuevo el add ., commit -m, push 

BRANCH
git branch = para ver en que rama estoy
git checkout -b <nueva branch>
git switch <branch a la que te quieres mover>
(creas lo que sea y cuando lo subas al nuevo branch usas)
git push origin <branch en la que estas o a la que lo quieres subir>

MERGE
(Fusiona la branches )
git log --oneline
git switch (te cambias al branch main)
git merge <branch que deseas juntar>
git log --oneline
git push origin main
INIT
git init
git status

--------------------------
CREAR
git clone [URL]
git init

VERIFICAR
git status
git log
git diff
git branch

AGREGAR
git add .
git add [archivo]

MOVER
git commit -m "[mensaje]"

Enviar 
git push

BAJAR ACTUALIZACIONES
git pull 

CAMBIAR
git checkout -b [branch-name]
git merge
git switch
git restore --source [hash] [archivo]
</p>
