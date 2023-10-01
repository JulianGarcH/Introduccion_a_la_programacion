<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 7 


<!-- Su documentación aquí -->



# **¿Qué es Git?**

[git](https://git-scm.com/.)

Git es un sistema de control de versiones de código, que permite a los desarrolladores llevar un registro de los cambios realizados en el código de un proyecto. Con Git, los desarrolladores pueden trabajar de manera colaborativa en un mismo proyecto, mantener diferentes versiones del código, y resolver conflictos de manera eficiente.

Git fue creado en 2005 por Linus Torvalds, el creador del sistema operativo Linux, y se ha convertido en uno de los sistemas de control de versiones más utilizados en el mundo. Con Git, los desarrolladores pueden llevar un registro completo del historial de cambios en el código, revertir a versiones anteriores en caso de ser necesario, y colaborar de manera eficiente con otros desarrolladores en el mismo proyecto.

Git es un software libre y de código abierto, lo que significa que está disponible gratuitamente para todos y que cualquier persona puede contribuir al desarrollo y mejora del software. Además, Git es compatible con una amplia gama de sistemas operativos, incluyendo Windows, MacOS y Linux.

# **¿Qué es GitHub?**

[github](https://github.com/.)

GitHub es una plataforma en línea para alojar y colaborar en proyectos de software. Fue fundada en 2008 y es una de las plataformas más populares para alojar proyectos de código abierto.

En GitHub, los desarrolladores pueden crear y alojar proyectos, colaborar con otros desarrolladores en proyectos existentes, hacer seguimiento a errores y problemas, y compartir y discutir ideas.

GitHub utiliza Git, un sistema de control de versiones de software, para llevar un registro de todos los cambios en los proyectos y permitir a los desarrolladores trabajar juntos en un proyecto sin interferir entre sí.

Además de alojar proyectos de código abierto, GitHub también ofrece planes de pago para equipos y organizaciones que desean alojar proyectos privados y obtener más características avanzadas.

# **Instalación de Git en diferentes sistemas operativos**

Para instalar Git en diferentes sistemas operativos, puedes seguir los siguientes pasos:

En Windows: Descarga el instalador de Git desde el sitio web oficial de Git (https://git-scm.com/download/win) y sigue las instrucciones del instalador.

En macOS: Instala Git utilizando Homebrew (https://brew.sh/) ejecutando el siguiente comando en la terminal: brew install git

En Linux: Utiliza el gestor de paquetes de tu distribución para instalar Git. Por ejemplo, en Ubuntu puedes ejecutar el siguiente comando en la terminal: sudo apt-get install git

# **Conceptos básicos de Git: repositorios, commits, ramas, fusiones, etc.**

- Repositorios: son los lugares donde se almacenan los archivos de un proyecto. Los repositorios pueden ser locales (en tu computadora) o remotos (en un servidor).

- Commits: son los cambios que se realizan en los archivos de un proyecto. Cada commit tiene un mensaje que describe los cambios realizados.

- Ramas: son diferentes versiones del proyecto que se crean a partir de la rama principal (también conocida como rama maestra o master). Las ramas permiten trabajar en diferentes versiones del proyecto de manera independiente.

- Fusiones: son la combinación de dos o más ramas en una sola. Las fusiones permiten incorporar los cambios realizados en diferentes ramas en una sola versión del proyecto.

# **Flujo de trabajo básico de Git**

- Haces cambios en tu código fuente en tu directorio de trabajo.

- Preparas (añades) esos cambios al staging area, es decir, añades los cambios. Esto es lo que Git rastreará para incluirlo en tu próxima confirmación.

- Confirmas los cambios, lo que crea un punto de comprobación en la historia del proyecto y almacena un commit de esos cambios de forma permanente en tu base de datos local.

- (Opcional) Pushes esos commits a un repositorio remoto, como por ejemplo GitHub. Esto comparte tus commits con otros colaboradores y los hace disponibles de forma remota

![imag1ses7](image-44.png)

# **Configuración inicial de Git**
Después de instalar Git, es importante configurarlo antes de usarlo. Para configurar Git, sigue los siguientes pasos:

Abre la terminal (en Windows, utiliza Git Bash) Configura tu nombre de usuario y correo electrónico utilizando los siguientes comandos:

![imag2ses7](image-45.png)

# **Comprobando tu Configuración**

![imag3ses7](image-46.png)

# **El comando git --version**

Se utiliza para verificar qué versión de Git está instalada.

![imag4ses7](image-47.png)


# **El comando git init**

Se utiliza para inicializar un repositorio Git nuevo.

Cuando ejecutas git init en un directorio, Git inicializará un repositorio Git nuevo y oculto en ese directorio. Este repositorio contiene la información de Git necesaria para rastrear cambios en los archivos.

![imag5ses7](image-48.png)


# **El comando git status:**

Para verificar el estado de los archivos en un repositorio Git, puedes usar el comando git status. Mostrará:

- Archivos sin hacer seguimiento (aún no agregados al índice)

- Archivos modificados (archivos que han cambiado pero aún no se han confirmado)

- Archivos preparados (archivos que se han agregado al índice y se confirmarán después)

![imag8ses7](image-49.png)


# **El comando git add:**

Se utiliza para agregar archivos al área de preparación (staging area) en Git. Esta área de preparación es una especie de área intermedia donde Git almacena información sobre los archivos que irán en tu próximo commit.

El uso básico es:

git add 'archivo'

Esto agregará un solo archivo al área de preparación.

También puedes:

- git add . - Agrega todos los archivos nuevos y modificados en el directorio actual

- git add -A - Agrega todos los archivos nuevos, modificados y eliminados

- git add -p - Selecciona de forma interactiva los cambios de archivos para agregar

![imag9ses7](image-50.png)

# **El comando git commit**

Se utiliza para guardar los cambios en el repositorio Git local.

El uso básico es:

git commit -m "mensaje del compromiso"

Esto confirmará todos los cambios que hayan estado preparados (agregados) usando git add. La bandera -m te permite especificar un mensaje de commit entre comillas.

Por ejemplo:

![imag9ses7](image-51.png)

# **El comando git log**

Se utiliza para ver el historial de commits de un repositorio Git. Muestra información como:

- ID del compromiso

- Mensaje del commit

- Autor del commit

- Fecha del commit

El uso básico es:

![imag10ses7](image-52.png)

Esto mostrará todos los commits en el historial, con la información anterior.

Por ejemplo:

![imag11ses7](image-53.png)


También se puede usar opciones para personalizar el formato y filtro de los resultados:

- --pretty=format: Muestra el formato deseado (abreviado, simple, etc.)
- --grep: Filtra los commits que coinciden con una expresión regular
- --author: Filtra por autor
- -n: Mostrar los últimos n commits
- --since, --until: Filtrar commits entre fechas

Por ejemplo:

![imag12ses7](image-54.png)

Se utiliza para mostrar un resumen de una solo línea para cada commit en el historial.

![imag13ses7](image-55.png)


Muestra solo el hash, autor y mensaje para cada commit.


# **El comando git diff**

Se utiliza para mostrar las diferencias entre commits, el código actual ( Working Directory) y el código confirmado (Staging Area).

![imag14ses7](image-56.png)

Esto mostrará las diferencias entre el código actual (sin confirmar) y el código confirmado más reciente. Muestra qué líneas se agregaron y eliminaron.

También puedes ver las diferencias entre:

- Dos confirmaciones: git diff 'commit1' 'commit2'

- El código actual y un commit específico: git diff HEAD 'commit'
Por ejemplo:

![imag15ses7](image-57.png)


# **El comando git checkout:**

El comando git checkout se utiliza para cambiar la rama actual o para restaurar un archivo a un estado anterior.

La sintaxis básica del comando git checkout es:

![imag16ses7](image-58.png)

Donde ref es la referencia que quieres cambiar. La referencia puede ser el nombre de una rama, el hash de un commit o una etiqueta.

Por ejemplo, para cambiar a la rama main, puedes usar el siguiente comando:

![imag17ses7](image-59.png)


Para restaurar el archivo README.md a su estado en el commit con el hash 1234567890, puedes usar el siguiente comando:

![ima18ses7](image-60.png)

El comando git checkout tiene muchas opciones que te permiten controlar cómo se realiza el cambio. Por ejemplo, la opción --patch te permite revisar los cambios antes de que se apliquen a tus archivos.

Aquí hay algunos ejemplos de cómo usar el comando git checkout:

- git checkout main: cambiar a rama main.

- git checkout -b feature: Crea una nueva rama llamada feature y cambia a ella.

- git checkout 1234567890: Cambia al commit con el hash 1234567890.

- git checkout README.md: Restaura el archivo README.md a su estado en el último commit.

- git checkout --patch README.md: Revisa los cambios que se realizarán en el archivo README.md antes de aplicarlos.


# **¿Qué es GitHub?**


GitHub es una plataforma en línea que permite el alojamiento, la colaboración y el control de versiones de proyectos de software. Es ampliamente utilizada por desarrolladores de software y equipos de programación para gestionar el desarrollo y seguimiento de código fuente, realizar colaboraciones en proyectos y facilitar la colaboración en equipo.

Algunas de las características clave de GitHub incluyen:

- Repositorios: Los repositorios son espacios donde se almacena y organiza el código fuente de un proyecto. Cada repositorio puede contener archivos, carpetas, documentación y registros de cambios.

- Control de Versiones: GitHub proporciona herramientas para realizar un seguimiento de los cambios en el código a lo largo del tiempo. Los desarrolladores pueden crear "commits" para registrar cambios específicos en el código, lo que facilita el rastreo y la reversión de modificaciones.

- Colaboración: Varios desarrolladores pueden trabajar juntos en un proyecto alojado en GitHub. Pueden colaborar de manera simultánea, realizar revisiones de código, sugerir cambios y fusionar contribuciones.

- Ramificaciones (Branches): Los desarrolladores pueden crear ramificaciones separadas del código principal para trabajar en nuevas características o solucionar problemas sin afectar la versión estable del proyecto. Luego, estas ramas pueden fusionarse nuevamente en el código principal.

- Solicitudes de extracción (Pull Requests): Una solicitud de extracción es una forma de proponer cambios al código de un repositorio. Los desarrolladores pueden crear una solicitud de extracción para que otros revisen y aprueben sus cambios antes de que se fusionen en el proyecto principal.

- Wikis y Documentación: Los repositorios de GitHub pueden contener documentación en forma de wikis, archivos Markdown u otros formatos, lo que facilita la creación y el acceso a información importante sobre el proyecto.

- Integración con Herramientas: GitHub se integra con muchas otras herramientas y servicios populares de desarrollo, como servicios de integración continua, sistemas de automatización, sistemas de prueba y despliegue, y más.

# **Crear un repositorio en GitHub**

- Dirígete a la página de inicio de GitHub y crea una cuenta si aún no tienes una.

- Una vez que hayas iniciado sesión, haz clic en el botón "Crear un repositorio".

- En la ventana de creación de repositorios, da un nombre a tu repositorio y selecciona si quieres que sea público o privado.

- Una vez que hayas terminado, haz clic en el botón "Crear repositorio".

[tutorial](https://firebasestorage.googleapis.com/v0/b/cesde-7fe22.appspot.com/o/NTPS4-1.gif?alt=media&token=ff3182ea-b684-4dfd-bc05-290cada54c9c)

# **Crear un nuevo repositorio en la línea de comandos**

![img19ses7](image-61.png)


**Explicación**

echo "# proyecto1" >> README.md: Este comando crea un archivo llamado README.md en el directorio actual y agrega la línea "# proyecto1" al archivo. El >> se utiliza para redirigir la salida y anexar el contenido al archivo. Esto es comúnmente utilizado para crear un archivo de README que describa el proyecto.

git init: Inicializa un nuevo repositorio Git en el directorio actual. Esto crea un subdirectorio oculto llamado .git que contiene toda la información necesaria para rastrear los cambios en el proyecto.

git add README.md: Añade el archivo README.md al área de preparación de Git. Esto significa que Git comenzará a rastrear los cambios en este archivo.

git commit -m "first commit": Crea un nuevo commit (instantánea de los cambios) en el repositorio. El mensaje -m se utiliza para proporcionar una descripción breve del commit. En este caso, se está creando el primer commit con el mensaje "first commit".

git branch -M main: Cambia el nombre de la rama predeterminada de master a main. GitHub ha estado promoviendo el uso de la terminología más inclusiva y, por lo tanto, este comando se utiliza para actualizar el nombre de la rama principal.

git remote add origin https://github.com/xxxxxxx/xxxxx.git: Conecta el repositorio local al repositorio remoto en GitHub. origin es el nombre convencional del control remoto. La URL proporcionada es la ubicación del repositorio remoto.

git push -u origin main: Sube los cambios locales al repositorio remoto en GitHub. El -u establece la rama local main para que haga un seguimiento de la rama remota main en el repositorio remoto. Después de este comando, los cambios y commits locales se copiarán en el repositorio remoto.





