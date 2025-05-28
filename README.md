# Prediccion-del-precio-del-Whisky-en-Iowa

Este proyecto se dedica a la predicción del precio del whisky en Iowa utilizando análisis exploratorio, limpieza de datos, visualizaciones y modelos de machine learning. Su funcionamiento se centra en dos notebooks principales, que abarcan desde la preparación y análisis de datos hasta la modelación y visualización de resultados.

## Estructura del Proyecto

El repositorio se organiza de la siguiente manera:

```
Prediccion-del-precio-del-Whisky-en-Iowa/
├── LICENSE                                # Licencia del proyecto
├── Proyecto_Mode_IV_Aleja_Pablo_Pablo (1).pdf   # Documento de informe y análisis
├── ProyectoFinalModeIV.html               # Exportación a HTML del notebook final
├── ProyectoFinalModeIV.ipynb              # Notebook con el análisis y modelación principal
├── Punto6.html                            # Exportación a HTML del modelo de predicción
├── Punto6.ipynb                           # Notebook de visualizaciones de la predicción del modelo final
├── Punto6Interfáz1.ipynb                  # Notebook para interfaz o despliegue (alternativa 1)
├── Punto6Interfáz2.ipynb                  # Notebook para interfaz o despliegue (alternativa 2)
├── pyproject.toml                         # Archivo de configuración y dependencias del proyecto
├── README.md                              # Este archivo
└── uv.lock
```  

Cada uno de estos elementos cumple un rol importante:
- **Notebooks (.ipynb):** Contienen la exploración de datos, limpieza, análisis descriptivo, modelación y visualizaciones. Algunos se utilizan para crear interfaces.
- **Archivos HTML (.html):** Son exportaciones de los notebooks para visualización en navegadores.
- **pyproject.toml:** Especifica las dependencias requeridas y la configuración del entorno Python del proyecto.
- **LICENSE:** Define los términos de uso del proyecto.
- **uv.lock:** Bloquea las versiones de las dependencias para garantizar la reproducibilidad.


## Notebooks Principales

- **ProyectoFinalModeIV.ipynb:**  
  Este notebook contiene el análisis completo y la modelación predictiva. Se utilizan técnicas de machine learning para entrenar modelos que estiman el precio del whisky, evaluando métricas como MAE, MSE y MAPE.

- **Punto6.ipynb:**  
  Aquí se lleva a cabo la exploración y limpieza de datos, además de generar visualizaciones que aportan una comprensión profunda de los patrones existentes en la información, paso fundamental para una buena predicción.

## Flujo de Trabajo

1. **Análisis y Preparación de Datos:**  
   Se importan los datos, se realizan procedimientos de limpieza y se efectúan análisis exploratorios que ayudan a identificar la estructura y las tendencias en la información recopilada.

2. **Modelación Predictiva:**  
   Con base en el análisis previo, se construyen y afinan modelos de machine learning para predecir el precio del whisky. Se validan los modelos mediante pruebas estadísticas y evaluaciones de precisión.

3. **Visualización de Resultados:**  
   Los resultados se documentan y se presentan tanto en formato interactivo a través de los notebooks como en archivos HTML exportados, facilitando su análisis y presentación.

## Dependencias y Configuración

La configuración del entorno y las dependencias necesarias se encuentran definidas en el archivo `pyproject.toml`, mientras que `uv.lock` garantiza que el entorno sea reproducible mediante el bloqueo de las versiones utilizadas.

Además, podemos visualizar las dependencias en el siguiente árbol
```

mode4 v0.1.0
├── datetime v5.5
│   ├── pytz v2025.2
│   └── zope-interface v7.2
│       └── setuptools v80.8.0
├── flask v3.1.1
│   ├── blinker v1.9.0
│   ├── click v8.2.1
│   ├── itsdangerous v2.2.0
│   ├── jinja2 v3.1.6
│   │   └── markupsafe v3.0.2
│   ├── markupsafe v3.0.2
│   └── werkzeug v3.1.3
│       └── markupsafe v3.0.2
├── ipywidgets v8.1.7
│   ├── comm v0.2.2
│   │   └── traitlets v5.14.3
│   ├── ipython v9.2.0
│   │   ├── decorator v5.2.1
│   │   ├── ipython-pygments-lexers v1.1.1
│   │   │   └── pygments v2.19.1
│   │   ├── jedi v0.19.2
│   │   │   └── parso v0.8.4
│   │   ├── matplotlib-inline v0.1.7
│   │   │   └── traitlets v5.14.3
│   │   ├── pexpect v4.9.0
│   │   │   └── ptyprocess v0.7.0
│   │   ├── prompt-toolkit v3.0.51
│   │   │   └── wcwidth v0.2.13
│   │   ├── pygments v2.19.1
│   │   ├── stack-data v0.6.3
│   │   │   ├── asttokens v3.0.0
│   │   │   ├── executing v2.2.0
│   │   │   └── pure-eval v0.2.3
│   │   └── traitlets v5.14.3
│   ├── jupyterlab-widgets v3.0.15
│   ├── traitlets v5.14.3
│   └── widgetsnbextension v4.0.14
├── matplotlib v3.10.3
│   ├── contourpy v1.3.2
│   │   └── numpy v2.2.6
│   ├── cycler v0.12.1
│   ├── fonttools v4.58.0
│   ├── kiwisolver v1.4.8
│   ├── numpy v2.2.6
│   ├── packaging v25.0
│   ├── pillow v11.2.1
│   ├── pyparsing v3.2.3
│   └── python-dateutil v2.9.0.post0
│       └── six v1.17.0
├── numpy v2.2.6
├── pandas v2.2.3
│   ├── numpy v2.2.6
│   ├── python-dateutil v2.9.0.post0 (*)
│   ├── pytz v2025.2
│   └── tzdata v2025.2
├── requests v2.32.3
│   ├── certifi v2025.4.26
│   ├── charset-normalizer v3.4.2
│   ├── idna v3.10
│   └── urllib3 v2.4.0
├── scikit-learn v1.6.1
│   ├── joblib v1.5.0
│   ├── numpy v2.2.6
│   ├── scipy v1.15.3
│   │   └── numpy v2.2.6
│   └── threadpoolctl v3.6.0
└── ipykernel v6.29.5 (group: dev)
    ├── comm v0.2.2 (*)
    ├── debugpy v1.8.14
    ├── ipython v9.2.0 (*)
    ├── jupyter-client v8.6.3
    │   ├── jupyter-core v5.7.2
    │   │   ├── platformdirs v4.3.8
    │   │   └── traitlets v5.14.3
    │   ├── python-dateutil v2.9.0.post0 (*)
    │   ├── pyzmq v26.4.0
    │   ├── tornado v6.5
    │   └── traitlets v5.14.3
    ├── jupyter-core v5.7.2 (*)
    ├── matplotlib-inline v0.1.7 (*)
    ├── nest-asyncio v1.6.0
    ├── packaging v25.0
    ├── psutil v7.0.0
    ├── pyzmq v26.4.0
    ├── tornado v6.5
    └── traitlets v5.14.3
```

## Contribuciones y Licencia

- El proyecto se distribuye bajo la licencia especificada en el archivo `LICENSE`.
- Se aceptan contribuciones siguiendo las directrices habituales del repositorio.

## Contacto

Para consultas adicionales o más información, revisa el documento PDF de informe o contacta a los responsables del proyecto.
