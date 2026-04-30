# CA0305 - Herramientas de Ciencia de Datos II
## Proyecto Grupal

![Python](https://img.shields.io/badge/Python-3.12.2-blue?logo=python)
![Anaconda](https://img.shields.io/badge/Anaconda-ML150-green?logo=anaconda)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 📋 Descripción

Repositorio del grupo para el proyecto del curso CA0305 - Herramientas de Ciencia de Datos II. Este proyecto cubre el desarrollo del módulo de Prerequisitos y Tensores de PaperCode.

---

## 👥 Integrantes

- Sebastián Calderón Segura
- Amy Chen Wu
- Luis Diego Elizondo Fennell
- Santiago Paniagua Chavarría
- Andrés Zúñiga

---

## 🗂️ Estructura del Proyecto

```
CA0305-Bitacora1/
│
├── src/
│   └── py/
│       └── prerequisitos_tensores.ipynb   # Notebook principal
│
├── modelos/                               # Modelos entrenados
│
├── datos/
│   ├── entradas/                          # Datos crudos de entrada
│   ├── intermedios/                       # Datos procesados
│   └── salidas/                           # Resultados finales
│
├── ambiente/
│   └── ml150_environment.yml             # Ambiente Anaconda exportado
│
├── docs/                                  # Documentación adicional
│
├── .gitignore
└── README.md
```

---

## ⚙️ Configuración del Ambiente

### Requisitos previos
- [Anaconda](https://www.anaconda.com/download) instalado
- [Git](https://git-scm.com/) instalado

### Clonar el repositorio

```bash
git clone https://github.com/usuario/CA0305---Proyecto-grupal.git
cd CA0305---Proyecto-grupal
```

### Crear y activar el ambiente ML150

```bash
conda env create -f ambiente/ml150_environment.yml
conda activate ML150
```

### Abrir el notebook

```bash
jupyter notebook src/py/prerequisitos_tensores.ipynb
```

> ⚠️ Asegúrate de que el kernel del notebook esté configurado como **ML150** antes de ejecutar.

---

## 📓 Contenido del Notebook

El notebook `prerequisitos_tensores.ipynb` implementa el módulo de Prerequisitos y Tensores de [PaperCode ML150](https://papercode.in/papers/ml150_prerequisites/problems/p10_gradient_sum), cubriendo los siguientes problemas:

| #   | Problema                                    |
| --- | ------------------------------------------- |
| 1   | Tensor Broadcasting Basics                  |
| 2   | Matrix Multiplication — Naive vs Vectorized |
| 3   | Element-wise Operations                     |
| 4   | Tensor Reshaping & Transposing              |
| 5   | Reduction Operations                        |
| 6   | Vector Norms (L1, L2)                       |
| 7   | Dot Product & Cross Product                 |
| 8   | Einstein Summation (einsum) Basics          |
| 9   | Advanced Einsum (Batch MatMul)              |
| 10  | Gradient of Sum                             |
| 11  | Gradient of Matrix Multiplication           |
| 12  | One-Hot Encoding                            |
| 13  | Softmax Implementation (Stable)             |
| 14  | Cross-Entropy Loss (Manual)                 |
| 15  | Numerical Stability (Log-Sum-Exp)           |

Cada problema incluye:
- Implementación en Python con NumPy siguiendo buenas prácticas
- Documentación de la función con descripción, variables y retorno
- Explicación de la fundamentación matemática con palabras propias

---

## 🔀 Flujo de Trabajo Git

Este proyecto sigue la convención de [Conventional Commits](https://www.conventionalcommits.org/).

### Formato de commits

```
tipo: descripción breve
```

| Tipo | Uso |
|------|-----|
| `feat:` | Nueva funcionalidad o sección |
| `fix:` | Corrección de errores |
| `docs:` | Cambios en documentación |
| `chore:` | Configuración, ambiente, estructura |
| `refactor:` | Reestructuración de código |

---

## 📦 Dependencias Principales

| Librería  | Uso                                    |
| --------- | -------------------------------------- |
| `numpy`   | Álgebra lineal y operaciones numéricas |
| `jupyter` | Entorno de desarrollo interactivo      |

---

## 📅 Información del Curso

- **Curso:** CA0305 - Herramientas de Ciencia de Datos II
- **Encargado:** Joshua Cervantes Artavia — joshua.cervantes@ucr.ac.cr
- **Fecha de entrega:** 01-05-2026 — 11:59 p.m.
- **Plataforma de entrega:** Mediación Virtual
