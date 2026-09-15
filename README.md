# DANTE CECILIO SIFUENTES MARTINEZ.

# MATRICULA: 2630276.

## NOMBRE DE LA PRACTICA: Creación y sincronización de repositorios con Git y GitHub.

* Objetivo: Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos:

Repositorio local → GitHub
GitHub → Repositorio local.
* Comandos utilizados:

|COMANDO|FUNCION|
|---|---|
|cd ~|Regresa a la carpeta principal del usuario.|
|mkdir|Crea una carpeta nueva.|
|cd|Permite entrar o cambiar de carpeta.|
|git init|Inicializa un repositorio de Git en la carpeta actual.|
|git --version|Muestra la versión de Git instalada.|
|git branch -M main|Cambia el nombre de la rama actual a main.|
|git status|Muestra el estado actual del repositorio.|
|git add -A|Agrega todos los cambios al área de preparación para realizar un commit.|
|git config --global user.name|Configura el nombre de usuario que Git utilizará en los commits.|
|git config --global user.email|Configura el correo electrónico que Git utilizará en los commits.|
|git commit -m|Guarda los cambios preparados en el repositorio con un mensaje.|
|git log|Muestra el historial de commits del repositorio.|
|git remote add origin|Conecta el repositorio local con un repositorio remoto.|
|git remote -v|Muestra las direcciones de los repositorios remotos configurado|
|git pull origin main|Descarga y combina los cambios de la rama main del repositorio remoto.|

* ¿Cómo se creó el repositorio local?

R= Primero hice una carpeta con el comando mkdir y después entré a ella usando cd. Luego utilicé git init para convertir esa carpeta en un repositorio de Git. También configuré mi nombre y correo para que Git pudiera identificar mis cambios.

* ¿Cómo se vinculó el repositorio local con GitHub?

R= Después creé un repositorio en GitHub y lo conecté con el que tenía en mi computadora usando git remote add origin. Para comprobar que se había conectado correctamente utilicé git remote -v.

* Explicación de la sincronización Local → GitHub

R= Cuando quería pasar mis archivos de la computadora a GitHub, primero usé git add -A para agregar los cambios. Después hice un commit con git commit -m y finalmente utilicé git push -u origin main para subir los cambios a GitHub.

* Explicación de la sincronización GitHub → Local

R= Cuando hice un cambio directamente desde GitHub, utilicé git pull origin main desde PowerShell. Este comando sirve para descargar los cambios de GitHub y actualizar mi repositorio local con esos cambios.

* Descripción de los archivos contenidos en el repositorio:

README.md: Este es un archivo que nos fue pedido que fueraguardado en nuestro repositorio en github, en este hablamos sobre todo el procedimiento y comandos utilizados para realizar esta actividad

datos.txt: Este archivo fue utilizado para primero dejar un mensaje localmente de la computadora, luego de esto se realizo otro mensaje ahora siendo agregado en github y luego guardarlo para que el mensaje hecho se guarde en el archivo origina para terminar con este archivo se realizo otro mensaje este siendo de nuevp siendo localmente en la computadora

* Conclusion: 

Para decir verdad esta practica esta muy bien hecha y estructurara para que alguien que no tiene mucha experiencia programando pueda hacer algo tan basico como guardar sus archivos en la nube para compartirlos con mas personas o simplemente resguardarlos.

Gracias a esta practica pude poner a prueba los conocimientos adquiridos en clase y reforzar los que no gracias a las instrucciones claras que el docente a agregado.






