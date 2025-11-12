
# Práctica 6 – Modificación de estilos y RETO

En esta práctica continuaremos el trabajo iniciado en la **Práctica 5**, mejorando el diseño visual de nuestra página mediante nuevas propiedades CSS y pequeños ajustes estructurales en el código HTML.

Se trata de **una ampliación del proyecto anterior**, en la que deberás **añadir una nueva hoja de estilos** o modificar la existente (`practica5_estilo1.css`) siguiendo las indicaciones que encontrarás en los comentarios del código facilitado.

Cada modificación deberá ir identificada con tus **iniciales y el número de la solución** en formato:

```css
/* DCS - sol1 */
```

o, en el caso del documento HTML:

```html
<!-- DCS - sol10 -->
```

No debes añadir explicaciones dentro de los comentarios, únicamente tus iniciales, el guión y el número de solución propuesto.

Para que trabajéis con la misma versión HTML de dónde yo he partido para generar estas modificaciones, se adjuntan en este repositorio los archivos solucionados de la práctica 5:

* [practica5_solucion.html](practica5_solucion.html)
* [practica5_estilo1.css](practica5_estilo1.css)

**Simplemente tenéis que actualizar el nombre de las imágenes con las vuestras dentro del fichero HTML.**

---

## 🧾 Instrucciones generales

1. Abre tu proyecto de la práctica anterior (**Práctica 5**).
2. Guarda una copia con el nombre:
   **`practica6_solucion.html`** y **`practica6_estilo.css`**
3. Aplica las **10 modificaciones** indicadas mediante comentarios en el archivo CSS base entregado.
4. Realiza el cambio solicitado en el HTML (agregar una clase a dos secciones).
5. Añade tus comentarios identificativos (`/* TUSINICIALES - solX */` o `<!-- TUSINICIALES - solX -->`) donde corresponda.
6. Visualiza los resultados en el navegador y revisa que cada modificación se haya aplicado correctamente.

---

## 🎯 Modificaciones a realizar

| Nº        | Modificación a realizar                                                                                                              |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **sol1**  | Corregir que no se muestre el título en la cabecera de las secciones.                                                                |
| **sol2**  | Cambiar el color del texto de los subtítulos en las cabeceras de las secciones a *LightGray*.                                        |
| **sol3**  | Aumentar el tamaño de fuente de las opciones del menú a *1.7em*. (ver [explicación de unidades de medida](#unidades))                                                                     |
| **sol4**  | Ampliar el tamaño del encabezado principal (`h1`) a *2.8em* y cambiar su color al amarillo del logo.                                 |
| **sol5**  | Crear un marco alrededor de las imágenes de los artículos con fondo, padding, márgenes y bordes redondeados.                         |
| **sol6**  | Aplicar un efecto de sombra (*box-shadow*) en las imágenes de los artículos con el color de las cabeceras.                           |
| **sol7**  | Modificar el color de fondo del menú al pasar el ratón por encima (*hover*) utilizando el color del logo.                            |
| **sol8**  | Ajustar la altura del logo a *120px*, manteniendo la proporción original.                                                            |
| **sol9**  | Cambiar el color del texto enfatizado (`<em>`) al color de fondo de las cabeceras, con fondo amarillo del logo.                      |
| **sol10** | Cambiar el color de fondo de las cabeceras de las secciones 2 y 4 a `#74750D` mediante clases aplicadas a los elementos `<section>`. |

**IMPORTANTE**
* Para `sol4` utiliza la herramienta online [imagecolorpicker.online](https://imagecolorpicker.online/es/)
* Para `sol6` utiliza la herramienta online [cssgenerator.org/box-shadow-css-generator](https://cssgenerator.org/box-shadow-css-generator.html)
* Otra página web interesante a la hora de obtener un color específico de forma gráfica y muy sencilla es [htmlcolorcodes](https://htmlcolorcodes.com/)

---

## ⚙️ Modificación en el HTML

En el archivo **`practica6_solucion.html`**, realiza **únicamente un cambio**:

> Añade la clase necesaria a los elementos `<section>` correspondientes a los menús **2** y **4**, para que la regla CSS de la solución 10 pueda aplicarse correctamente.
>
> Comenta el cambio con tu identificador:
>
> ```html
> <!-- DCS - sol10 -->
> ```

---

## 🚀 Reto final

> **RETO:**
> Alrededor de la página web debe visualizarse un **marco** con el color de fondo amarillo del logo, y el contenido principal debe proyectar una **sombra similar a la utilizada en las imágenes**, pero con la **mitad de los valores de desenfoque y radio de extensión**.

Incluye el comentario correspondiente:

```css
/* DCS - RETO */
```

📸 Cuando termines, realiza **una captura de pantalla** del resultado final y compárala con la imagen de referencia que se facilitará.
Guarda el archivo con el nombre **`practica6_reto.png`** y entrégalo junto con el resto del proyecto.

<img width="1923" height="2100" alt="image" src="https://github.com/user-attachments/assets/ac86839d-bf19-47b3-b59d-3885c7598f95" />

---

## 📦 ENTREGA DE LA PRÁCTICA

Tu entrega debe incluir los siguientes archivos en un **repositorio de GitHub** con el o los commits realizados desde **terminal**, gestionando la carpeta `LM_practica6` *(o cóm la hayas llamado tú)*  con Git. El contenido de la carpeta será el siguiente:

* Una carpeta `img` con las imágenes utilizadas, renombradas correctamente, por ejemplo img01.jpeg, img02.jpeg, etc.
* Los ficheros HTML y CSS: `practica6_solucion.html` y `practica6_estilo.css`.
* Una carpeta `capturas`, con el pantallazo al final del reto: `practica6_reto.png`.

---

## ⚖️ UNIDADES DE MEDIDA EN CSS <a id="unidades"></a>

| Unidad      | Tipo     | Descripción                                                     | Ejemplo              |
| ----------- | -------- | --------------------------------------------------------------- | -------------------- |
| `px`        | Absoluta | Píxeles. Valor fijo, no depende del tamaño de texto o pantalla. | `width: 300px;`      |
| `%`         | Relativa | Porcentaje respecto al contenedor.                              | `width: 80%;`        |
| `em`        | Relativa | Basada en el tamaño de fuente del elemento actual.              | `padding: 2em;`      |
| `rem`       | Relativa | Basada en el tamaño de fuente del elemento raíz (`html`).       | `font-size: 1.2rem;` |
| `vh` / `vw` | Relativa | Porcentaje del alto o ancho de la ventana del navegador.        | `height: 50vh;`      |

---

## 🧩 EXPLICACIÓN DE ALGUNAS PROPIEDADES INTERESANTES

### 📐 `max-width`

Permite definir un **ancho máximo** para un elemento, impidiendo que crezca más allá de ese valor incluso si el contenedor es más ancho.
Se usa mucho en diseños **responsivos**, especialmente para centrar bloques sin fijar tamaños absolutos.

```css
article figure {
  max-width: 540px;
}
```

---

### 💨 `box-shadow`

Crea sombras alrededor de los elementos, proporcionando sensación de profundidad.
Su sintaxis general es:

```css
box-shadow: desplazamientoX desplazamientoY desenfoque extensión color;
```

Ejemplo:

```css
box-shadow: 0px 0px 30px 20px rgba(13,59,102,0.6);
```

* `0px 0px`: sin desplazamiento horizontal ni vertical.
* `30px`: radio de desenfoque.
* `20px`: extensión del área de sombra.
* `rgba(...)`: color con transparencia.

---

### 🖋️ `font-family`

Define la **fuente tipográfica** del texto.
Se pueden indicar varias fuentes, separadas por comas.
El navegador probará cada una **en orden** hasta encontrar una disponible.

#### 📘 Tipos de fuentes en CSS

**A) Fuentes del sistema o del navegador**
Son las preinstaladas (como Arial, Verdana, Times New Roman, Georgia…).
No requieren descarga.

```css
body {
  font-family: Arial, Helvetica, sans-serif;
}
```

---

**B) Fuentes locales (instaladas en el equipo o en el proyecto)**
Si la fuente está descargada, puede incluirse con `@font-face`:

```css
@font-face {
  font-family: "MiFuente";
  src: url("fonts/MiFuente.ttf") format("truetype");
}

h1 {
  font-family: "MiFuente", Arial, sans-serif;
}
```

---

**C) Fuentes desde Internet (Google Fonts, Adobe Fonts, etc.)**

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
```

```css
body {
  font-family: "Roboto", Helvetica, sans-serif;
}
```

---

#### 💡 Buenas prácticas con fuentes

1. **Indica siempre varias fuentes de respaldo** (de más específica a más genérica).
2. Termina la lista con una **familia genérica**, una de las cinco reconocidas por CSS:

| Familia genérica | Ejemplo visual                 | Uso típico                 |
| ---------------- | ------------------------------ | -------------------------- |
| `serif`          | con remates (Times, Georgia)   | textos impresos o formales |
| `sans-serif`     | sin remates (Arial, Helvetica) | diseño web moderno         |
| `monospace`      | ancho fijo (Courier, Consolas) | código o tablas alineadas  |
| `cursive`        | escritura manuscrita           | títulos decorativos        |
| `fantasy`        | artísticas o creativas         | logotipos, carteles        |

Ejemplo correcto:

```css
font-family: "Segoe UI", "Roboto", Arial, sans-serif;
```

Si el navegador no encuentra las primeras, usará cualquier fuente **sans-serif** disponible.

---

### 🧱 `display`

Controla cómo se comporta un elemento dentro del flujo del documento.

| Valor          | Descripción                                                                                                                |
| -------------- | -------------------------------------------------------------------------------------------------------------------------- |
| `block`        | El elemento ocupa toda la línea y permite márgenes, padding, ancho y alto.                                                 |
| `inline`       | Ocupa solo el espacio de su contenido. No admite `width` ni `height`, y los márgenes/padding verticales no separan líneas. |
| `inline-block` | Combina lo mejor de ambos: mantiene el flujo horizontal pero permite tamaño, márgenes y relleno.                           |

Ejemplo típico en el menú de navegación:

```css
nav li {
  display: inline-block;
  margin: 0 10px;
}
```

Esto hace que las opciones del menú aparezcan **alineadas horizontalmente**.

Para eliminar los puntos de lista del menú se utiliza:

```css
nav ul {
  list-style: none;
}
```

---

### 📏 `line-height`

Define la **altura de línea**, es decir, el espacio vertical entre líneas de texto.
Puede expresarse en unidades relativas o absolutas:

```css
p {
  line-height: 1.5;
}
```

Un valor `1.5` significa 1,5 veces el tamaño de la fuente.

---
