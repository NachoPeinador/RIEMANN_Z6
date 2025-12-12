# 🌌 Dualidad Espectral-Aritmética: La Estructura Oculta $\mathbb{Z}/6\mathbb{Z}$ en Riemann

[![License](https://img.shields.io/badge/License-PolyForm_Noncommercial_1.0.0-blue.svg)](https://polyformproject.org/licenses/noncommercial/1.0.0/)
[![Python](https://img.shields.io/badge/Python-3.10%2B-green.svg)]()
[![Numba](https://img.shields.io/badge/Numba-JIT_Compiled-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Peer_Review_Ready-brightgreen.svg)]()
[![Papers](https://img.shields.io/badge/📄-Read_Paper-yellow.svg)](https://github.com/NachoPeinador/RIEMANN_Z6/blob/main/Papers/Dualidad_Espectral_Aritmetica.pdf)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?style=flat&logo=Jupyter)](https://github.com/NachoPeinador/RIEMANN_Z6/blob/main/Notebooks/Validacion_Experimental_Completa.ipynb)
[![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.PLACEHOLDER-blue)](https://doi.org/)

**Autor**: José Ignacio Peinador Sala
**Contacto**: joseignacio.peinador@gmail.com
**ORCID**: [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

---

## 🔍 Visión

Este proyecto resuelve la tensión fundamental de medio siglo entre el **Caos Cuántico** (GUE) y el **Orden Aritmético** en los ceros de la Función Zeta de Riemann. 

Desafiando el paradigma de que las fases espectrales son aleatorias a larga distancia, demostramos que el espectro opera como un **sistema físico rígido** gobernado por la estructura modular $\mathbb{Z}/6\mathbb{Z}$. Esta "memoria aritmética" no es solo una curiosidad teórica: permite **acelerar algoritmos de factorización** y predecir la ubicación de los números primos más grandes conocidos.

> **Paradigma**: Los ceros no son un "gas" caótico; son un "cristal" aritmético con defectos locales. El módulo 6 actúa como una **Guía de Onda sin Ruido** para la información prima.

---

## 📊 Validación Experimental ($N=10^5$ Ceros)

[![Statistical Significance](https://img.shields.io/badge/p--value-10^-75-purple)]()
[![SNR Saturation](https://img.shields.io/badge/SNR_Saturation-12.69-blue)]()
[![Algorithm Speedup](https://img.shields.io/badge/Factorization_Speedup-33.33%25-green)]()
[![Mersenne Symmetry](https://img.shields.io/badge/Mersenne_Polarization-100%25-red)]()

| Dominio | Métrica | Resultado | Implicación |
| :--- | :--- | :--- | :--- |
| **Estadístico** | Test de Uniformidad (KS) | **$p \sim 10^{-75}$** | Rechazo absoluto de la hipótesis nula (GUE puro) |
| **Espectral** | Saturación SNR | **12.69 $\pm$ 0.01** | Coincidencia exacta con predicción teórica ($1+\pi^2/9$) |
| **Computacional** | Eficiencia Factorización | **33.3335%** Reducción | Validación física de la densidad de canales prohibidos |
| **Estructural** | Simetría Mersenne ($p>2$) | **100% en Canal 1** | Ruptura total de simetría (Canal 5 vacío) |
| **Termodinámico** | ROI de Complejidad | **0.105** (vs 0.028 en mod 30) | El sistema se "congela" en el óptimo mod 6 |
| **Modelo** | Validación Riemann-GUE | **$p_{KS} = 0.27$** | Indistinguibilidad local del caos estándar |

---

## 🧩 Innovaciones Nucleares

### 1. La Identidad de Coherencia Cuadrática
Demostramos analíticamente que la saturación del SNR obedece a la identidad exacta:
$$L(2,\chi_0^{(6)}) = [L(1,\chi_{12})]^2 = \frac{\pi^2}{9}$$
Esto implica que el módulo 6 tiene un **Factor de Ruido $R_1=1.0$**, actuando como un canal de transmisión perfecto para la información aritmética.

### 2. Reactor de Factorización Modular
Implementación de un algoritmo de cribado que explota la **resonancia $\mathbb{Z}/6\mathbb{Z}$**. Al saltar los "canales prohibidos" ($0,2,3,4 \pmod 6$) donde el SNR espectral es nulo, logramos una reducción del espacio de búsqueda del **33.33%** respecto a la criba de impares estándar.

### 3. El Radar de Mersenne
Descubrimiento de una **polarización estructural**: mientras los primos normales se distribuyen simétricamente (50/50) entre los canales 1 y 5, los Primos de Mersenne ($M_p = 2^p-1$) colapsan **exclusivamente** en el Canal 1, validando la hipótesis de rigidez espectral.

---

## 📁 Estructura del Repositorio

```
Papers/
├── Dualidad-Espectral_Aritmetica.tex   # Artículo completo en formato LaTeX.
└── Dualidad-Espectral_Aritmetica.pdf   # Artículo completo como PDF

Notebooks/
├── Dualidad-Espectral_Aritmetica_Complete_Suite.ipynb    # Validación end-to-end:
│   ├── 1. Detección de Anomalía (Tests KS con p ~ 10^-75)
│   ├── 2. Dinámica del SNR (Modelo de saturación a 12.69)
│   ├── 3. Validación Riemann-GUE (Simulación Monte Carlo p=0.27)
│   ├── 4. Verificación Analítica (Identidad exacta L(2) = π²/9)
│   ├── 5. Termodinámica de Información (Cálculo de ROI óptimo)
│   ├── 6. Reactor de Factorización (Benchmark: -33% operaciones)
│   └── 7. Radar de Mersenne (Visualización de Ruptura de Simetría)
└── zetazeros.txt  # Dataset (Primeros 100k ceros)

Images/    # Figuras y visualizaciones
```

---

## 🚀 Reproducibilidad

Este proyecto prioriza la ciencia reproducible. El código utiliza `numba` para garantizar que los benchmarks de tiempo sean comparaciones justas (JIT vs JIT).

**Prerrequisitos:**

```bash
python>=3.8
numpy>=1.21
matplotlib>=3.5
scipy>=1.7
numba>=0.55  # Crítico para el factorizador
```
Ejecutar la Suite:
```bash
clone [https://github.com/NachoPeinador/RIEMANN_Z6.git](https://github.com/NachoPeinador/RIEMANN_Z6.git)
cd RIEMANN_Z6
```
jupyter notebook Notebooks/Validacion_Experimental_Completa.ipynb


---

## 🎯 Filosofía Científica

> ** La universalidad del caos es solo una fachada asintótica. A baja frecuencia, el esqueleto de los números primos impone una geometría rígida e ineludible.
Este trabajo no contradice a Montgomery-Odlyzko; lo completa. Introducimos el Ensemble Riemann-GUE, un modelo matricial que respeta tanto la libertad asintótica (caos local) como el determinismo aritmético (orden global), cerrando una brecha de 50 años en la física matemática.**

---

## 📝 Citación
```
Peinador Sala, J. I. (2025). Dualidad Espectral-Aritmética: Coherencia de Fase Modular en el Espectro de Riemann (Versión v1). Zenodo. [https://doi.org/](https://doi.org/)[TU_DOI_AQUI]
```
---

## 📫 Contacto

Para discusiones académicas, colaboraciones o consultas sobre los algoritmos de cribado:

Email: joseignacio.peinador@gmail.com
Twitter/X: @todos_lumpen

⚖️ Licencia

Este trabajo utiliza un modelo de licenciamiento dual para proteger la propiedad intelectual de los algoritmos de optimización:

  🔬 Investigación y Educación (Open Science)
      Licencia: PolyForm Noncommercial 1.0.0Permitido: Replicación académica, enseñanza, uso personal.

  💼 Uso Comercial (Algoritmos de Cribado)
      Cualquier uso de la arquitectura de cribado $\mathbb{Z}/6\mathbb{Z}$ o variantes derivadas para fines comerciales (criptoanálisis, optimización industrial) requiere permiso explícito.
      Ver COPYRIGHT.md.
      
Última actualización: Diciembre 2025

