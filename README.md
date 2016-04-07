jQuery Bootgrid Plugin - Implementações
============

Grid / Tabela utilizando o plugin jQuery Bootgrid, mas com algumas implementações.

## Como Usar

**jQuery Bootgrid** é um componente escrito para **jQuery** e **Bootstrap** (Bootstrap não é necessariamente requerido).

Tudo que você precisa pra iniciar rapidamente é:

1. Incluir as bibliotecas **jQuery**, **jQuery Bootgrid** e **Bootstrap** no seu código HTML.
2. Definir sua tabela e suas colunas adicionando o atributo 'data-column-id'.
3. Especificar a URL para preencher a tabela e alterar a opção de ajax para 'true' via data API.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Demo</title>
        <meta charset="utf-8">
        <!-- Styles -->
        <link href="bootstrap.css" rel="stylesheet">
        <link href="jquery.bootgrid.css" rel="stylesheet">
    </head>
    <body>
        <table id="grid" data-toggle="bootgrid" data-ajax="true" data-url="/api/data/basic" class="table table-condensed table-hover table-striped">
            <thead>
                <tr>
                    <th data-column-id="id">ID</th>
                    <th data-column-id="name">Sender</th>
                </tr>
            </thead>
        </table>
        <!-- Scripts -->
        <script src="jquery.js"></script> 
        <script src="jquery.bootgrid.js"></script>
    </body>
</html>
```

> Para mais informações [verifique a documentação](http://www.jquery-bootgrid.com/Documentation).

### Exemplos

Você pode encontrar alguns exemplos [aqui](http://www.jquery-bootgrid.com/Examples).

## License

Copyright (c) 2014-2015 Rafael J. Staib Licensed under the [MIT license](https://github.com/rstaib/jquery-bootgrid/blob/master/LICENSE.txt).

