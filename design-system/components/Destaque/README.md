# Destaque

Variação do slide Colunas em que o lado direito abre com uma chamada em negrito itálico antes do texto (slide 7 do PPT). Tem as faixas douradas no canto.

**Você fornece:** título de até duas linhas, uma chamada de uma linha (`destaque`) e um parágrafo (`corpo`, até ~70 palavras).

```html
<section class="cah-slide cah-destaque" data-theme="escuro">
  <img class="cah-icone" src="cah-icone.svg" alt="">
  <h2 class="cah-destaque__titulo cah-titulo titulo-secao">Governança e crescimento<br>com segurança.</h2>
  <div class="cah-filete"></div>
  <div class="cah-destaque__texto">
    <h3 class="destaque">Visão de longo alcance, execução precisa</h3>
    <div class="cah-corpo corpo"><p>…</p></div>
  </div>
  <img class="cah-faixas" src="faixas-douradas.svg" alt="">
</section>
```

- Só tema escuro.
- A chamada repete ou resume a tese do slide; não é um segundo título.
