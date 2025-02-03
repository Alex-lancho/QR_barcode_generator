# Generador de Códigos de Barras y QR para DNI

Este proyecto contiene dos utilidades web que permiten generar códigos a partir de un número de DNI. Cada herramienta ha sido diseñada con una interfaz limpia y responsiva para facilitar su uso.

## 1. Código de Barras Code39

- **Funcionalidad:**  
  Permite generar un código de barras en formato Code39 a partir de un DNI de 8 dígitos.

- **Características:**  
  - Valida que el DNI ingresado tenga exactamente 8 caracteres.
  - Genera el código de barras utilizando la librería [JsBarcode](https://github.com/lindell/JsBarcode).
  - Opción para descargar el código de barras en formato SVG.
  - Interfaz moderna, centrada y responsiva.

## 2. Generador de QR para DNI

- **Funcionalidad:**  
  Permite generar un código QR a partir de cualquier DNI ingresado.

- **Características:**  
  - Valida que se ingrese un DNI válido antes de generar el código.
  - Crea el código QR usando la librería [qrcodejs](https://davidshimjs.github.io/qrcodejs/).
  - Opción para descargar la imagen del código QR en formato PNG.
  - Diseño visual atractivo y adaptativo, con un contenedor que resalta el código generado.

---

Ambas herramientas están implementadas en HTML, CSS y JavaScript, manteniendo la funcionalidad original mientras se mejora la experiencia de usuario con estilos modernos y responsivos. Puedes integrar y personalizar estos módulos según las necesidades de tu proyecto.
