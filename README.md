# Proyecto ML — Estructura inicial

Proyecto de ejemplo con estructura mínima para empezar un flujo de Machine Learning.

Estructura creada:

- data/
  - raw/           (datos originales, no trackear en git)
  - processed/     (datos procesados listos para modelado)
- notebooks/       (notebooks exploratorios)
- models/          (modelos serializados y artefactos)
- src/             (código fuente: loaders, entrenamiento, utilidades)
- app/             (app Streamlit)
- docs/            (documentación básica)
- tests/           (tests básicos de unidad)

Requisitos

Instalar dependencias (PowerShell):

```powershell
python -m pip install -r d:\Python\DataScience4Bussines\proyecto_ml\requirements.txt
```

Ejecutar la app Streamlit (desde PowerShell):

```powershell
cd d:\Python\DataScience4Bussines\proyecto_ml
streamlit run app\streamlit_app.py
```

Notas

- Los datos crudos se colocan en `data/raw/` y no se versionan por defecto.
- `data/processed/` puede contener artefactos derivados que sí quieras versionar.
- Edita `src/` para añadir tus funciones de carga, limpieza y modelado.
