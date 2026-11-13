# Colunas

Slide de conteúdo principal: título e linha fina alinhados à direita, filete vertical, texto corrido à direita (slides 5 e 6 do PPT). É o único layout com tema claro.

**Você fornece:** título de até duas linhas, linha fina de até ~30 palavras e de um a três parágrafos de texto corrido (até ~140 palavras no total).

```html
<section class="cah-slide cah-colunas" data-theme="escuro"> <!-- ou "claro" -->
  <img class="cah-icone" src="cah-icone.svg" alt="">
  <div class="cah-colunas__lado">
    <h2 class="cah-titulo titulo-secao">Uma marca global,<br>mais clara e moderna</h2>
    <p class="cah-colunas__linha-fina linha-fina">…</p>
  </div>
  <div class="cah-filete"></div>
  <div class="cah-colunas__corpo cah-corpo corpo"><p>…</p><p>…</p></div>
</section>
```

- `data-theme="claro"` troca o fundo para `cinza-claro`, o texto para `azul-logo` e o título para `dourado-escuro`. O título claro tem contraste baixo (2.55:1): mantenha-o em 40px negrito e curto.
- Alterne claro e escuro para dar ritmo a sequências longas; não use claro em dois slides seguidos.
- Sem marcadores (bullets): o PPT usa parágrafos.
