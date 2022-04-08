# webdev

### viewport

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### responsive design

```
@media (min-width: 600px){
    body {
        background-color: red;
    }
}
```

### flexbox
```
        #container{
            display:flex;
            flex-wrap: wrap;
        }

        #container > div {
            background-color: springgreen;
            font-weight: bold;
        }

    <div id="container">
        <div>1. This is sample</div>
        <div>2. This is sample</div>
        <div>3. This is sample</div>
        <div>4. This is sample</div>
    </div>
    
    
```

### grid

```
    <div id="grid">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>
        <div class="grid-item">4</div>
    </div>
    
      #grid{
            background-color: green;
            display:grid;
            padding: 20px;
            grid-column-gap: 20px;
            grid-row-gap: 10px;
            grid-template-columns: 200px 200px auto;
        }

        .grid-item {
            background-color: white;
            padding:20px;
        }

```

### Specificity

1. inline
2. id
3. class
4. type

### CSS Selectors

|css|desc|
|---|---|
|a,b|Multiple element selector|
|a b|Descendant selector e.g. ul li|
|a > b|child selector e.g. ul > li|
|a + b|adjacent selector|
|[a=b]|attribute selector e.g. a[href="https://index.com"]{color:blue;}|
|a:b|pseudoclass selector|
|a::b|pseudoelement selector|

* pseudoclass
```
        button {
            font-weight:bold;
            background-color: green;
        }

        button:hover {
            background-color: orange;
        }
        
        <button>Click Me</button>
```

# SASS

* convert sass to css
```
sass variables.scss:variables.css
```

```
    <link rel="stylesheet" href="variables.scss">


```

```
$color:red;

ul {
  background-color: $color;
}
```