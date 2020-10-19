# Usando requerir cambios -- `request changes` en una solicitud de extracción

Gracias otra vez por toda tu ayuda en esa última solicitud de extracción. Con nuestro poder combinado, ¡_cualquier cosa_ es posible! Este próximo cambio podría introducir algunos cambios que no van a tener buen aspecto.

A veces, el autor podría identificar algo que no está funcionando. Podrían necesitar que alguien les eche una mano :wave: para resolver el problema. En otras ocasiones, podría solamente funcionar en su equipo. Cuando revises una solicitud de extracción, mira y prueba el código para identificar cualquier error o comportamiento inesperado.

### Escribir una revisión

#### Revisa la `diff`

Revisa la `diff`, la comparación del código propuest, en el contexto del proyecto en su conjunto. ¿Podría introducir problemas de rendimiento o vulnerabilidades de seguridad? Intenta predecir posibles consecuencias indeseadas que este cambio podría causar.

#### Pruébalo

En la mayoría de ocasiones, probar el cambio propuesto es una buena idea. Esto hace que sea mucho más fácil distinguir si el cambio realmente se ajusta a la intención. Puedes hacer esto de las siguientes maneras:

- Clona el repositorio, y cámbiate (o _check out_) a la rama que se compara en la solicitud de extracción. Ejecuta la aplicación en tu entorno local de desarrollo.
- Impementa la solicitud de extracción a un laboratorio de revisión o entorno intermedio (según sea apropiado).

Cuando resumas tu revisión, informa al autor de si has realizado algún test o prueba de este tipo.

#### Empatía y feedback constructivo

El objetivo de ofrecer feedback en una solicitud de extracción es asegurarse de que se incorpora el mejor cambio posible. A veces un cambio no afronta el problema de la mejora manera. Es responsabilidad del revisor ofrecer feeedback significativo y constructivo.

### Requerir cambios

Antes de que envíes tu revisión, tus comentarios en línea figuran como pendientes y son solamente visibles para ti. Puedes editar comentarios pendientes en cualquier momento antes de enviar la revisión. Para cancelar una revisión pendiente y todos sus comentarios pendientes, haz scroll hasta el final de la página en la pestaña "Conversation", y haz clic en **Cancel review**.

## Paso 4: Deja una revisión que requiere algunos cambios

Si pudieras comprobar este código por mí y decirme dónde está el problema, sería genial.

### :keyboard: Actividad: Requerir cambios

1. En la solicitud de extracción, haz clic en **Files changed**
1. Coloca el cursor sobre la línea de código donde te gustaría añadir un comentario, y haz clic en el icono azul de comentario
1. En la ventana de comentarios, redacta tu comentario
1. Haz clic en **Start a review**
    - Si ya has iniciado una revisión, puedes hacer clic en **Add review comment**
2. Encima del código modificado, haz clic en **Review changes**
3. Escribe un comentario que resuma tu feedback sobre los cambios propuestos
    - _Nota: El problema aquí es que demasiadas piezas del Tetris tienen el mismo color. En tu revisión, podrías sugerir que escoja colores que sean más fáciles de distinguir durante el juego._
4. Selecciona **Request changes** para enviar feedback que introduzca los cambios necesarios antes de combinar
5. Haz clic en **Submit review**

<hr>
<h3 align="center">Vuelve a esta solicitud de extracción para mi siguiente comentario</h3>

> _A veces respondo demasiado rápido y no doy tiempo a que se actualice la página. Si realizas alguna acción prevista y no recibes ninguna respuesta, espera unos segundos y actualiza la página para los próximos pasos._
