# TAREA FLEX

## Ejemplo 1:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
            display: block;
            }

            .contenedorFlex {
            display: flex;
            background: #F6EBC6;
            }
        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
![ejemplo_1](image.png)
___
## Ejemplo 2:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
            display: block;
            }

            .contenedorFlex {
            display: flex;
            background: #F6EBC6;
            }

            p {
                max-width: 23%;
                border: 1px solid gray;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 3:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
            display: block;
            }

            .contenedorFlex {
            display: flex;
            background: #F6EBC6;
            flex-flow: row wrap;
            }

            p {
                max-width: 23%;
                border: 1px solid gray;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 4:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
            display: block;
            }

            .contenedorFlex {
            display: flex;
            background: #F6EBC6;
            flex-flow: row wrap;
            height: 400px;
            }

            p {
                max-width: 23%;
                border: 1px solid gray;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 5:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
            display: block;
            }

            .contenedorFlex {
            display: flex;
            background: #F6EBC6;
            flex-flow: row wrap;
            height: 400px;
            justify-content: flex-start;
            }

            p {
                max-width: 23%;
                border: 1px solid gray;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 6:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
            display: block;
            }

            .contenedorFlex {
            display: flex;
            background: #F6EBC6;
            flex-flow: row wrap;
            height: 400px;
            justify-content: flex-start;
            align-items: flex-start;
            }

            p {
                max-width: 23%;
                border: 1px solid gray;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 7:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
            display: block;
            }

            .contenedorFlex {
            display: flex;
            background: #F6EBC6;
            flex-flow: row wrap;
            height: 400px;
            justify-content: flex-start;
            align-items: flex-start;
            }

            p {
                flex: 0 0 20%;
                border: 1px solid gray;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 8:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
                display: block;
            }


            .contenedorFlex {
                display: flex;
                flex-flow: row wrap;
                justify-content: flex-start;
                align-items: stretch;
                background: #F6EBC6;
            }


            p:not(:nth-of-type(1)){
                border: 1px solid gray;
                flex: 1 0 20%;
            }


            p:nth-of-type(1){
                border: 1px solid gray;
                flex: 7 0 20%;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 9:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
                display: block;
            }


            .contenedorFlex {
                display: flex;
                flex-flow: row wrap;
                justify-content: flex-start;
                align-items: stretch;
                background: #F6EBC6;
            }


            p:not(:nth-of-type(1)){
                border: 1px solid gray;
                flex: 0 1 400px;
            }


            p:nth-of-type(1){
                border: 1px solid gray;
                flex: 0 5 400px;
            }

        </style>
    </head>
    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
___
## Ejemplo 10:
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8" />
        <meta name="author" content="juan carlos p.r."/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <title>inicios con flex</title>
        <style type="text/css">

            header, section, footer, aside, nav, main, article, figure {
                display: block;
            }


            .contenedorFlex {
                display: flex;
                flex-flow: row wrap;
                justify-content: flex-start;
                align-items: stretch;
                background: #F6EBC6;
            }


            p {
                border: 5px solid gray;
                margin: 3px;
                flex: 1 0 45%;
            }

        </style>
    </head>

    <body>
        <main class="contenedorFlex">
            <p>1 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum incidunt, nostrum! lorem</p>
            <p>2 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore ipsa laudantium ea.</p>
            <p>3 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam laborum provident pariatur aspernatur? Lorem ipsum dolor sit amet, consectetur adipisicing elit. Id maiores reiciendis quod sit cupiditate debitis amet mollitia, recusandae consequatur alias!</p>
            <p>4 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam voluptatem tempore blanditiis facere natus.</p>
            <p>5 Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates, animi! Reiciendis, sequi, quasi. Totam, minus. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatum, eius, velit reiciendis molestiae vitae ipsam.</p>
        </main>
    </body>
</html> 
```
