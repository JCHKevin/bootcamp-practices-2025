<!-- inicializando nuestro repositorio -->

**inicializando nuestro repositorio**
git init

**verificar el estado de los archivos**
git status
git status -s

**sirve para agregar archivos**
git add <nombrearchivo>
git add .
git add --all

**agregamos los comentarios de los cambios realizados**
git commit -m

**subiendo los cambios al repositorio remoto**
git push origin <ramaprincipal>

### Comandos Adicionales

**Configuracion de usuario**
git config user.name
git config user.email
git config user.name <usuarioGithub>
git config user.email <correoGithub>

**para verificar que haya un repository**
git remote -v

**agregar un repositorio remoto**
git remote add origin <enlaceRepositorioGithub>
