# DevsuPruebas

El primer paso es Clonar o descargar el archivo "PRUEBAS.rar"

# Instrucciones para Ejecutar Pruebas en Cypress

Estas instrucciones te guiarán a través del proceso de configuración y ejecución de pruebas automatizadas en Cypress para el proyecto.

## Requisitos Previos

Asegúrate de tener instalado VSC

## Instalación de Cypress

1. Abre la terminal en la raíz del proyecto.

2. Ejecuta el siguiente comando para instalar Cypress como una dependencia de desarrollo:

npm install cypress --save-dev


## Ejecución de Pruebas

1. Abre la terminal en la raíz del proyecto.

2. Ejecuta el siguiente comando para abrir la interfaz de usuario de Cypress:

npx cypress open

3. Cypress se abrirá y mostrará una ventana con una lista de archivos de prueba.

4. Haz clic en el archivo de prueba que deseas ejecutar en nuestro caso, el archivo ("spec.cy.js2") tanto para las dos pruebas.

5. Cypress abrirá una ventana de navegador donde ejecutará las pruebas y mostrará los resultados.

Adicional, si quieres que se ejecute las pruebas desde el terminal de VSC, sigue los siguientes pasos:


## Modificación de las Pruebas

Si deseas modificar las pruebas existentes o agregar nuevas pruebas, puedes hacerlo editando los archivos de prueba en la carpeta `cypress/integration`.

## Notas Adicionales

- Asegúrate de que el sitio web de demostración esté en ejecución mientras ejecutas las pruebas.

- Si encuentras problemas específicos durante la ejecución de las pruebas, asegúrate de que los selectores de elementos utilizados en las pruebas coincidan con la estructura de la página real.

- Si necesitas ayuda adicional o tienes preguntas, no dudes en contactar al equipo de desarrollo.

¡Listo! Ahora estás listo para ejecutar y modificar las pruebas en Cypress para este proyecto. ¡Buena suerte!


