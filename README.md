# Minimalist table list

Table list with a minimalist design

<!-- See the [demo](https://codepen.io/darlanmendonca/full/vKqLOx) -->

### Install

With bower

```sh
bower install --save mn-table-list
```

Or just download the main file ```dist/mn-table-list.css``` in your project, and make a reference to their, like:

```html
<link rel="stylesheet" href="path/to/dist/mn-table-list.css">
```


### Usage

Juse use the class `.mn-table-list` in a tag table, and use inside their, thead, and tbody to content.

```html
<table class="mn-table-list">
  <thead>
    <tr>
      <td>Name</td>
      <td>Email</td>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>John Snow</td>
      <td>snow@iknownothing.com</td>
    </tr>
    <tr>
      <td>Khaleesi</td>
      <td>motherofdragons@targaryen.com</td>
    </tr>
  </tbody>
</table>
```


## Responsive

In screens smaller than 600px, only the first td in every line will be displayed. If you want force a td to always be visible, use the class `.sm-visible`, e.g.

```html
<tr>
  <td>Name</td>
  <td class="sm-visible">Email</td>
</tr>

<tr>
  <td>John Snow</td>
  <td class="sm-visible">snow@iknownothing.com</td>
</tr>
```



