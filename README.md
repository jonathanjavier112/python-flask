# EJEMPLO BÁSICO FLASK Y PYTHON
### Requerimientos
 - Python 3.8
 - Flask
 - Bootstrap

---

### Instalación framework Flask
`pip install flask`

---

### Iniciar
`python index.py`
> "Abrir navegador y escribir la dirección:" [localhost:5000](http://localhost:5000/)

---

### Rutas

|Ruta del archivo|Descripción|
|-|-|
|`static/css/main.css`|Hoja de estilo usada en la aplicación|
|`templates/*.html`|Archivos donde se encuentra el diseño de cada ruta web|
|`index.py`|Archivo principal del microservicio|

|Ruta web|Descripción|
|-|-|
|`/`|Vista principal del microservicio|
|`/acerca`|Visualiza el contenido de la ruta "Acerca de"|

---

#### Notas
Los cambios realizados en el código se mostrarán automáticamente

	if __name__ == '__main__':
	    app.run(debug=True)

Será necesario detener e iniciar la ejecución

	if __name__ == '__main__':
	    app.run()
