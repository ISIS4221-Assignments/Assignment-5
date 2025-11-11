# ASSIGNMENT-5

Este proyecto implementa la construcción de sistemas de clasificación haciendo uso de arquitecturas encoder y decoder con el objetivo de comparar la diferencia de rendimiento entre estas. Las tareas de clasificación se llevan a cabo sobre los conjuntos de datos 20 Newsgroup y Multi-Domain Sentiment Analysis, con el objetivo de tener tanto clasificación binaria como multiclase. 

## 📁 Estructura del Proyecto

```
.
├── data
│   ├── 20_news_dataset.tar.gz
│   └── multi_domain_sentiment_dataset.tar.gz
├── docs
│   ├── ENUNCIADO.pdf
│   ├── INFORME.odt
│   └── INFORME.pdf
├── LICENSE
├── models
├── README.md
├── requirements.txt
└── src
    ├── decoders.ipynb
    └── encoders.ipynb
```

## 🐍 Requisitos del Sistema

- **Python**: 3.11.9 (recomendado)
- **Sistema Operativo**: Windows, macOS o Linux

## 🚀 Instalación y Configuración

### 1. Clonar el repositorio
```bash
git clone git@github.com:ISIS4221-Assignments/Assignment-5.git
cd ASSIGNMENT-5
```

### 2. Crear entorno virtual
```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
# En Windows:
venv\Scripts\activate

# En macOS/Linux:
source venv/bin/activate
```

### 3. Instalar dependencias
```bash
pip install -r requirements.txt
```

## 📋 Documentación Detallada

- **Código**: Todo el código incluye docstrings detallados
- **Documento**: En la carpeta docs se incluye un informe detallado del proyecto, junto con la respuesta a las preguntas planteadas en el enunciado del mismo