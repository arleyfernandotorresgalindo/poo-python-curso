# Programación II - Ciencia de Datos

Este repositorio contiene los materiales, ejercicios y soluciones del curso de **Programación II** de la Universidad Externado de Colombia. El entorno está diseñado para ejecutarse de forma sencilla y rápida utilizando **GitHub Codespaces**.


## 📂 Estructura del Repositorio

La organización de las carpetas sigue el cronograma del microcurrículo del curso:
```
.
├── .devcontainer/          # Configuración de Python 3.13 o 3.12 para Codespaces
├── parcial1/               # Funciones de orden superior y clausuras
│   └── soluciones_p1.py
├── parcial2/               # Generadores, excepciones y recursión
│   └── soluciones_p2.py
├── pandas/                 # Manipulación de datos (Series y DataFrames)
│   └── soluciones_pandas.py
├── poo/                    # Programación Orientada a Objetos
│   └── soluciones_poo.py
├── main_soluciones.ipynb   # Cuaderno de Jupyter para integrar soluciones
└── README.md               # Instrucciones del proyecto
└── requirements.txt

```

## 👉 Indicaciones generales

- Acerca del contenido de las carpetas:
    1. En `soluciones_p1.py` deben aparecer las respuestas del parcial 1. Lo mismo debe ocurrir en `soluciones_p2.py`
    2. En `soluciones_pandas.py` deben aparecer las soluciones a los problemas que se proponen en dicho modulo. Tendra una lista de ejercicios que debe realizar
    3. En `soluciones_poo.py` deberan aparecer algunos ejercicios resueltos sobre POO.
- Acerca del trabajo:
    1. El trabajo debe ser equitativo en todo el desarrollo del repositorio. Cada estudiante debe resolver la mitad de los problemas propuestos en cada modulo. Por ejemplo, en `soluciones_p1.py` cada estudiante debe subir dos soluciones y poner los commit respectivos
    2. Se espera que al hacer una copia o un folk de su repositorio este de manera automatica inicie una versión de python y que instale las librerias de `requirements.txt`. Ese archivo es el mismo que el de este repositorio.
    3. Trabaje como lo considere adecuado. Si cada estudiante quiere iniciar una rama y luego integrar su trabajo puede hacerlo. Si prefieren trabajar en una sola rama de manera lineal puede hacerlo. Al final en su repositorio se revisará la rama del main con algunos test.

## 🚀 Acerca de la estructura del repositorio final

La idea de tener esta estructura de archivos es la de poder llamar las funciones de los modulos en un cuaderno de jupyter de la siguiente forma:

```python
# Importar una función específica del archivo soluciones_p1.py
from parcial1.soluciones_p1 import tu_funcion_de_clausura

# O importar todo el módulo para usarlo con un alias
import parcial1.soluciones_p1 as p1

# Ejemplo de uso:
resultado = p1.tu_funcion_de_clausura(datos)
print(resultado)        

```