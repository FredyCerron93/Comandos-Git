# Lista de Comandos 
1. PARA INICIAR REPOSITORIO
git init //crea repositorio
git remote add origin https:.... //va el link
//-----------------------------------------------------------------------------------------------
2. subir el proyecto
2.1. git add .
git reset . 			//deshace los archivos incluidos en el ADD
git commit -m "'mensaje'"
git commit --amend 		//editar el ultimo commit (press 'i', 'ESC, :, wq!')
git checkout -- . 		//vuelve a la version anterior al commit
git push origin master
//-----------------------------------------------------------------------------------------------
3. Manejo de Ramas 
PARA CREAR RAMAS
git branch 'NOMBRE'

CAMBIAR DE RAMAS
git checkout 'NOMBRE'

CAMBIAR NOMBRE DE LA RAMA
git branch -m 'NOMBRE VIEJO' 'NOMBRE NUEVO'

CREAR Y CAMBIAR RAMA
git checkout -b 'NOMBRE'

FUSIONAR RAMA A LA MASTER
git merge 'NOMBRE DE LA RAMA'

BORRAR RAMA
git branch -d 'NOMBRE'
//-----------------------------------------------------------------------------------------------
4. PARA CLONAR REPOSITORIO
git clone https:... //va el link

5. SUBIR PARTE
git add .
git commit -m "MENSAJE"
git push origin "NOMBRE DE LA RAMA"
//-----------------------------------------------------------------------------------------------
