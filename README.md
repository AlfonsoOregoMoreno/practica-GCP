* Solo están hechas las 3 primeras partes de la práctica. 
* El verdadero fichero del diagrama es "**Diagrama1_GCP___DevOps_bootcamp_keepcoding.drawio.png**". Por alguna razón, github no termina de eliminar los demás que subí, y que no son la versión final.  
* En la VM "**vm-que-provoca-escalado**", en el "home" de "**cpp_alfonso_orego**", hay un script llamado "**provoca-escalado-ab.sh**" al que le pueden pasar params, tal como el propio script indica si se le llama sin params. 
* Dicho Script escribe en la Base de Datos "**google**", un Log de aviso del lanzamiento del script, y queda registrada la fecha/hora del lanzamiento.
* Además, el Script lanza peticiones a la IP que se le indique, usando la aplicación "**Apache Bench**", instalada previamente en la VM "**vm-que-provoca-escalado**". 
