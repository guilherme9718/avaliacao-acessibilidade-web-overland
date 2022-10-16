# Avaliação de acessibilidade web

Guilherme Oliveira - 2127954
Tiago Silva - 2023644

# Descrição do trabalho

Website escolhido para avaliação foi 
~~~
https://overland-game.com/
~~~

Trata-se de um jogo que se diz acessível para pessoas com dislexia.

## Correções dos arquivos .html

### Correção arquivo a.html
* Adicionado `<!DOCTYPE html>` no começo
* Adicionado `<title>a</title>`
* Adicionado atributo `lang="en-us"`

### Correção do arquivo Overland.html
* Retirado os comentários do início
* Retirado a linha 7: 
~~~
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
~~~
* Retirado "chrome=1" da linha 10
* Substitiído o segmento da linha 244: 
~~~
"<iframe title="o desafio reCAPTCHA expira em dois minutos" src="Overland_arquivos/bframe.html" style…llow-modals allow-popups-to-escape-sandbox allow-storage-access-by-user-activation" frameborder="0">"
~~~
Por:
~~~
"<iframe style="overflow:hidden;">"
~~~
* Substitiído o segmento da linha 307: 
~~~
"<iframe title="o desafio reCAPTCHA expira em dois minutos" src="Overland_arquivos/bframe.html" style…llow-modals allow-popups-to-escape-sandbox allow-storage-access-by-user-activation" frameborder="0"></iframe>"
~~~
Por:
~~~
"<iframe style="overflow:hidden;"></iframe>"
~~~

### Correção do anchor.html
* Substituído o segmento da linha 2:
~~~
pt_br
~~~
Por:
~~~
pr-br
~~~
* Substituída a linha 185:
~~~
</script><div id="rc-anchor-container" class="rc-anchor rc-anchor-normal rc-anchor-light"><div id="recaptcha-accessible-status" class="rc-anchor-aria-status" aria-hidden="true">reCAPTCHA requer verificação. </div><div class="rc-anchor-error-msg-container" style="display:none"><span class="rc-anchor-error-msg" aria-hidden="true"></span></div><div class="rc-anchor-content"><div class="rc-inline-block"><div class="rc-anchor-center-container"><div class="rc-anchor-center-item rc-anchor-checkbox-holder"><span class="recaptcha-checkbox goog-inline-block recaptcha-checkbox-unchecked rc-anchor-checkbox" role="checkbox" aria-checked="false" id="recaptcha-anchor" tabindex="0" dir="ltr" aria-labelledby="recaptcha-anchor-label"><div class="recaptcha-checkbox-border" role="presentation"></div><div class="recaptcha-checkbox-borderAnimation" role="presentation"></div><div class="recaptcha-checkbox-spinner" role="presentation"><div class="recaptcha-checkbox-spinner-overlay"></div></div><div class="recaptcha-checkbox-checkmark" role="presentation"></div></span></div></div></div><div class="rc-inline-block"><div class="rc-anchor-center-container"><label class="rc-anchor-center-item rc-anchor-checkbox-label" aria-hidden="true" role="presentation" id="recaptcha-anchor-label"><span aria-live="polite" aria-labelledby="recaptcha-accessible-status"></span>Não sou um robô</label></div></div></div><div class="rc-anchor-normal-footer"><div class="rc-anchor-logo-portrait" aria-hidden="true" role="presentation"><div class="rc-anchor-logo-img rc-anchor-logo-img-portrait"></div><div class="rc-anchor-logo-text">reCAPTCHA</div></div><div class="rc-anchor-pt"><a href="https://www.google.com/intl/pt-BR/policies/privacy/" target="_blank">Privacidade</a><span aria-hidden="true" role="presentation"> - </span><a href="https://www.google.com/intl/pt-BR/policies/terms/" target="_blank">Termos</a></div></div>
~~~
Por:
~~~
"</script><div id="rc-anchor-container" class="rc-anchor rc-anchor-normal rc-anchor-light"><div id="recaptcha-accessible-status" class="rc-anchor-aria-status" aria-hidden="true">reCAPTCHA requer verificação. </div><div class="rc-anchor-error-msg-container" style="display:none"><div class="rc-anchor-error-msg" aria-hidden="true"></div></div><div class="rc-anchor-content"><div class="rc-inline-block"><div class="rc-anchor-center-container"><div class="rc-anchor-center-item rc-anchor-checkbox-holder"><div class="recaptcha-checkbox goog-inline-block recaptcha-checkbox-unchecked rc-anchor-checkbox" role="checkbox" aria-checked="false" id="recaptcha-anchor" tabindex="0" dir="ltr" aria-labelledby="recaptcha-anchor-label"><div class="recaptcha-checkbox-border" role="presentation"></div><div class="recaptcha-checkbox-borderAnimation" role="presentation"></div><div class="recaptcha-checkbox-spinner" role="presentation"><div class="recaptcha-checkbox-spinner-overlay"></div></div><div class="recaptcha-checkbox-checkmark" role="presentation"></div></div></div></div></div><div class="rc-inline-block"><div class="rc-anchor-center-container"><label class="rc-anchor-center-item rc-anchor-checkbox-label" aria-hidden="true" id="recaptcha-anchor-label"><span aria-live="polite" aria-labelledby="recaptcha-accessible-status"></span>Não sou um robô</label></div></div></div><div class="rc-anchor-normal-footer"><div class="rc-anchor-logo-portrait" aria-hidden="true" role="presentation"><div class="rc-anchor-logo-img rc-anchor-logo-img-portrait"></div><div class="rc-anchor-logo-text">reCAPTCHA</div></div><div class="rc-anchor-pt"><a href="https://www.google.com/intl/pt-BR/policies/privacy/" target="_blank">Privacidade</a><div aria-hidden="true" role="presentation"> - </div><a href="https://www.google.com/intl/pt-BR/policies/terms/" target="_blank">Termos</a></div></div></div><iframe style="display: none;"></iframe></body></html>"
~~~

### Correção do bframe.html
* Substituído o segmento da linha 2:
~~~
pt_br
~~~
Por:
~~~
pr-br
~~~

### Descrição alternativa das imagens
Descrições alternativas que não continham no site

~~~html
<img alt="logo Overland" src="Overland_arquivos/logo.png">
~~~
<img alt="logo Overland" src="Overland_arquivos/logo.png">

~~~html
<img alt="two survivals and a dog. All of then behind a car with gas gallon, medkit and toolbox on top of it" src="Overland_arquivos/group2.png">
~~~

<img alt="two survivals and a dog. All of then behind a car with gas gallon, medkit and toolbox on top of it" src="Overland_arquivos/group2.png">

~~~html
<img alt="apple logo with description find it on arcade" src="Overland_arquivos/Apple_Arcade_Badge_US.svg" style="margin-top: 20px; width: 190px; height: 90px;">
~~~

<img alt="apple logo with description find it on arcade" src="Overland_arquivos/Apple_Arcade_Badge_US.svg" style="margin-top: 20px; width: 190px; height: 90px;">

~~~html
<img class="icon" alt="gas gallon icon" src="Overland_arquivos/gas.png">
~~~
<img class="icon" alt="gas gallon icon" src="Overland_arquivos/gas.png">

~~~html
<img class="icon" alt="horizontal white bar" src="Overland_arquivos/break.png">
~~~
<img class="icon" alt="horizontal white bar" src="Overland_arquivos/break.png">

~~~html
<img class="icon" alt="map icon" src="Overland_arquivos/map.png">
~~~
<img class="icon" alt="map icon" src="Overland_arquivos/map.png">

~~~html
<img class="icon" alt="campfire icon" src="Overland_arquivos/campfire.png">
~~~
<img class="icon" alt="campfire icon" src="Overland_arquivos/campfire.png">

~~~html
<img alt="windmill with gass around and a gas gallon next to it" src="Overland_arquivos/windmill.png">
~~~
<img alt="windmill with gass around and a gas gallon next to it" src="Overland_arquivos/windmill.png">

## Correções dos arquivos .css

O único erro encontrado no arquivo main_launch.css apontado pelo validador
~~~
Erro de valor : font-weight 600px não é um valor font-weight : 600px
~~~

Na linha 258 foi atualizado de `font-weight: 600px;` para `font-weight: 600;`

## Correções dos arquivos .js

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

## Correções de acessibilidade

### validador WAVE
* Adicionado linguagem `en-us` em `lang="en-us"`
* Todos os erros de texto alternativos para imagem foram corrigidos
* Alguns botões estão com pouco constraste com texto na cor <span style="color:#FAF7E5">#FAF7E5</span> e background <span style="color:#F9423A;">#F9423A</span>
Foi ajustado isso mudando o background para a cor <span style="color:#952622;">#952622</span>
* Corrigido texto com head`h3` sem head `h2`, mudado para head `h2`

### Falsos positivos
* FALSO POSITIVO: o software indicou que há links sem texto, porém os links não são clicáveis, eles são imagens.

* FALSO POSITIVO: link para vídeo do youtube. O problema não é o link em si, o problema é que o vídeo não tem narração, é somente visual e não tem legendas.