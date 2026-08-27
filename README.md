# Homework Notebooks

Repositorio sencillo para publicar tareas hechas en Jupyter Notebook.

## Estructura

- `notebooks/`: tareas en formato `.ipynb`.
- `requirements.txt`: paquetes necesarios para ejecutar las tareas.

## Uso local

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Abre un notebook dentro de `notebooks/` y ejecuta sus celdas en orden.

## Publicar en GitHub

```bash
git init
git add .
git commit -m "Add homework notebooks"
git branch -M main
git remote add origin https://github.com/USUARIO/homework-notebooks.git
git push -u origin main
```

GitHub puede mostrar los notebooks directamente en el navegador. Para una página más presentable, se puede añadir posteriormente Jupyter Book o Quarto.
