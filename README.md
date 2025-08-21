# 🛰️ Teledetección: Imágenes Satelitales, Drones y Machine Learning Aplicado a Agricultura Digital

*Transforma datos espaciales remotos en decisiones inteligentes* 🌱

> **📚 Curso dictado en la Universidad de Magdalena** para los programas de **Maestría y Doctorado en Ingeniería** en alianza con **AGROSAVIA - Colombia** 🇨🇴

Este repositorio contiene los materiales, ejemplos y recursos del curso especializado en **Teledetección** con énfasis en aplicaciones agrícolas y uso de inteligencia artificial.

## 🎯 Descripción

Curso de formación avanzada en teledetección óptica y radar, con énfasis en imágenes multiespectrales y algoritmos de machine learning. Integra radiometría de campo, preprocesamiento digital y clasificación supervisada para implementar soluciones reales en agricultura de precisión usando herramientas de software libre.

**Entidad organizadora:** AGROSAVIA – Centro de Investigación Turipaná

## 🎓 Objetivos

### Objetivo General
Formar participantes en fundamentos, técnicas y aplicaciones de teledetección mediante sensores remotos, con énfasis en plataformas satelitales y drones, procesamiento digital de imágenes y aprendizaje automático aplicado al monitoreo de variables biofísicas.

### Objetivos Específicos
- 🔬 Explicar principios físicos de la teledetección y la interacción electromagnética
- 🛰️ Identificar características técnicas de plataformas Sentinel, Landsat, MODIS y drones
- 📊 Aplicar conceptos de resolución espacial, espectral, temporal y radiométrica
- 🔧 Realizar preprocesamiento de imágenes (correcciones radiométricas, atmosféricas, geométricas)
- 🌿 Comprender índices espectrales (NDVI, NDRE, SAVI) y su relación con cobertura vegetal
- 🤖 Aplicar técnicas de machine learning (SVM, Random Forest, XGBoost)
- 📡 Diferenciar sensores pasivos (ópticos, térmicos, hiperespectrales) de activos (radar SAR, LIDAR)

## 📚 Módulos del Curso (36 horas)

### Módulo 1: Fundamentos de Teledetección (6 horas)
- Definición y alcance de la teledetección (óptica y radar)
- Tipos de sensores: pasivos y activos
- Plataformas: satélites, drones, aviones, sensores proximales
- Interacción de la radiación electromagnética con la materia
- Firmas espectrales y radiometría proximal

### Módulo 2: Imágenes Pasivas (18 horas)
- Sensores ópticos multiespectrales e hiperespectrales
- Plataformas Sentinel-2, Landsat 8/9, MODIS, drones (DJI, Micasense)
- Índices espectrales: NDVI, NDRE, SAVI, NDWI
- Radiometría de campo con espectrómetros
- Procesamiento con QGIS, SNAP, Google Earth Engine, Python

### Módulo 3: Imágenes Activas y Machine Learning (12 horas)
- Radar SAR: bandas L, C, X y polarización VV, VH, HV, HH
- LIDAR: principios y aplicaciones topográficas
- Algoritmos ML: SVM, Random Forest, XGBoost
- Clasificación supervisada y no supervisada
- Procesamiento con Google Earth Engine y Python

## 🗂️ Estructura del Repositorio

```
📁 Teledeteccion-Curso/
├── 📁 codigo/                    # 🐍 Notebooks Python y scripts de análisis
│   ├── NDVI_Satellite.ipynb
│   ├── ClasificadorRF*.ipynb
│   ├── XGBoost*.ipynb
│   └── 13-Segmentación_Kmeans/
├── 📁 datasets/                  # 🗃️ Datos satelitales y ejemplos
│   ├── NDVI_Sentinel2.tif
│   ├── VH.tif, VV.tif
│   └── Ejemplo_FirmasEspectrales/
├── 📁 QGIS_SNAP/                # 🗺️ Proyectos QGIS
├── 📁 documentos/               # 📄 Material teórico del curso
├── 📁 datasheet-drones/         # 🚁 Especificaciones técnicas drones
└── 📁 tutorial-y-aprendizaje/   # 📖 Material de apoyo y tutoriales
```

## 🛠️ Tecnologías y Herramientas

### Software Libre:
- 🐍 **Python**: rasterio, scikit-learn, geopandas, matplotlib
- 🗺️ **QGIS**: Análisis geoespacial
- 📡 **SNAP**: Procesamiento imágenes Sentinel
- 🌍 **Google Earth Engine**: Análisis en la nube
- ☁️ **Google Colab**: Ejecución de notebooks

### Plataformas Satelitales:
- 🛰️ Sentinel-1/2 (ESA)
- 🛰️ Landsat 8/9 (NASA/USGS)
- 🛰️ MODIS (NASA)

### Drones Multiespectrales:
- 🚁 DJI Phantom 4 Multiespectral
- 🚁 DJI Mavic 3 Multiespectral  
- 🚁 MicaSense RedEdge-MX

## 🎯 Público Objetivo

- 🔬 **Investigadores** y técnicos en proyectos agroambientales
- 🎓 **Estudiantes y profesionales** de ingeniería, agronomía, geografía, física, biología
- 🌾 **Productores agrícolas** interesados en monitoreo remoto
- 👥 **Público general** que desee competencias básicas en teledetección

## 📋 Requisitos Previos

- 💻 Manejo básico de software informático
- 🐍 Deseable: conocimientos básicos de Python
- 🗺️ Deseable: conocimientos de SIG (QGIS, SNAP, Google Earth Engine)

## 🚀 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/claumiseimbett1/teledeteccion-curso.git
   ```

2. **Instala las dependencias de Python:**
   ```bash
   pip install numpy matplotlib rasterio scikit-learn geopandas
   ```

3. **Abre los notebooks en Jupyter o Google Colab**

4. **Sigue las instrucciones de cada módulo**

## 👩‍🎓 Instructora

**Claudia Milena Serpa Imbett, PhD.**
- 🎓 Posdoctoral MINCIENCIAS
- 🏫 Docente Universitaria UNISINU – Montería
- 🔗 [claumiseimbett1](https://github.com/claumiseimbett1)

## 🏢 Instituciones

### 🎓 Universidad de Magdalena
Programas de **Maestría y Doctorado en Ingeniería**

### 🌱 AGROSAVIA
Centro de Investigación Turipaná - Líder en innovación agrícola en Colombia

## 📜 Acerca del Curso

Este curso se enmarca en los programas de formación e innovación en agricultura digital, sensado remoto y tecnologías emergentes aplicadas al monitoreo agrícola, en el contexto de la apropiación de tecnologías 4.0.

---

🌟 **¡Transforma datos espaciales remotos en decisiones inteligentes!** 🌟

*Impulsamos la transferencia de conocimiento orientada a la sostenibilidad de los sistemas productivos mediante la integración de herramientas tecnológicas avanzadas para su monitoreo y gestión remota.*
