# Editor LaTeX Interactivo
Ejemplo de uso => https://tex.waremlab.com/
## Descripción
Este proyecto es un editor LaTeX interactivo que permite escribir código LaTeX y obtener una previsualización en tiempo real. Está diseñado para facilitar la creación de fórmulas matemáticas complejas mediante una interfaz intuitiva con botones para insertar símbolos comunes, letras griegas, fracciones, raíces, entre otros.

## Características principales
- **Editor con resaltado de sintaxis**: Utiliza CodeMirror para una experiencia de edición mejorada.
- **Previsualización en tiempo real**: Renderiza el código LaTeX usando MathJax.
- **Categorías de símbolos**: Organiza los comandos LaTeX en 10 categorías accesibles mediante menús desplegables.
- **Funcionalidades adicionales**:
  - Copiar el código al portapapeles.
  - Limpiar el editor.
  - Insertar un ejemplo predefinido.

## Tecnologías utilizadas
- [CodeMirror](https://codemirror.net/): Para el editor de código con resaltado de sintaxis.
- [MathJax](https://www.mathjax.org/): Para renderizar las fórmulas matemáticas.
- HTML, CSS y JavaScript: Para la estructura, estilos y funcionalidad.

## Cómo usar
1. **Escribe tu código LaTeX** en el editor.
2. **Inserta símbolos** utilizando los botones de las categorías disponibles.
3. **Previsualiza el resultado** en el área de previsualización.
4. **Copia el código** generado para usarlo en tus documentos.

## Ejemplo de código LaTeX

```latex
\mathcal{L}(\theta ,\phi )=\int_{i\in \mathcal{X}} D_{KL}(p_{\theta}(\cdot |i)\,||\,q_{\phi}(\cdot |i)) = \int_{i\in \mathcal{X}} \int_{j\in \mathcal{X}} p_{\theta}(j|i) \log\left(\frac{p_{\theta}(j|i)}{q_{\phi}(j|i)}\right)
```

## Personalización
Puedes modificar los estilos en el archivo CSS para adaptar el editor a tus preferencias. Además, puedes añadir más símbolos o categorías editando las secciones correspondientes en el HTML y JavaScript.

## Notas
- La previsualización se actualiza automáticamente al detectar cambios en el editor.
- El editor es compatible con la mayoría de los navegadores modernos.

---
## Notas técnicas  
El desarrollo de este proyecto contó con asistencia de herramientas de IA para generación de código y optimizaciones.

## Licencia  
© 2024 - Wiliam Trujillo.  
Este proyecto está bajo la licencia (ver archivo `LICENSE`).  

## Dependencias y créditos  
- [CodeMirror](https://codemirror.net/) (MIT): Editor de código.  
- [MathJax](https://www.mathjax.org/) (Apache 2.0): Renderizado de fórmulas.  

## Inspiración  
Interfaces de editores como [LaTeXLive](https://www.latexlive.com/) y [CodeGogs](https://editor.codecogs.com), aunque este diseño es original.  

## Notas técnicas  
Asistencia de IA utilizada para generación de código y optimizaciones.  
