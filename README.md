/*Git Book. Recomienda leer al menos los primeros 3 capítulos del libro Git Book.*/

https://git-scm.com/book/es/v1




/*Ir al directorio:*/

ls															//Listar los documentos que hay en el directorio donde estamos
cd (nombre_directorio)										//Entrar en un directorio
browser-sync start --server --directory --files "*"			//Permitir la actualización automática de local a navegador




/*Github*/

														//Crear el nuevo repositorio en servidor. Dejarlo público.
git clone https://github.com/amayaizcue/coursera.git	//Clonar el nuevo repositorio a local
git status												//Comprobrar en que branch estamos ("branch master", "gh-pages",…)
git checkout gh-pages									//Pasar de "branch master" a "gh-pages"
git pull												//Bajarme la última versión del servidor a local
git add *												//Asociar mis cambios con local
git commit -m "Mensaje"									//Subir cambios a local
git push												//Subir repository local a web
browser-sync start --server --directory --files "*" 	//Permitir la actualización automática de local a navegador




/*Resources for asking questions*/

http://stackoverflow.com/		//Stackoverflow -> foro para desarrolladores

https://jsfiddle.net/			//jsfiddle -> editor online donde otros desarrolladores pueden hacer "fork" y hacer cambios a mi
								//código -> Escribir el html, escribir el css, "run", "save", "update"

http://codepen.io/				//codepen -> foro gigante donde existen muchísimos ejemplos de webs. "+New pen", escribir
								//"html" (lo vemos justo debajo sin necesidad de actualizar), "css" (vemos los cambios
								//automáticamente). Lo mejor: en la parte inferior existe "console":
								//var x="Hello Coursera!";
								//undefined -> resultado
								//console.log(x);
								//"Hello Coursera!" -> resultado
								//save y copiar url en una nueva pestaña
								//Se recomienda darse de alta.

https://css-tricks.com/			//css-tricks -> info sobre css
