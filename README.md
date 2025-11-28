# Resonancia Espectral y Estructura Modular Z/6Z en la Distribución de los Ceros de la Función Zeta de Riemann

[![License: PolyForm Noncommercial](https://img.shields.io/badge/License-PolyForm_Noncommercial-5D6C89.svg)](LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?style=flat&logo=Jupyter)](Notebooks/)
**Autor:** José Ignacio Peinador Sala  
**Contacto:** [joseignacio.peinador@gmail.com](mailto:joseignacio.peinador@gmail.com)  
**ORCID:** [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

---

## 📜 Resumen Ejecutivo

Este repositorio contiene el código fuente, los experimentos numéricos y el manuscrito de la investigación **"Resonancia Espectral y Estructura Modular Z/6Z"**.

Este trabajo resuelve la aparente paradoja entre la estocasticidad local de los ceros de Riemann (gobernada por el caos cuántico/GUE) y la rigidez aritmética de los números primos. Proponemos y validamos un nuevo marco teórico donde los ceros actúan como un banco de filtros resonantes que, mediante interferencia constructiva, generan la estructura modular $6k \pm 1$ de los primos.

---

## 🚀 Hallazgos Principales

### 1. Teorema de Reconstrucción Modular
Demostramos analítica y numéricamente que el espectro de ceros contiene, codificada holográficamente en sus fases, la prohibición estricta de primos en las clases de residuos $0, 2, 3, 4 \pmod 6$. La suma espectral reconstruye la función de Chebyshev $\psi(x)$ anulando el crecimiento en estos canales prohibidos.

### 2. Resonancia de Fase (SNR 12.65x)
Mediante **espectroscopía logarítmica**, revelamos que las fases de los ceros $\theta_n = \gamma_n \ln p$ no son aleatorias. Los canales primos ($1, 5 \pmod 6$) exhiben una resonancia constructiva masiva con una Relación Señal-Ruido de **12.65 veces** superior al ruido de fondo, validando la existencia de una estructura global rígida.

### 3. Factorización Modular de Alto Rendimiento
Implementamos el motor `CribaModularZ6` utilizando compilación JIT (Numba). Este algoritmo explota la estructura modular para factorizar claves semiprimas de 19 dígitos (límite de 64 bits) en **< 9 segundos**, demostrando la eficiencia computacional del filtrado modular.

---

## 📂 Estructura del Repositorio

* **`Paper/`**: Manuscrito completo en PDF y fuentes LaTeX.
    * `Resonancia_Espectral_Zeta.pdf`: El artículo científico.
* **`Notebooks/`**: Experimentos reproducibles.
    * `Analisis_Espectral_Logaritmico.ipynb`: Validación de la resonancia de fase y cálculo de SNR.
    * `Tomografia_HDR.ipynb`: Generación de los hologramas espectrales.
* **`Code/`**: Implementaciones optimizadas.
    * `criba_modular_jit.py`: Motor de factorización acelerado con Numba.

---

## 💻 Reproducibilidad

El código está escrito en Python y optimizado para cálculo científico.

### Requisitos
* Python 3.8+
* Librerías Críticas: `numpy`, `scipy`, `matplotlib`, `numba`, `tqdm`

### Ejecución del Motor de Factorización
Para probar el algoritmo de factorización modular en su máquina local:

```bash
python Code/criba_modular_jit.py --target 3520732520364809881
```
--

## ✍️ Citación

Si utiliza este software o los hallazgos teóricos en su investigación, por favor cite el artículo unificado:

```bibtex
@article{PeinadorSala2025_Exascale,
  author = {Peinador Sala, José Ignacio},
  title = {El Espectro Modular de $\pi$: Unificación Teórica, Isomorfismo DSP y Validación a Exaescala},
  year = {2025},
  publisher = {Zenodo},
  version = {v1.0},
  doi = {10.5281/zenodo.XXXXXXX}
}
```
---

## 🚀 Apoya la Ciencia Independiente

Este desarrollo es fruto de la investigación independiente. Si la arquitectura te resulta útil o inspiradora:

⭐️ Dale una Estrella: Ayuda a visibilizar el repositorio.

📢 Difunde: Comparte los resultados en redes con el hashtag #ModularPi.

🤝 Colabora: Traducciones y nuevas implementaciones son bienvenidas. Bajo la misma licencia no comercial.

"La simplicidad es la máxima sofisticación." — Leonardo da Vinci

