# Version del curso
version 1.2.2

# Cabeceras. 
# cabecera H1 
## cabecera H2
### Cabecera H3
#### cabecera H4
##### cabecera H5
###### cabecera H6

# UnderLine
Underline 1
---------------------

Underline 2
======================

# Formatos de enfasis.
- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~, formato normal.
- aqui podemos usar *Formato italica*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada. 
2. Esto es un item de lista ordenada. 
3. Esto es un item de lista ordenada. 
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="http://google.com">Esto es un link HTML</a> 
- [Esto es un link en Markdown](http://google.com) 
- [Esto es un link index](index.html)

# Imagenes
![Logo GIthub](https://avatars0.githubusercontent.com/u/6598377?s=400&v=4)

# Code Snippets
Codigo en JSON
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
Codigo en JS
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
| Nombre |Apellido | Documento |
|--------|---------|-----------|
|MaXi    | Burgos  | 5646532   |
|Tomas   | Tompson | 654653    |

# Citas
Esto es un texto referene a una cita que pondremos abajo.
> Esto es una cita.

Esto e otro texto que no se relaciona a la cita anterior.
> Esto es untra cita, importante dejar un espacio extras al final.

# Lineas Divisoras
Esto es un texto que sera divido por guiones medios dejar un enter de referencia xD 

---
Esto es otro texto dividido por asteriscos 

***
Este es otro texto dividido por guiones bajos

___

# Saltos de linea (linebreak)
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista

