# Sankey Diagrams

Sankey diagrams library based on d3. 

## Install

```sh
npm install https://github.com/ONE-LOGIC/d3-sankey
```

Add Javascript:
```html
<script src="node_modules/d3-sankey/releases/sankey_1.4_2013_03_12.js"></script>
```

## Usage

Define the sankey chart
```js
var sankey = d3.sankey()
    .size([width, height])
    .nodeWidth(15)
    .nodePadding(10)
    .nodes(myNodes)
    .links(myLinks)
    .layout(32);
```

Create the links
```
var path = sankey.link();
```