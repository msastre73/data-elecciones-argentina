# Data elecciones Argentina 2023
Este proyecto contiene el código por el cual, a partir de la base de datos oficial de las elecciones en Argentina 2023, llegué a los resultados expuestos en [este informe](https://msastre73.github.io/data-elecciones-argentina-web/).

## Reproducir los gráficos
Para reproducir en tu propia computadora los gráficos a los que llegué necesitas:
- Conocimientos en análisis de datos con Python (pandas, np, Jupyter, etc). Conocimientos básicos son suficientes, yo personalmente estoy muy lejos de ser un experto.
- Poder descargar algunos archivos de las fuentes oficiales

Si tienes los requisitos, sigue estos pasos:

### 1. Bifurcar el Repositorio

Para tener tu propia copia del repositorio, haz un "fork":

- Haz clic en el botón "Fork" en la esquina superior derecha de esta página.

### 2. Clonar el Repositorio

Clona tu repositorio bifurcado a tu máquina local:

    git clone https://github.com/[TuUsuario]/data-elecciones-argentina.git
    cd data-elecciones-argentina

Reemplaza `[TuUsuario]` con tu nombre de usuario en GitHub.

### 3. Configurar el Entorno Virtual

Es recomendable utilizar un entorno virtual para gestionar las dependencias:

    python -m venv venv
    source venv/bin/activate  # En Windows usa `venv\Scripts\activate`

### 4. Instalar las Dependencias

Instala todas las dependencias necesarias para el proyecto, incluyendo Jupyter:

    pip install -r requirements.txt

### 5. Descargar Archivos Adicionales

Descarga los archivos listados a continuación y colócalos en el directorio indicado. Estos archivos son necesarios para la correcta ejecución del análisis.
- [Resultados de las Elecciones Generales 2023](https://www.argentina.gob.ar/dine/resultados-electorales/elecciones-2023). Esto va a descargar un ZIP del cual tienes que extraer el archivo `ResultadosElectorales_2023.csv` y colocarlo en el root del proyecto.
- [Resultados de las Elecciones Generales 2019](https://www.argentina.gob.ar/dine/resultados-electorales/elecciones-2019). Esto va a descargar un ZIP del cual tienes que extraer el archivo `ResultadosElectorales.csv`, renombrarlo como `ResultadosElectorales_2019.csv` y colocarlo en el root del proyecto.
- [Resultados de las Elecciones Generales 2015](https://www.argentina.gob.ar/dine/resultados-electorales/elecciones-2015). Esto va a descargar un ZIP del cual tienes que extraer el archivo `ResultadosElectorales.csv`, renombrarlo como `ResultadosElectorales_2015.csv` y colocarlo en el root del proyecto.
- [Shapefile para el mapa de Argentina dividido por provincia](https://datos.gob.ar/dataset/jgm-servicio-normalizacion-datos-geograficos/archivo/jgm_8.26). Esto va a descargar un ZIP del cual tienes que extraer los 5 archivos y colocarlos en una carpate con nombre `shapefiles`

### 6. Ejecutar Jupyter Notebook

Inicia Jupyter Notebook ejecutando:

    jupyter notebook

Esto abrirá Jupyter en tu navegador web predeterminado.

### 7. Abrir y Ejecutar el Notebook

En la interfaz de Jupyter, navega y abre el archivo `Elecciones 2023.ipynb`. Para ejecutar las celdas del notebook:

- Haz clic en una celda para seleccionarla.
- Presiona Shift + Enter para ejecutarla.
- Espera a que finalice la ejecución (el indicador "`*`" desaparecerá).

Repite lo mismo con los archivos `Elecciones 2019.ipynb` y `Elecciones 2015.ipynb` para obtener los gráficos de esos años.

## Contribuciones

Las contribuciones al proyecto son bienvenidas. Mandá un pull request si encontras mejoras o con ideas para agregar. 

Si es algo nuevo, te recomiendo mandarme un mensaje por instagram antes de empezar a trabajar en eso, para asegurarte que es algo que me interesaría agregar al proyecto.

Mi instagram es [@msastre73](https://www.instagram.com/msastre73/)

## Licencia

Este proyecto está bajo la licencia Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC 4.0). Para más detalles, consulta el archivo [LICENSE](LICENSE) en este repositorio o visita [Creative Commons](https://creativecommons.org/licenses/by-nc/4.0/).


