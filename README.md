# proyecto1_analisis_datos

## Configuración del entorno

### 1. Requisitos previos

- Python 3
- pip

Verificar las versiones instaladas:

```bash
python --version
pip --version
```

### 2. Crear el entorno virtual

```bash
python -m venv ~/venv-olist
```

Activar el entorno virtual:

```bash
source ~/venv-olist/bin/activate
```

### 3. Instalar dependencias

```bash
pip install duckdb pandas jupyterlab pyarrow matplotlib seaborn
```

Instalar JupySQL:

```bash
pip install jupysql
```

### 4. Ejecutar JupyterLab

Activar el entorno virtual:

```bash
source ~/venv-olist/bin/activate
```

Iniciar JupyterLab:

```bash
jupyter lab
```

JupyterLab se abrirá en el navegador. Desde allí se puede acceder al notebook del proyecto y ejecutar las celdas.

### 5. Desactivar el entorno virtual

Al finalizar el trabajo:

```bash
deactivate
```

### 6. Dependencias utilizadas

| Librería | Descripción |
|---|---|
| `duckdb` | Motor de base de datos para consultas SQL y procesamiento de datos. |
| `pandas` | Manipulación y análisis de datos. |
| `jupyterlab` | Entorno para ejecutar notebooks. |
| `pyarrow` | Lectura y escritura de archivos Parquet. |
| `matplotlib` | Generación de gráficos. |
| `seaborn` | Visualización estadística. |
| `jupysql` | Ejecución de consultas SQL dentro de Jupyter. |

**Nota:** El entorno virtual se crea una sola vez. Para las siguientes ejecuciones, únicamente es necesario activarlo antes de iniciar JupyterLab.