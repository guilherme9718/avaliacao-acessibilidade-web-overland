### Correção arquivo api_002.js
Não foi encontrado nenhum erro grave, somente warnings. Foram corrigidos alguns deles abaixo:

1. **tirado agrupamento de função por parênteses**
~~~js
(function () {
    ...
}).call(this)
~~~
para
~~~js
func = function () {
    ...
};

func..call(this);
~~~

2. **Declarado uma variável por linha**
~~~js
var domain, url, xhr;
~~~
para
~~~js
var domain; 
var url; 
var xhr;
~~~

3. **Checagem de null com operador `===`**
~~~js
if (opts == null)
~~~
para
~~~js
if (opts === null)
~~~