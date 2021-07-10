# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline
Underline 1
*********

Underline 2
==========

# Formatos de enfásis
- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma
- Formato __bold o strong__ de la segunda forma
- Formato ~~tachado~~ normal

# Listas
1. Esto es un item
2. Esto es un item
3. Esto es un item
- Esto es un item desordenado
- Esto es un item desordenado
- Esto es un item desordenado

# Links
- <a href="https://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](https://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GitHub](https://image.flaticon.com/icons/png/512/25/25231.png)

# Code Snippets
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Código en javascript
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
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento|
| ---------| --------- | ------------|
| Héctor| Ariza | 123455|
| Héctor| Ariza | 123456|

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la línea anterior:
> Esto es otra cita


# líneas divisoras
Esto será un texto que será dividido guion medio

---
Este es otro texto divido por arteriscos

***

Este es otro texto divido por guion bajo
___

# Saltos de línea
Esto es un primer parrafo.

Esto es un segundo parrafo.

Esto es un tercer parrafo.