[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21392916)
# Ejercicio: Adopción de mascotas 🐶🐱

## Objetivos 🎯​
- Uso de elementos HTML para el ingreso de información.
- Implementar validaciones de datos en la interfaz.
- Utilizar componentes y estilos Bootstrap.
- Evaluar y mejorar la accesibilidad de la interfaz.

## Preparación 🔨​
- Clonar el repositorio para trabajar localmente.
- Abrir la carpeta del proyecto en Visual Studio Code.
- Instalar las extensiones `Live Preview` o `Live Server` en Visual Studio Code para visualizar la página HTML en el navegador.
- Instalar la extensión `WAVE Evaluation Tool` en Chrome para realizar el análisis de accesibilidad.

## Parte A: Ajustes en Formulario HTML 📐

1. Incluir un campo que permita ingresar el nombre de la mascota con la etiqueta 'Nombre'
2. Implementar validación de datos con HTML:
   - **Nombre de la mascota** → El campo de texto Nombre es **requerido**.  
   - **Mail del adoptante** → El campo de email deberá validar que el input cuente con el formato adecuado y es **requerido**.
   - **Peso (kg)** → Es un campo **numérico**. **No debe aceptar valores valores negativos**.  
3. Implementar un checkbox que permita ingresar si la mascota está vacunada.
4. Guardar los cambios y subirlos al repositorio remoto.
5. Crear un issue en GitHub con el título **Parte A** y subir una captura de pantalla del formulario web visualizado en el navegador.

## Parte B: Bootstrap 🖼️​

6. Estilizar el botón de envío con la clase correspondiente al botón **secundario** de Bootstrap.
7. Aplicar la clase `form-control` a los inputs del formulario (**exceptuando el checkbox**) y la clase `form-label` a las etiquetas correspondientes a cada input.
8. Agregar las clases `mx-3` y `p-3` al elemento **card** para aumentar el margen lateral y el padding.
9. Guardar los cambios y subirlos al repositorio remoto.
10. Crear un issue en GitHub con el título **Parte B** y subir una captura de pantalla del formulario web visualizado en el navegador.

## Parte C: Evaluación y mejora de la accesibilidad 🔍​

11. Utilizar la extensión `WAVE Evaluation Tool` en Chrome para evaluar la accesibilidad de la página.
12. Identificar y corregir **errores** (incluyendo errores de contraste) y **alerts** de accesibilidad detectados por la herramienta. Implementar las correcciones necesarias directamente en el código HTML o, cuando corresponda, agregarlas en la hoja de estilos (CSS).
13. Guardar los cambios y subirlos al repositorio remoto.
14. Crear un issue en GitHub con el título **Parte C** y subir una captura de pantalla de la evaluación de accesibilidad (WAVE) sin errores ni advertencias.


## Recursos adicionales 
- [Documentación de HTML](https://html.spec.whatwg.org/multipage/)
- [Documentación HTML](https://www.w3schools.com/html/default.asp)
- [Documentación de Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [WAVE Evaluation Tool](https://chromewebstore.google.com/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh)
