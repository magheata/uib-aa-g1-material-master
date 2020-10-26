# Aprendizaje Automático

Material para las prácticas asíncronas.

## Instalar entorno virtual

Para instalar el entorno virtual usando conda, ejecutar desde la terminal:

```bash
conda env create --file datascience.yaml
```

Esto creará el entorno virtual `ds-uib`. 

Para poder activarlo y trabajar en él, desde la terminal ejecutar:

```bash
conda activate ds-uib
```

y para dejar de trabajar en él:

```bash
conda deactivate
```

### Hacer el entorno virtual visible en jupyter

Para poder tener disponible el `kernel` con el entorno que hemos creado, bastará con ejecutar **una vez** desde la terminal:

```bash
# activar el entorno virtual
conda activate ds-uib

# Hacer visible el entorno a jupyter
python -m ipykernel install --user --name ds-uib --display-name "Py37 (ds-uib)"
```
