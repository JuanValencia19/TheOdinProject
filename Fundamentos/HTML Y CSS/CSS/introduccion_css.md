# Introducción a CSS

**CSS** (Hojas de Estilo en Cascada) es un lenguaje que describe cómo se deben mostrar los elementos HTML en la pantalla, en papel o en otros medios.

## **Selectores**

Los **selectores CSS** se utilizan para "encontrar" (o seleccionar) los elementos **HTML** a los que deseas dar estilo.

*   **Selector de elemento:** Selecciona elementos basados en el nombre del elemento.
    Ejemplo: `p { color: blue; }` (todos los párrafos serán azules)
*   **Selector de clase:** Selecciona elementos con un atributo de clase específico.
    Ejemplo: `.mi-clase { color: green; }` (todos los elementos con `class="mi-clase"` serán verdes)
*   **Selector de ID:** Selecciona el elemento con un atributo de ID específico.
    Ejemplo: `#mi-id { color: red; }` (el elemento con `id="mi-id"` será rojo)

## **Propiedades**

Las **propiedades CSS** definen el estilo de los elementos **HTML**.

*   `color`: Define el color del texto.
*   `font-size`: Define el tamaño de la fuente.
*   `background-color`: Define el color de fondo.
*   `margin`: Define el margen alrededor del elemento.
*   `padding`: Define el espacio entre el contenido del elemento y su borde.
*   `border`: Define el borde del elemento.

## **Modelo de Caja**

El **modelo de caja CSS** es un concepto fundamental que describe cómo se generan los elementos **HTML** en la pantalla. Cada elemento se considera una caja que consta de:

*   **Contenido:** El contenido del elemento (texto, imágenes, etc.).
*   **Padding:** El espacio entre el contenido y el borde.
*   **Border:** El borde que rodea el padding y el contenido.
*   **Margin:** El espacio alrededor del borde.

## **Cascada y Especificidad**

La "**cascada**" se refiere a cómo **CSS** aplica estilos cuando hay múltiples reglas que podrían aplicarse a un elemento. La "**especificidad**" determina qué regla tiene prioridad.

*   **Especificidad:** Los selectores más específicos tienen mayor prioridad. Por ejemplo, un selector de ID es más específico que un selector de clase, que a su vez es más específico que un selector de elemento.
*   **Importancia:** La regla `!important` se puede utilizar para dar máxima prioridad a una regla. Sin embargo, se recomienda evitar su uso excesivo.

## **Unidades**

**CSS** utiliza varias unidades para especificar tamaños y distancias.

*   **px:** Píxeles (absoluto).
*   **em:** Relativo al tamaño de la fuente del elemento padre.
*   **rem:** Relativo al tamaño de la fuente del elemento raíz (HTML).
*   **%:** Porcentaje (relativo a otro valor).

## Ejemplo

```css
/* Estilos para todos los párrafos */
p {
  font-size: 16px;
  line-height: 1.5;
  color: #333;
}

/* Estilos para elementos con la clase "destacado" */
.destacado {
  font-weight: bold;
  color: navy;
}

/* Estilos para el elemento con el ID "titulo" */
#titulo {
  font-size: 24px;
  text-align: center;
}
```
