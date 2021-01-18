# Lista de Comandos 
1. PARA INICIAR REPOSITORIO
    * git init                                         //crea repositorio
    * git remote add origin https:....                 //va el link
    * git clone https:... //va el link
//-----------------------------------------------------------------------------------------------\
2. subir el proyecto
    * git add .
    * git reset .                                       //deshace los archivos incluidos en el ADD
    * git commit -m "'mensaje'"
    * git commit --amend 		                        //editar el ultimo commit (press 'i', 'ESC, :, wq!')
    * git checkout -- . 		                        //vuelve a la version anterior al commit
    * git push origin master
//-----------------------------------------------------------------------------------------------\
3. Manejo de Ramas 
    * git branch 'NOMBRE'                               //PARA CREAR RAMAS
    * git checkout 'NOMBRE'                             //CAMBIAR DE RAMAS
    * git branch -m 'NOMBRE VIEJO' 'NOMBRE NUEVO'       //CAMBIAR NOMBRE DE LA RAMA
    * git checkout -b 'NOMBRE'                          //CREAR Y CAMBIAR RAMA
    * git merge 'NOMBRE DE LA RAMA'                     //FUSIONAR RAMA A LA MASTER
    * git branch -d 'NOMBRE'                            //BORRAR RAMA
//-----------------------------------------------------------------------------------------------\
4. SUBIR PARTE
    * git add .
    * git commit -m "MENSAJE"
    * git push origin "NOMBRE DE LA RAMA"
//-----------------------------------------------------------------------------------------------\

Ver mas:\
https:\
<confluence.atlassian.com/bitbucketserver/markdown-syntax-guide-776639995.html\>