# Texto

Slide de conteúdo com a águia ao fundo: filete vertical, título dourado e um parágrafo à direita (slide 3 do PPT).

**Você fornece:** um título de até duas linhas (`titulo-secao`) e um ou dois parágrafos curtos (`corpo`, até ~60 palavras).

```html
<section class="cah-slide cah-texto" data-theme="escuro">
  <img class="cah-aguia" src="aguia-fundo-conteudo.png" alt="">
  <div class="cah-filete"></div>
  <h2 class="cah-texto__titulo cah-titulo titulo-secao">Governança e crescimento<br>com segurança.</h2>
  <div class="cah-texto__corpo cah-corpo corpo"><p>…</p></div>
</section>
```

- O título quebra em duas linhas por sentido, com `<br>`, como no PPT.
- O lado esquerdo fica vazio de propósito: é onde a águia aparece. Não coloque nada ali.
- Texto mais longo pede o slide Colunas.
