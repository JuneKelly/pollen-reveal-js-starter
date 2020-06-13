# Pollen / Reveal.JS

Open `index.html.pm`, and write your slides.


## Run the Pollen Server


``` sh
$ raco pollen start
```

... then visit `http://localhost:8080`


## Compile

``` sh
$ raco pollen render index.html
```

... then open `index.html` in a browser


## Changing the theme

Open `template.html.p`, and change the `link#theme` element:

``` html
  <link rel="stylesheet" href="dist/theme/simple.css" id="theme">
```


And for syntax highlighting, change the `link#highlight-theme` element:

``` html
  <!-- Theme used for syntax highlighted code -->
  <link rel="stylesheet" href="plugin/highlight/monokai.css" id="highlight-theme">
```
