# Capa

Slide de abertura: o logotipo negativo sobre `azul-fundo`, com a faixa de águia (`Imagens/aguia-faixa-capa.png`) atravessando a metade inferior e o selo 10 anos à direita do logotipo.

**Você fornece:** a versão do logotipo (sigla ou completo) e se o selo 10 anos aparece. Nada de texto: a capa não tem título.

```html
<section class="cah-slide cah-capa" data-theme="escuro">
  <img class="cah-aguia" src="aguia-faixa-capa.png" alt="">
  <img class="cah-capa__logo" src="cah-sigla-negativo.svg" alt="CAH Law">
  <img class="cah-capa__selo" src="cah-selo-10anos.svg" alt="10 anos">
</section>
```

- `cah-capa` usa a sigla (slide 1 do PPT). Acrescente `cah-capa--completo` e troque a imagem por `cah-completo-negativo.svg` para o logotipo completo (slide 2).
- Sempre `data-theme="escuro"`: a imagem da águia só existe sobre azul.
- Não use a versão `cah-sigla-10anos-*` junto com o selo: escolha um ou outro.
- Não escreva título, data ou nome do cliente sobre a capa; isso vai no slide seguinte.
