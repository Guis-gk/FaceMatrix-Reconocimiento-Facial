# FaceMatrix: Sistema de Reconocimiento Facial

Proyecto académico para el curso de **Cálculo y Álgebra Lineal** de la Escuela Profesional de Ingeniería de Inteligencia Artificial.
Proyecto de reconocimiento facial usando PCA, Eigenfaces y similitud coseno

## 📌 Descripción

Este proyecto demuestra la aplicación de conceptos matemáticos fundamentales en un sistema de reconocimiento facial, desde el enfoque clásico de Eigenfaces hasta conceptos modernos como el margen angular (ArcFace). La demostración práctica está organizada en niveles progresivos que permiten comprender paso a paso la matemática detrás del reconocimiento facial.

## 📚 Conceptos matemáticos abordados

| **Área** | **Conceptos** |
|----------|---------------|
| Álgebra lineal | Espacios vectoriales, matrices, valores y vectores propios, PCA |
| Estadística | Varianza, matriz de covarianza |
| Cálculo | Gradiente descendente, retropropagación, regla de la cadena |
| Geometría | Similitud coseno, hiperesfera unitaria |

## 🧪 Demostración práctica (PoC)

El notebook está organizado en 6 niveles:

| **Nivel** | **Concepto** | **Descripción** |
|-----------|--------------|-----------------|
| 1.1 | PCA en 2D | Datos sintéticos, centrado, covarianza, autovalores |
| 1.2 | Similitud coseno en 3D | Vectores normalizados, hiperesfera unitaria |
| 2.1 | Eigenfaces | Dataset Olivetti Faces, cara promedio, proyección |
| 2.2 | Comparación de distancias | Euclidiana vs coseno, efecto de iluminación |
| 3.1 | Gradiente descendente | Optimización de función simple |
| 3.2 | Margen angular | ArcFace didáctico, separación de clases |

## 🚀 Mejoras implementadas

| Mejora | Descripción |
|--------|-------------|
| SVD dispersa | Comparación de rendimiento entre PCA clásico y SVD dispersa |
| Ampliación de dataset | Aumento del número de imágenes de entrenamiento |
| Detección facial | Integración de OpenCV para localización de rostros |
| Interpretabilidad | Visualización de pesos por persona mediante boxplots |

## 🛠️ Requisitos

```bash
pip install numpy matplotlib scikit-learn
pip install numpy matplotlib scikit-learn opencv-python-headless
