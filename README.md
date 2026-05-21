| Command | Descripción | Argumentos | Ejemplo | Salida en Terminal |
|---|---|---|---|---|
| `mv` | Sirve para mover archivos entre directorios, aunque también sirve para renombrar archivos. | `archivo1 archivo2` | `mv quierorenombrar.txt renombre.txt` | No sale una respuesta en la terminal; únicamente lo mueve o renombra según se indique. |
| `echo` | Tiene 2 usos: sirve para escribir directamente en la terminal o para llenar el contenido de un `.txt`. | Texto a imprimir o texto + `>` y el archivo destino | `echo "hola mundo"`<br>`echo "nombrar archivos" > nombre.txt` | ```bash\nhola mundo\n``` |
| `pwd` | Muestra la posición actual donde estás ubicado entre los directorios. | Solo `pwd` | `pwd` | ```bash\nsircloudz@pop-os:~$ pwd\n/home/sircloudz\n``` |
| `nano` | Es otra manera de crear archivos y, al hacerlo, te manda al editor GNU Nano para agregar contenido. | `nombre_del_archivo` | `nano holaa.txt` | Abre la interfaz de GNU Nano. Con `Ctrl + S` guardas y con `Ctrl + X` sales. |
| `cat` | Sirve para imprimir el contenido de un archivo en bash. | `archivo` | `cat estearchivoseimprimira.txt` | Aquí se imprimiría el texto contenido en el archivo. |
