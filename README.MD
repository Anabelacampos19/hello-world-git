# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italico* pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href = "http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GitHub](https://cdn-icons-png.flaticon.com/256/25/25231.png)

# Code Snippets
Codigo en JSON 
```JSON 
[
  {
    "title": "apples",
    "count":,
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]

```
Codigo en Javascript
```JAVASCRIPT
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }

  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined) {
      console.log('undefined');
    }
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  );
}
```

# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Marisol| Campos   | 39201885  |
|Izan    | Chaile   | 1122345   |

# Citas
Esto es un texto referente a una cita que pondremos debajo: 
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior: 
> Esto es otra cita.

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro txto dividido por asteriscos.

***

Esto es otro texto dividido por guines bajos.

___

# Saltos de linea
Esto nuestro primer parrafo.

Esto nuestro segundo parrafo.

Esto nuestro tercer parrafo.
- Lista