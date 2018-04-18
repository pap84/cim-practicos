### Imágenes radiológicas en el ámbito clínico - 2018 - FaMAF - UNC

# Operaciones básicas sobre imágenes


## Requisitos de Instalación <sup>1</sup>

Hay dos manejadores principales de paquetes para Python: conda y pip. Para este curso les recomendamos usar conda, ya que funciona también como un manejador de entornos (como virtualenv). Además de ello, las notebooks estarán escritas para Python 3.5.

Para configurar el entorno de trabajo con jupyter y todas las herramientas necesarias para este curso (en Linux de 64 bits <sup>2</sup> ), pueden ejecutar los siguientes comandos:

```
$ wget https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ bash Miniconda3-latest-Linux-x86_64.sh
$ conda create --name imagenes-ayv python=3.5 numpy scipy jupyter nb_conda seaborn pandas matplotlib pillow
$ source activate imagenes-ayv
```

Una vez que hayan activado el environment y clonado este repositorio, en este mismo directorio pueden ejecutar jupyter para abrir las notebooks:

```
$ jupyter notebook
```

En caso que algún paquete no se encuentre instalado, puede instalarse con el comando:

```
$ conda install <nomre-del-paquete>
```

Si prefieren utilizar otro manejador de paquetes distinto de conda, las librerías que utilizaremos son:

* matplotlib
* numpy
* scipy
* pandas
* seaborn
* [pillow](http://pillow.readthedocs.io/en/3.1.x/handbook/tutorial.html)


<!-- ## Datasets

Los datasets con los que estaremos trabajando se encuentran en https://cs.famaf.unc.edu.ar/~mteruel/datasets/diplodatos. Son pequeños, pero si quieren pueden llevarlos previamente descargados. -->


<sup>1</sup> Tomado del curso de la Diplomatura de Datos de FAMAF: https://github.com/DiploDatos/AnalisisyVisualizacion/blob/master/README.md

<sup>2</sup> En MacOS, Windows o Linux de 32 bits hay que tener en cuenta que en el presente texto se descarga el instalador de `Miniconda3` para Linux de 64 bits.
