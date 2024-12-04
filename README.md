# Machine-Learning-101

## 💻 Proceso de instalación
Vamos a utilizar Python. Lo siguiente probablemente ya lo sepáis si habéis usado `conda` para otros módulos, ¡pero nunca está de más!

Lo primero es instalar [Miniconda](https://docs.anaconda.com/miniconda/install/) .
Yo lo he hecho en Windows con el instalador `.exe`, pero podéis seguir las instrucciones para instalarlo desde PowerShell (Windows)
o desde la terminal de Linux o MacOS.

He incluido un archivo [requirements.txt](requirements.txt).
Haced `git clone` de este repositorio, entrad (`cd`) desde PowerShell/terminal y ejecutad:
```shell
conda create -n KCML python=3.12
conda install --name KCML --file .\requirements.txt
conda activate KCML
```
El nombre `KCML` podéis cambiarlo, es sólo el que le he dado yo.

Por último, ejecutad `jupyter lab`.

## 🎓 Diapositivas

[0. Presentación y requisitos previos](0.%20Presentación%20y%20requisitos%20previos.pdf)

[1. Fundamentos de Machine Learning](1.%20Fundamentos%20de%20Machine%20Learning.pdf)

[2. Regularización](2.%20Regularización.pdf)

[3. Selección de características](3.%20Selección%20de%20características.pdf)

[4. Árboles de decisión](4.%20Árboles%20de%20decisión.pdf)

[5. Bagging y Random Forest](5.%20Bagging%20y%20Random%20Forest.pdf)

[6. Boosted Trees](6.%20Boosted%20Trees.pdf)

[7. SVMs y Métodos Kernel](7.%20SVMs%20y%20Métodos%20Kernel.pdf)

[8. Métricas](8.%20Métricas.pdf)

## 📚 Notebooks
Hace falta tener `utils.py`, `data/` y `figuras/` en el mismo directorio.

[1. Fundamentos de Machine Learning](1.%20Fundamentos%20de%20Machine%20Learning.ipynb)

[2. Regularización](2.%20Regularización.ipynb)

[3. Selección de características](3%20Selección%20de%20características.ipynb)

[3.1 Consejos para la práctica](3.1%20Ayuda%20para%20la%20práctica_%20análisis%20exploratorio.ipynb)

[4. Árboles de decisión](4.%20Árboles%20de%20decisión.ipynb)

[5. Bagging y Random Forest](5.%20Bagging%20y%20Random%20Forest.ipynb)

[6. Boosted Trees](6.%20Boosted%20Trees.ipynb)

[6.1 Boosting - Otras implementaciones](6.1%20Boosting%20-%20Otras%20implementaciones.ipynb)

[7. SVMs y Métodos Kernel](7.%20SVMs%20y%20Métodos%20Kernel.ipynb)

[8. Métricas](8.%20Métricas.ipynb)

[9. Casos prácticos](9.%20Casos%20prácticos.ipynb)

## 📖 Notebooks con soluciones 🕯
[1. Fundamentos de Machine Learning](1.%20Fundamentos%20de%20Machine%20Learning-Soluciones.ipynb)

[2. Regularización](2.%20Regularización-Soluciones.ipynb)

[3. Selección de características](3%20Selección%20de%20características-Soluciones.ipynb)

[3.1 Consejos para la práctica](3.1%20Ayuda%20para%20la%20práctica_%20análisis%20exploratorio-Soluciones.ipynb)

[4. Árboles de decisión](4.%20Árboles%20de%20decisión-Soluciones.ipynb)

[5. Bagging y Random Forest](5.%20Bagging%20y%20Random%20Forest-Soluciones.ipynb)

[6. Boosted Trees](6.%20Boosted%20Trees-Soluciones.ipynb)

[6.1 Boosting - Otras implementaciones](6.1%20Boosting%20-%20Otras%20implementaciones-Soluciones.ipynb)

[7. SVMs y Métodos Kernel](7.%20SVMs%20y%20Métodos%20Kernel-Soluciones.ipynb)


## 👷‍♀️ Proyecto 👷‍♂️
Comprimido en `.zip` [aquí](Proyecto.zip). Contiene el enunciado en pdf y 60MB de datos.
