En este repositorio vamos a estudiar la librería Numpy para su uso en Machine Learning. Para crear nuestro entorno de desarrollo local, vamos a hacer uso de python en un ambiente virtual, e instalamos los requerimientos:

1. Una vez clonado el repositorio, entramos a la carpeta numpy_wwcode en la terminal:

```bash
cd numpy_wwcode/
```

2.creamos un ambiente virtual y lo activamos:

Mac/Linux:

```python
python3 -m venv <nombre_env>
source <nombre_env>/bin/activate
```

Windows:

```python
python -m venv <nombre_env>
<nombre_env>\Scripts\activate
```

3. Instalamos los requerimientos:

```python
pip install -r requirements.txt
```

4. Iniciamos el servidor de jupyter notebook:

```bash
jupyter notebook
```