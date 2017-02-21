/*Git Book. Recomienda leer al menos los primeros 3 capítulos del libro Git Book.*/
https://git-scm.com/book/es/v1


/*Ir al directorio:*/
ls							//Listar los documentos que hay en el directorio donde estamos
cd (nombre_directorio)					//Entrar en un directorio
browser-sync start --server --directory --files "*"	//Permitir la actualización automática de local a navegador


/*Github*/
							//Crear el nuevo repositorio en servidor. Dejarlo público.
git clone https://github.com/amayaizcue/coursera.git	//Clonar el nuevo repositorio a local
git status						//Comprobrar en que branch estamos ("branch master", "gh-pages",…)
git checkout gh-pages					//Pasar de "branch master" a "gh-pages"
git pull						//Bajarme la última versión del servidor a local
git add *						//Asociar mis cambios con local
git commit -m "Mensaje"					//Subir cambios a local
git push						//Subir repository local a web
browser-sync start --server --directory --files "*" //Permitir la actualización automática de local a navegador 
