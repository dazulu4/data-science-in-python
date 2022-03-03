# data-science-in-python
Data Science Fundamentals in Python

## Instalación de Python sin Anaconda
Con el fin de aprender, vamos a realizar la instalación de los productos sin Anaconda para de esta forma comprender el proceso de instalación en ambientes no developer:

#### Python 3.8
* Realizar la instalación de Python <a href="https://www.python.org/downloads/windows/" target="_blank">3.8.x</a>. Siga el wizzard de instalación y al final verifique que en la variable de ambiente **PATH** se encuentra la rutan *bin* de Python.
* Realizar la instalación de Jupyter Notebook. Abra una consola **CMD** y lance el comando **pip**; si el programa responde proceda con la  instalación:
  * Actualizar la instalación de pip a la última versión:
  ```
  python -m pip install --upgrade pip
  ```
  * Realizar la instalación del componente Notebook:
  ```
  pip install notebook
  ```
  * Realizar la instalación del componente Jupyter:
  ```
  pip install jupyter
  ```
* Valide la instalación anterior lanzando el comando **jupyter notebook** en la consola **CMD**, se debe abrir el navegador por defecto y se debe poder visualizar los archivos del directorio actual.

#### Visual Studio Code (*Opcional*)
* Realizar la instalación de Visual Studio Code *(Opcional)*. Descargue e instale el producto, la url para descarga es la siguiente: <a href="https://code.visualstudio.com/download" target="_blank">code.visualstudio.com</a>.
* Abra el IDE y realice la instalación de los plugins Python que desee. Los recomendados son los siguientes: Python extension for Visual Studio Code, R support for Visual Studio Code, Code Runner (Ejecutor de scripts en cualquier lenguaje).

## Instalación de Python con Anaconda
Ver manual de instalación: <a href="/install-python-R-windows10.pdf" target="_blank">install-python-R-windows10.pdf</a>. Para instalar <a href="https://docs.anaconda.com/anaconda/install/windows/" target="_blank">Anaconda</a>, apoyese en la versión para Python 3.8 o 3.9.

## Creación Variables de Ambiente
Verifica que la variable de ambiente **Path** contenga las rutas correspondiente a los *bin* de Python (o Anaconda) y R. Ejemplo:
```
PATH=%PATH%;D:\Programas\Anaconda3;D:\Programas\Anaconda3\Library\bin;D:\Programas\Anaconda3\Scripts;D:\Programas\R\R-3.5.0\bin\x64
```

## Sincronización del Repositorio GitHub
1. Clona el repositorio:
```
git clone https://github.com/dazulu4/data-science-in-python.git
```
2. Ingresa en el directorio de trabajo
```
cd data-science-in-python
```

## Ejecución de Documentos Jupyter
Sobre el directorio **data-science-in-python** ejecute el comando:
```
jupyter notebook
```
