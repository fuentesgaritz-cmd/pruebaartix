# Aritz Fuentes — Liquid Glass Portfolio

Segunda versión del portfolio.

## Incluye
- Estética liquid glass / translucent UI
- Paleta de colores complementarios y vibrantes
- Tipografía moderna + tipografía experimental para titulares
- Responsive: móvil, tablet y escritorio
- Menú móvil
- Selector de idioma ES / EU / EN
- Traducciones integradas en JavaScript
- Persistencia del idioma seleccionado con localStorage
- Microinteracciones y efecto 3D sutil en proyectos con ratón
- Compatibilidad con `prefers-reduced-motion`

## Abrir
Haz doble clic en `index.html`.

## Archivos
- index.html
- styles.css
- script.js

## Sustituir proyectos
Las composiciones actuales son placeholders diseñados en CSS. Puedes cambiarlas por imágenes reales dentro de `.project-visual`, o usar `background-image`.

## Email y redes
Busca:
- `hola@aritzfuentes.com`
- `href="#"`

y sustitúyelos por tus datos reales.

## Traducciones
Están dentro de `script.js` en el objeto `translations`.


## Cambios v2
- Eliminado el punto junto al nombre.
- Header más alto, ancho y legible.
- Nueva paleta complementaria de alto contraste: azul eléctrico / naranja y violeta / amarillo ácido.
- Ajustes cromáticos en hero, proyectos, selector de idioma y contacto.


## Cambios v3
- La tarjeta “Feria del Libro de Chinchón” enlaza ahora a una página de proyecto.
- Se ha añadido `feria-libro-chinchon.html`.
- El cartel de la feria está integrado como imagen real.
- El PDF del díptico se ha convertido en imágenes para mostrar exterior e interior.
- Se ha creado una animación interactiva: el díptico aparece cerrado y se abre al hacer clic.
- El contenido nuevo también está traducido a castellano, euskera e inglés.

## Cambios v4
- Se elimina la repetición del cartel: solo aparece una vez.
- El texto conceptual se compacta debajo de la introducción del proyecto.
- Cliente, tipo de encargo y año aparecen inmediatamente después.
- El visor del díptico se ha reconstruido desde cero.
- Estado inicial: portada cerrada.
- Al hacer clic, la portada gira y el interior se despliega.
- El control del díptico es independiente del resto de interacciones.
- Las traducciones del proyecto se cargan antes de inicializar el idioma.

## Cambios v5
- El díptico ya no gira usando una única imagen.
- La hoja de portada tiene ahora dos caras reales en 3D.
- Cara frontal: portada.
- Cara posterior: panel izquierdo del interior.
- Panel fijo: panel derecho del interior.
- Cuando termina de abrirse, la portada desaparece completamente y el resultado es el interior completo.

## Cambios v6
- Al abrir el díptico ya no se muestra ninguna cara trasera espejada.
- El estado abierto muestra exclusivamente la página 2 completa del PDF.
- La portada se anima con un giro y desaparece visualmente al abrirse.
- Se ha simplificado la lógica del componente para hacerlo más fiable.

## Cambios v7
- La portada del proyecto “Feria del Libro de Chinchón” en la página de inicio usa ahora un recorte del cartel real.
- El encuadre se centra en el título “XVII Feria del Libro de Chinchón (2026)”.
- El cartel completo sigue apareciendo únicamente dentro de la página del proyecto.

## Cambios v8
- La sección de trabajos ahora usa una cuadrícula 3 × 3.
- Hay 9 tarjetas de proyecto iguales.
- Las tarjetas son más compactas.
- El nombre del proyecto aparece siempre debajo de la imagen con buena legibilidad.
- Responsive: 3 columnas en escritorio, 2 en tablet y 1 en móvil.

## Cambios v9
- Reencuadre de la miniatura de Feria del Libro en Trabajos seleccionados.
- El foco queda centrado en “XVII Feria del Libro de Chinchón (2026)”.

## Cambios v10
- La miniatura de Feria del Libro en la home se ha reducido visualmente.
- El bloque del título tiene más aire alrededor para mejorar la lectura.

## Cambios v11
- La carátula de “Feria del Libro de Chinchón” en la home usa ahora exactamente el recorte aprobado por el usuario.

## Cambios v12
- La miniatura de “Noche de los Cuentos” en la home usa ahora el recorte aprobado por el usuario.

## Cambios v13
- La miniatura de “Noche de los Cuentos” en la home se ha sustituido por la nueva imagen aprobada por el usuario.

## Cambios v14
- Se ha añadido una página propia para “Noche de los Cuentos”.
- La tarjeta en la home enlaza ahora a `noche-cuentos-chinchon.html`.
- Se ha integrado el cartel final del proyecto.
- Se ha añadido un texto explicativo en castellano, euskera e inglés.
- Se mantiene el mismo lenguaje visual que la página de la Feria del Libro.

## Cambios v15
- Corregido el enlace de la tarjeta “Noche de los Cuentos”.
- Ahora abre `noche-cuentos-chinchon.html`.
- Eliminado el enlace incorrecto de la tarjeta “Imagina Bilbao”.

## Cambios v16
- Añadida sección de variaciones generadas con apoyo de IA en Noche de los Cuentos.
- Carrusel con 5 piezas visuales.
- Navegación con flechas, indicadores y swipe táctil.
- Añadido texto conceptual sobre un uso de la IA como herramienta de acompañamiento al criterio humano.
- Traducciones ES / EU / EN.

## Cambios v17
- Actualizadas las 5 variantes visuales del bloque de IA en “Noche de los Cuentos”.
- Nuevo layout en dos columnas:
  - izquierda: texto explicativo
  - derecha: carrusel/selector visual
- Los carteles del carrusel aparecen ahora bastante más pequeños y elegantes.
- Mejorado el texto conceptual sobre el uso responsable de la IA.
- Actualizado el JS del carrusel para soportar controles duplicados (escritorio / móvil).

## Cambios v18
- Añadida flecha en ambos lados del carrusel.
- Añadidos botones de reproducir y detener.
- El carrusel puede avanzar automáticamente.
- Nueva transición más suave, tipo morph (fade + blur + escala).
- Actualizadas las 5 imágenes del módulo con las versiones correctas.
- Se mantiene el layout en dos columnas: texto a la izquierda y selector visual a la derecha.

## Cambios v19
- El modo automático del carrusel cambia ahora cada 5 segundos.
- El botón “Detener” para por completo la reproducción automática.
- Las flechas manuales siguen funcionando siempre, tanto en play como en stop.

## Cambios v20
- Auditoría de internacionalización de la web.
- Regla fija del proyecto: todo el contenido visible debe existir en ES / EU / EN.
- Traducidos también controles y etiquetas auxiliares del carrusel.
- Añadida traducción de etiquetas ARIA para navegación y accesibilidad.
- El botón de menú adapta también su etiqueta al idioma activo.

## Cambios v21
- Corregido el fallo estructural del sistema de traducciones.
- `noche` ya no está anidado dentro de `feria`.
- La página “Noche de los Cuentos” traduce correctamente todos sus textos en ES / EU / EN.
- Validada programáticamente la existencia de las claves principales de traducción en los tres idiomas.

## Cambios v22
- Añadido fondo decorativo de stickers flotantes en la página “Noche de los Cuentos”.
- Máximo de 5 stickers simultáneos: 3 a color y 2 monocromos.
- Movimiento suave por toda la página, con velocidad constante y aleatoria.
- Renovación automática del conjunto cada 10 segundos.
- Los stickers son decorativos de fondo y no interfieren con la lectura.
- Restaurado también el autoplay del carrusel a 5 segundos.
