#Instalación de RVM/Ruby y Git en Mac OS
###Por Eduardo Javier Acuña Ledesma - Asignatura: SYTW

* **Instalación de RVM y Ruby**
	
	Para la correcta instalación de RVM y para que no hayan conflictos con el usuario root, tenemos que realizar los siguientes pasos. En primer lugar, realizamos la instalación de RVM con el siguiente comando:
	
	`$ \curl -sSL https://get.rvm.io | bash -s -- --autolibs=read-fail`
	
	![Instalacion inicial de RVM](https://raw.githubusercontent.com/alu3286/SYTW_tareas_iniciales/gh-pages/images/1.png)
	
	Luego ejecutamos lo siguiente e instalamos la versión 2.0.0:
	
	`$ rvm autolibs disable`
	
	`$ rvm requirements`
	
	`$ rvm install 2.0.0`
	 
	 ![Instalacion final de RVM](https://raw.githubusercontent.com/alu3286/SYTW_tareas_iniciales/gh-pages/images/2.png)
	 
	 Además también instalaremos la versión 1.9.3, y elegiremos por defecto la 2.0.0:
	 
	 `$ rvm install 1.9.3`
	 
	 `$ rvm use 2.0.0`
	 
	  ![Instalacion de otra versión de Ruby](https://raw.githubusercontent.com/alu3286/SYTW_tareas_iniciales/gh-pages/images/3.png)
	  
	   ![Seleccionando una versión de Ruby](https://raw.githubusercontent.com/alu3286/SYTW_tareas_iniciales/gh-pages/images/4.png)
	
	Para comprobar la versión que tenemos que Ruby ejecutamos:
	
	`$ ruby -v`
	

* **Instalación de Git**

	No hizo falta la instalación de git, puesto que previamente estaba instalado. ![Aquí](http://git-scm.com/book/es/Empezando-Instalando-Git) puede consular el manual de instalación de Git.
	Para comprobar la vesión de git ejecutamos: 

	`$ git --version`

	![instalacion de Git](https://raw.githubusercontent.com/alu3286/SYTW_tareas_iniciales/gh-pages/images/5.png)
