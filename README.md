# WorkshopAnalisisDatos
Repositorio usado para el taller de Análisis de Datos: entendiendo el mundo con Python.

<a target="_blank" href="https://colab.research.google.com/github/danielroa98/WorkshopAnalisisDatos#">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Acceso al repositorio

![Enlace al repositorio](./imgs/QRRepo.png)

## Pasos a seguir

### Entorno local

Si alguien quiere hacer uso de este repositorio, ese necesario que ambienten su equipo para que eviten tener conflictos con sus proyectos de Python.

Esto lo pueden hacer con el comando que se ve a continuación:

```bash
python3 -m venv workshop-da
```

Por temas de librerías, se recomienda utilizar la versión `3.11` de Python, no es obligatorio pero si recomendable.

### Instalación de dependencias

Una vez creado el entorno virtual, actívenlo con el siguiente comando:

**En macOS/Linux:**
```bash
source workshop-da/bin/activate
```

**En Windows:**
```bash
workshop-da\Scripts\activate
```

Luego, instalen las dependencias necesarias ejecutando:

```bash
pip install -r requirements.txt
```

### Uso del repositorio

Para ejecutar los scripts o notebooks incluidos en este repositorio, asegúrense de que el entorno virtual esté activado. Por ejemplo, para ejecutar un notebook, pueden usar:

```bash
jupyter notebook
```

### Abrir en Google Colab

Si prefieren trabajar en Google Colab, pueden abrir este repositorio directamente desde la plataforma. Para ello, sigan estos pasos:

1. Asegúrense de que el repositorio esté disponible en un servicio como GitHub.
2. Copien el enlace del archivo que desean abrir (por ejemplo, un notebook `.ipynb`).
3. Vayan a [Google Colab](https://colab.research.google.com/).
4. Seleccionen la opción **GitHub** en la ventana de inicio.
5. Peguen el enlace del archivo en el campo correspondiente y presionen **Enter**.

Esto les permitirá ejecutar los notebooks sin necesidad de configurar un entorno local.

### Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, revisen el archivo `LICENSE`.