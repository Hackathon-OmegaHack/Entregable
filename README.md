# Descripcion de los proyectos

## Descripción
Este repositorio contiene el desarrollo de front, back y entrenamiento del modelo, el siguiente link se contiene el entregable del poryecto y la bitacora

## Documento Entregable y bitacora
Por favor, consulta el documento entregable para más detalles: [Entregable](https://docs.google.com/document/d/10XPGSA8f83XxOJyr741QBS0GnA0bKQiPpOMaY5kljKU/edit?usp=sharing).
##
Por favor, consulta el documento bitacora para más detalles: [Bitacora](https://docs.google.com/document/d/1eJSguXiwOOCWThZrM-JE72qhjw1qmB_lcJdybwqeeWY/edit?usp=sharing).
##
Por favor, consulta la presentacion de pitch: [Pitch](https://www.canva.com/design/DAGCZn7KB6M/9C0_WcMf_zBaDGQe_SWWJw/edit?utm_content=DAGCZn7KB6M&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).
## Sobre el modelo
El modelo es una regresion lineal de keras, en el preprocesamiento se aprovecha la funcion seno para aislar las caracteristicas del comportamiento ciclico(diario,semanal...etc)
de consumo general de los electrodomesticos reduciendo el ruido normalizando los datos y en general dandonos un modelo eficiente, se piensa escalar el modelo llevando a un modelo
de red neuronal para poder aplicar fine tuning con el cual se esacalara y aislara por tipo de personas
- Python 3.12.3
- Jupyter notebooks
las celdas de los notebooks deben ser ejecutadas en orden de arriba a abajo
## Sobre el Frontend
El proyecto está hecho utilizando las siguientes librerias:
- ReactJS
- NextJS
- Typescript
- DaisyUI

Se quizo utilizar una estructura de carpetas en base a modulos, cada modulo puede representar una page por ejemplo, con el fin de tener una organización por conjuntos

### Instalación del proyecto:

      Clona el repositorio desde github o bajando el .zip
      
      cd Frontend
      
      npm install
      
      npm run dev

- El proyecto se abrirá en el puerto 3000 de tu localhost: http://localhost:3000

- Despliegue en vercel: celsia-omegahack.vercel.app
  
## Sobre el Backend
El backend es una API construida en FastAPI y desplegada en nube en railwai que consume el modelo y al cual se le puede entregar un archivo csv y nos devuelve dos json una de la prediccion de los electrodomesticos y otro que nos indica el estado de encendido de los electrodomesticos
- Python 3.12.3
- FastAPI
- Docker
  Link Backend [BACK](https://backend-production-27fa.up.railway.app/).

