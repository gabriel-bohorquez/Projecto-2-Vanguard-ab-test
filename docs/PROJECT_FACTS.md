# PROJECT_FACTS

## Identidad del proyecto

- Nombre actual del proyecto: Projecto-2-Vanguard-ab-test
- Tipo de proyecto: Análisis A/B de experiencia digital
- Estado: Proyecto existente en proceso de auditoría y profesionalización
- Repositorio: https://github.com/gabriel-bohorquez/Projecto-2-Vanguard-ab-test
- Origen: Fork de un repositorio colaborativo

## Inventario inicial del repositorio

### Carpetas principales

- `Análisis AB Vanguard Nueva Interfaz Digital y Tasas de Finalización/`
- `data_raw/`
- `docs/`
- `notebooks/`
- `src/`

### Archivos en la raíz

- `Proyecto.twbx`
- `README.md`
- `output.png`
- `output4.png`
- `vanguard_tableau_ready.csv`

### Notebooks

- `01_data_understanding_1.ipynb`
- `02_data_cleaning.ipynb`
- `03_eda_client_behavior.ipynb.ipynb`
- `04_kpis_ab_testing.ipynb`
- `05_hypotesis_testing.ipynb`
- `06_final_analysis.ipynb`

### Scripts

- `src/functions.py`

### Documentación de trazabilidad

- `docs/README_ORIGINAL_VANGUARD_AB_TEST.pdf`
- `docs/PROJECT_FACTS.md`

### Estado del inventario

Inventario inicial registrado antes de modificar la estructura, nombres o contenido del proyecto.

## Riesgos iniciales detectados

### Prioridad alta

- El repositorio contiene un archivo `.DS_Store`, que no debe versionarse.
- El README documenta una estructura distinta de la estructura real.
- No existe todavía un archivo `.gitignore`.
- No existe un archivo `requirements.txt` visible en la raíz.
- El dataset `vanguard_tableau_ready.csv` está suelto en la raíz.
- El dashboard Tableau tiene un nombre genérico: `Proyecto.twbx`.

### Prioridad media

- `01_data_understanding_1.ipynb` contiene un sufijo innecesario.
- `03_eda_client_behavior.ipynb.ipynb` tiene doble extensión.
- `05_hypotesis_testing.ipynb` contiene un error ortográfico en inglés.
- `output.png` y `output4.png` no tienen nombres descriptivos.
- La carpeta de imágenes tiene un nombre excesivamente largo y poco mantenible.

### Prioridad baja

- El nombre del repositorio mezcla idiomas y conserva una denominación académica.
- La sección About de GitHub no tiene descripción, sitio web ni topics.
- El repositorio conserva visiblemente su condición de fork.