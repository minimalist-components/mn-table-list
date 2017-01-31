# mn-table-list

Table list with a minimalist design

![preview demo](https://raw.githubusercontent.com/minimalist-components/mn-table-list/master/sources/imgs/preview.png)

<!-- See the [demo](https://codepen.io/darlanmendonca/full/vKqLOx) -->

### Install

```sh
npm install --save mn-table-list
```

And bundle dependencies and main files in [dist/](https://github.com/minimalist-components/mn-table-list/tree/master/dist) with your preferred tool.


### Usage

Just use the class `.mn-table-list` in a div, and inside of them, `.mn-item`.

```pug
.mn-table-list
  .mn-item
    span John Snow
    span snow@iknownothing.com

  .mn-item
    span Khaleesi
    span motherofdragons@targaryen.com
```


If you want a header, just use the tag header before items, each title need be h1, h2, ... h6, e.g.

```pug
.mn-table-list
  header
    h2 Name
    h3 Email

  .mn-item
    span John Snow
    span snow@iknownothing.com
```


## Responsive

In screens smaller than 600px, only the first content of in every .mn-item will be displayed. If you want force to always be visible, use the class `.sm-visible`, e.g.

```html
.mn-table-list
  header
    h3 Name
    h3.sm-visible Email

  .mn-item
    span John Snow
    span.sm-visible snow@iknownothing.com
```




