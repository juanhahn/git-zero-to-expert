# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline2
==========

# Formatos de enfasis
- Formato *Italica* de la primera forma.
- Formato _Italica_ de la segunda forma.
- Formato **bold o strong** de la primera forma
- Formato __bold o strong__ de la segunda forma
- Formato ~~tachado~~, formato normal.

# Listas
1. Item n°1
2. Item n°2
3. Item n°3
- Item de lista desordenada
- Item de lista desordenada
- Item de lista desordenada

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets
Código en JSON
```JSON
[
    {
        "title": "apples",
        "count": [12000, 20000],
        "description": {
            "text": "...",
            "sensitive": false
            }
    },
    {
        "title": "oranges",
        "count": [17500, null],
        "description": {
            "text": "...",
            "sensitive": false
            }
    }
]
```
Código en Javascript
```Javascript
function $initHighlight(block, cls) {
    try {
        if (cls.search(/\bno\-highlight\b/) != -1)
            return process(block, true, 0x0F) + ` class="${cls}"`
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
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | 3546481 |
| Tomas | Thompson | 3243243 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es un a cita.

Esto es otro texto que no se relaciona con la cita anterior
> Esto es otra cita.

# Linea Divisoras
Esto es un texto que sera dividido por guiones medios.
---
Esto es otro texto dividido por asteriscos.
***
Esto es otro texto dividido por guiones bajos.
___

# Saltos de Lineas
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.