# projectoneu
Primer proyecto de desarrollo de proyecto IA

El propósito de este proyecto es instruirnos a los estudiantes en la adquisición de habilidades técnicas necesarias para el desarrollo de software. En el marco de este proyecto, deberán utilizar herramientas como GIT, Docker, pruebas unitarias y conceptos de diseño de software.

Además, se aplicará una técnica de explicación denominada Grad-CAM para destacar, mediante un mapa de calor, las áreas relevantes de la imagen de entrada.
rimera parte local:
Uso de la herramienta:
A continuación le explicaremos cómo empezar a utilizarla.

Requerimientos necesarios para el funcionamiento:

Instale Anaconda para Windows siguiendo las siguientes instrucciones: https://docs.anaconda.com/anaconda/install/windows/

Abra Anaconda Prompt y ejecute las siguientes instrucciones:

conda create -n tf tensorflow

conda activate tf

cd UAO-Neumonia

pip install -r requirements.txt

python detector_neumonia.py

Uso de la Interfaz Gráfica:

Ingrese la cédula del paciente en la caja de texto
Presione el botón 'Cargar Imagen', seleccione la imagen del explorador de archivos del computador (Imagenes de prueba en https://drive.google.com/drive/folders/1WOuL0wdVC6aojy8IfssHcqZ4Up14dy0g?usp=drive_link)
Presione el botón 'Predecir' y espere unos segundos hasta que observe los resultados
Presione el botón 'Guardar' para almacenar la información del paciente en un archivo excel con extensión .csv
Presione el botón 'PDF' para descargar un archivo PDF con la información desplegada en la interfaz
Presión el botón 'Borrar' si desea cargar una nueva imagen

Segunda parte
Se crea el docker 
![Pantallazo Proyecto neumonía](https://github.com/user-attachments/assets/8b6531c4-de36-49c2-9e7e-70116788e40c)
Se obtienen los resultados del proyecto
![Diagnóstico médico Neumonia](https://github.com/user-attachments/assets/998f0077-6c06-463a-a5d4-227abbb057d3)
