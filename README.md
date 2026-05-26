# Neural ODEs sobre Datos Biologicos
**Analisis Numerico | Universidad Nacional de Colombia**  
Prof. Carlos Manuel Orrego Franco  
Generado: 2026-05-27  

---

## Integrantes
- Andrés Sebastián Guevara Ortiz
- Thomas Jaramillo Aguirre

## Dataset
**COVID-19 JHU (nuevos casos diarios)**  
- Trayectorias: 178  
- Pasos de tiempo: 400  
- Variables: Nuevos casos (norm.)  

## Resultados (100% de observaciones)
| Modelo | RMSE Rec | RMSE Ext | Params | Tiempo |
|--------|----------|----------|--------|--------|
| Metodo Clasico | 0.0000 | nan | 4 | 0.0s |
| Neural ODE | 0.5007 | nan | 3,721 | 1646.5s |
| Latent ODE | 0.5695 | nan | 7,593 | 2083.8s |

## Reproducir
```bash
# Abrir A_notebook_base.ipynb en Google Colab
# Ejecutar todas las celdas en orden desde la Seccion 1
```

## Estructura
```
notebooks/   <- NB01-NB07 + A_notebook_base.ipynb
informe/     <- informe.tex + informe.pdf
evidencia_ia/ <- capturas del chat con la IA
README.md
```
