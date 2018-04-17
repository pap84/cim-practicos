### Imágenes radiológicas en el ámbito clínico - 2018 - FaMAF - UNC

# Análisis y Visualización de Imágenes


## Requisitos de Instalación [^1](Tomado del curso de la Diplomatura de Datos de FAMAF:)

Hay dos manejadores principales de paquetes para Python: conda y pip. Para este curso les recomendamos usar conda, ya que funciona también como un manejador de entornos (como virtualenv). Además de ello, las notebooks estarán escritas para Python 3.5.

Para configurar el entorno de trabajo con jupyter y todas las herramientas necesarias para este curso (en Linux [2^] ), pueden ejecutar los siguientes comandos:

```
$ wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ bash Miniconda3-latest-Linux-x86_64.sh
$ conda create --name imagenes-ayv python=3.5 numpy scipy jupyter nb_conda
$ source activate imagenes-ayv
```

Una vez que hayan activado el environment y clonado este repositorio, en este mismo directorio pueden ejecutar jupyter para abrir las notebooks:

```
$ jupyter notebook
```

Si prefieren utilizar otro manejador de paquetes distinto de conda, las librerías que utilizaremos son:

* matplotlib
* numpy
* pandas
* seaborn


<!-- ## Datasets

Los datasets con los que estaremos trabajando se encuentran en https://cs.famaf.unc.edu.ar/~mteruel/datasets/diplodatos. Son pequeños, pero si quieren pueden llevarlos previamente descargados. -->

[^1] Tomado del curso de la Diplomatura de Datos de FAMAF: https://github.com/DiploDatos/AnalisisyVisualizacion/blob/master/README.md

[^2] En MacOS o Windows hay que tener en cuenta que en el presente texto se descarga el instalador para Linuz de `conda`.
