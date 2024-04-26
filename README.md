<!-- Encabezados -->

# Mi título H1
## Mi título H2
### Mi título H3
#### Mi título H4
##### Mi título H5
###### Mi título H6

<!-- Formatos -->

Este es un texto en *itálica*

Este es un texto en **negritas**

Este es un texto ~~tachado~~

<!-- Listas desordenadas -->

* Manzana
    * Manzana 2
* Naranja
* Etc.

<!-- Listas ordenadas -->

1. Manzana
    1. Manzana 2
        1. Manzana 3
2. Naranja
3. Etc.

<!-- Enlaces -->

[Faztweb](https://www.faztweb.com)

[Faztweb](https://www.faztweb.com "Título personalizado")

<!-- Citas -->

> Esta es una cita

<!-- Línjeas -->

---
___

<!-- Código -->

`console.log('hello world');`

`
print('hello world')
`

```javascript
const { createServer } = require('node:http');

const hostname = '127.0.0.1';
const port = 3000;

const server = createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello World');
});

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`);
});
```
```python
print('hello world')
```
```html
<h1>Hello world</h1>
```

<!-- Tablas -->

| Col1  | Col2  | Col3  |
|-------|-------|-------|
|Valor 1|Valor 2|Valor 3|
|Valor 4|Valor 5|Valor 6|
|Valor 7|Valor 8|Valor 9|

| Col1   | Col2    | Col3  |
|--------|:-------:|------:|
|Valor 1 |Valor 2  |Valor 3|
|Valor 4 |Valor 5  |Valor 6|
|Valor 7 |Valor 8  |Valor 9|

<!-- Imágenes -->

![visal studio code logo](visual-studio-code-icon.webp "VSCode logo")

<!-- GitHub Markdown -->

To do list:
* [x] Task 1
* [x] Task 2
* [x] Task 3
* [ ] Task 4
* [ ] Task 5

## Mencionar usuarios:

@nombre_de_usuario

## Emojis:

:smiley:

:sweat_smile:

Usar:

[Lista de emojis para GitHub](https://gist.github.com/rxaviers/7360908 "Lista de emojis para GitHub")

[Cheatsheet de MarkDown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Cheatsheet")