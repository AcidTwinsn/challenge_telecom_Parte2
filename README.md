# challenge_telecom_Parte2
Segunda parte del challenge Telecom X

Introducción

Tras realizar un proceso exhaustivo de limpieza y preparación de datos, se trabajó con un dataset de 7,267 clientes y 21 características, con el objetivo de analizar los principales factores que influyen en la cancelación del servicio (churn) dentro del sector de telecomunicaciones.
Con la información depurada, se aplicaron diferentes enfoques de modelado predictivo y análisis exploratorio, lo que permitió no solo comparar el rendimiento de diversos algoritmos de machine learning, sino también identificar variables críticas asociadas a la evasión de clientes.
Entre los modelos evaluados se destacan SVM, Gradient Boosting, Random Forest, Naive Bayes, K-Neighbors y Decision Tree, analizados bajo métricas de rendimiento como Exactitud, Precisión, Recall y F1-Score, así como su eficiencia de entrenamiento y predicción. Adicionalmente, se empleó Regresión Logística con técnicas de balanceo (SMOTE) para un análisis interpretativo de los factores clave que explican la cancelación.

Este enfoque integral permitió obtener una visión completa:

	Comparación de desempeño de modelos predictivos

	Identificación de variables determinantes en la cancelación

	Recomendaciones estratégicas para la retención de clientes

INSTALACION DEL PROYECTO
Para clonar el proyecto o descargar los archivos, realizar las siguientes acciones.
- Descargar el instalador de la herramienta Git desde el siguiente enlace https://git-scm.com/downloads
- Eligir el instalador de acuerdo con su sistema operativo.
- Instalar el componente.
- Crear un directorio en su sistema de archivos para alojar el proyecto.
- Abrir una terminal del sistema, dirigirse al directorio creado en el paso anterior y ejecutar el comando siguiente.
  cd "Ruta_Directorio" 
  Ejemplo: 
  cd "C:\Repositorios\TelecomX"
- Una vez que se encuentre en el directorio, ejecutar el siguiente comando para descargar el proyecto o los archivos.
  git clone https://github.com/acidTwinss/TelecomX.git
- Verificar en el directorio que se hayan descargado los archivos del proyecto de manera correcta.

ESTRUCTURA DEL PROYECTO
challenge_telecom_Parte2/
├── TelecomX_Analisis.ipynb        # Notebook principal con todos los pasos realizados en el análisis
├── Recursos/
│   └── TelecomX_Limpio.csv         # Datos limpios despues de analizarlos en el proyecto anterior Telecom X
├── Informe/
│   └── Informe_Telecom_parte2.pdf       # Informe completo como resultado del análisis y conclusiones del autor
├── README.md                      # Archivo de texto que proporciona información esencial sobre el proyecto.

INSTALACION DE DEPENDENCIAS NECESARIAS PARA EJECUTAR EL PROYECTO.
- Abrir la página de Google Colab, en el navegador de su preferencia, desde el siguiente enlace https://colab.research.google.com/
- Una vez que haya ingresado al sitio, aparecerá un menú con opciones para importar el archivo del proyecto.
- Dar clic en el menú Subir y arrastrar el archivo TelecomX_LATAM.ipynb

Si es la primera vez que abre el archivo, se deben ejecutar los siguientes comandos.
- Instalación de la biblioteca Pandas.
  pip install pandas 

USO:
Para obtener los resultados y gráficas generadas en el análisis, realizar el siguiente paso:
- Ir al menú Entorno de Ejecución y dar clic en la opción Ejecutar todas.

CONTRIBUCIÓN:
Este análisis fue desarrollado como una iniciativa de análisis exploratorio y mejora de retención para compañías de telecomunicaciones. 
Si deseas aportar con mejoras al modelo predictivo o visualizaciones adicionales, puedes contactarme y conectar conmigo vía correo electrónico o LinkdIn.
📧 nxchavarria@gmail.com


Así mismo, si lo deseas puedes descargar el proyecto desde GitHub y realizar una solicitud de pull request, mediante los siguientes pasos.
-1.- Realicemos un fork del repositorio
Realiza un fork del repositorio haciendo un clic en el botón fork de la parte superior de la página. Esto creará una instancia del repositorio completo en tu cuenta.

-2.- Clona el repositorio
Una vez que el repositorio esté en tu cuenta, clónalo a tu computador para trabajarlo localmente.
Para clonarlo, has clic en el botón "Code" y copia el link.
Abre la terminal y ejecuta el siguiente comando. Esto clonará el repositorio localmente, en caso de que aun no lo hayas descargado.
git clone https://github.com/acidTwinss/TelecomX.git
Ahora hemos configurado una copia de la rama maestra desde el repositorio principal del proyecto en línea.
Debemos ir al repositorio clonado ejecutando el siguiente comando:
cd [NOMBRE DEL REPOSITORIO]

-3.- Crea una rama
Es una buena práctica crear una rama (branch) nueva cuando trabajas con repositorios, ya sea que se trate de un proyecto pequeño o estés contribuyendo en un equipo de trabajo.
El nombre de la rama debe ser breve y debe reflejar el trabajo que estamos haciendo.
Ahora crea una rama usando el comando git checkout:
git checkout -b [Nombre de la Rama]

-4.- Realiza cambios y confírmalos
Has cambios esenciales al proyecto y guárdalos.
Luego ejecuta git status , y verás los cambios.
Agrega tus cambios a la rama recién creada usando el comando git add:
git add .
Ahora confirma esos cambios utilizando el comando git commit:
git commit -m "Adding an article to week 02 of articles of the week"

-5.- Envía los cambios a GitHub
Para enviar los cambios a GitHub, debemos identificar el nombre del repositorio remoto.
git remote
remote
Para este repositorio el nombre es "origin".
Luego de identificar el nombre podemos enviar en forma segura los cambios a GitHub.
git push origin [Nombre de la Rama]

-6.- Crea un pull request
Ve a tu repositorio en GitHub y verás un botón llamado "Pull request", has clic en él.
Por favor, provee todos los detalles necesarios de lo que has hecho (puedes referenciar problemas utilizando "#"). Ahora, envía el pull request.
¡Felicitaciones! Has hecho tu primer pull request.
