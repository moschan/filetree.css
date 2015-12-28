# filetree.css
Implement function and style of file tree view using CSS only. No JavaScript.

[![NPM](https://nodei.co/npm/filetree-css.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/filetree-css/)

<h1 align="center">
  <img src="./doc/demo.gif" alt="demo giff">
</h1>

# Installation

in Cli

```
npm i firetree-css --save
```

in HTML

```
<link rel="stylesheet" href="./node_modules/firetree-css/filetree.css">
```


# Usage

```
<ul class="filetree">
  <li>
    <input type="checkbox" id="level1-1">
    <label for="level1-1">js</label>
    <ul>
      <li>
        <input type="checkbox" id="level2-1">
        <label for="level2-1">lib</label>
        <ul>
          <li>some.js</li>
          <li>any.js</li>
        </ul>
      </li>
      <li>my.js</li>
      <li>core.js</li>
    </ul>
  </li>
  <li><input type="checkbox">
    <input type="checkbox" id="level1-2">
    <label for="level1-2">css</label>
    <ul>
      <li>my.css</li>
      <li>core.css</li>
    </ul>
  </li>
</ul>
```

# Contributing
Welcome :)

# License
MIT

