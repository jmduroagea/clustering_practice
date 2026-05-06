# Práctica 2 — Determinación de tipos de estrellas mediante Clustering

## Autores

- **Matias Djukic** — 100504112@alumnos.uc3m.es  
- **José María Duro Agea** — 100522306@alumnos.uc3m.es

## Ejecución

### Google Colab

1. Abrir `practica2.ipynb` en [Google Colab](https://colab.research.google.com/).
2. Subir `stars_data.csv` al entorno.
3. Ejecutar todas las celdas (**Runtime > Run all**).

La primera celda del notebook instala automáticamente las dependencias que Colab no incluye por defecto (`hdbscan`, `kneed`, `jinja2`). El resto de bibliotecas necesarias ya vienen preinstaladas en Colab.

### Local

```bash
git clone https://github.com/jmduroagea/clustering_practice.git
cd clustering_practice
pip install -r requirements.txt
```

El archivo `requirements.txt` incluye **todas** las dependencias necesarias (tanto las preinstaladas en Colab como las adicionales).

> **Nota:** En ejecución local, cambiar en el notebook la ruta `"/stars_data.csv"` por `"stars_data.csv"`.

Abrir el notebook con Jupyter o VS Code y ejecutar todas las celdas.