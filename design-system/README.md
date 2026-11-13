Sistema de apresentações do **Carneiro & Hannemann Law** (CAH Law), escritório de advocacia empresarial com atuação internacional em governança, compliance e regulação. As regras vêm do Manual da Marca e do modelo oficial de PowerPoint (`Cah_Adv_PPT.pptx`). Toda apresentação parte de um dos sete layouts de slide deste sistema.

## Voz e conteúdo

- Escreva em português do Brasil, registro formal e direto. O escritório fala na primeira pessoa do plural: "Atuamos…", "Nossa experiência…", "Nossa marca evoluiu…".
- A metáfora da marca é a águia-real: visão ampla, precisão, força para sustentar a rota. Use-a com parcimônia, no máximo uma vez por apresentação. Exemplo real: "Atuamos com a mesma lógica de uma águia-real: visão ampla para antecipar cenários, precisão para decidir rápido e força para sustentar a rota até o resultado."
- Títulos em frase comum (só a primeira letra maiúscula), em duas linhas que se completam: "Governança e crescimento / com segurança.", "Uma marca global, / mais clara e moderna".
- Frases de efeito em CAIXA ALTA, sem ponto final: "VISÃO DE LONGO ALCANCE, EXECUÇÃO PRECISA".
- Texto em parágrafos, sem marcadores, sem emoji, sem exclamação. Termos da casa: governança, compliance, regulação, crescimento em escala global, solidez, credibilidade.
- O nome se escreve "Carneiro & Hannemann Law" por extenso e "CAH Law" na forma curta. Contato padrão: `+55 41 3359-5190  //  www.cah.law`.

## Cores

A marca tem duas cores: azul e dourado. Nos slides, o azul é sempre o fundo e o dourado é sempre título, filete ou grafismo.

- Fundo dos slides: `fundo` (tema escuro = `azul-fundo` #032533). O tema claro (`cinza-claro`) só existe no layout Colunas.
- Títulos: `titulo` (escuro = `dourado-claro`, claro = `dourado-escuro`).
- Texto corrido: `texto`; linha fina: `texto-linha-fina`.
- Filetes verticais: `filete` (`azul-filete`), 1.5px. No encerramento o filete é `filete-rodape` (dourado).
- Faixas diagonais: `faixa` (`dourado-escuro`).
- `azul-institucional` (Pantone 303C) e `dourado-institucional` (Pantone 8384C) são as referências oficiais do manual para impressão. Os arquivos de logotipo usam `azul-logo` e `dourado-logo`, e o PPT usa `azul-fundo`. Não "corrija" um pelo outro: cada um vale no seu suporte.
- Não crie cores novas, degradês, transparências ou tons intermediários. A única textura é a foto da águia.

Contraste: `texto` e `texto-linha-fina` passam de 9:1 nos dois temas; `dourado-claro` sobre `azul-fundo` dá 6.17:1. O título do tema claro (`dourado-escuro` sobre `cinza-claro`) dá só 2.55:1. É o valor exato do PPT, mantido, então use-o apenas em `titulo-secao` (40px negrito) e nunca em texto menor.

## Tipografia

Uma família só: **Arsenal** (regular, itálico, negrito, negrito itálico), também disponível no Google Fonts. Os arquivos estão em `fonts/`.

- Títulos: `titulo-secao` (negrito itálico, 40px) em `titulo`.
- Frase de efeito: `titulo-frase` (negrito itálico, 48px, caixa alta).
- Chamada acima do texto: `destaque` (negrito itálico, 32px) em `texto`.
- Linha fina: `linha-fina` (itálico, 32px), alinhada à direita sob o título.
- Texto corrido e contato: `corpo` (regular, 28px, entrelinha 1.68), parágrafos separados por `espaco-paragrafo`.
- Rótulos do catálogo: `rotulo`. Rodapé do mestre: `rodape`.
- Os tamanhos estão em px no canvas de 1920 × 1080: cada 1pt do PowerPoint vale 2px. Ao montar um .pptx, divida por dois (títulos 20pt, texto 14pt, frase 24pt).
- Nunca use negrito sem itálico em títulos. Itálico é a marca da voz.

## Layout

- Canvas 16:9, `slide-largura` × `slide-altura` (1920 × 1080). Cantos sempre retos (`raio-nenhum`). Sem sombras, sem caixas, sem cards.
- Slides internos levam o símbolo (`cah-icone.svg`) no canto superior esquerdo, em `margem-icone-x` / `margem-icone-y`, com `icone-largura` × `icone-altura`.
- A composição de conteúdo é assimétrica: título alinhado à direita numa coluna de `coluna-titulo`, um filete vertical, e o texto alinhado à esquerda do outro lado (`espaco-titulo-filete`, `espaco-filete-texto`). O filete começa na altura do título.
- As faixas douradas (`faixas-douradas.svg`) ficam no canto inferior direito, a `margem-faixas` da borda, sangrando para baixo. Aparecem nos slides Frase, Destaque e Marca; não em todos.
- A águia (`Imagens/`) fica sempre no fundo, nunca recortada em caixa. A capa e o encerramento usam a faixa horizontal; Texto e Frase usam o fundo inteiro.
- Sem animações além da transição simples entre slides.

## Os sete layouts

| Layout | Uso | Tema |
| --- | --- | --- |
| `Capa` | Abertura com sigla ou logotipo completo e selo 10 anos | escuro |
| `Texto` | Título e um parágrafo à direita, sobre a águia | escuro |
| `Frase` | Uma frase de efeito em caixa alta | escuro |
| `Colunas` | Título e linha fina, filete, texto corrido | escuro ou claro |
| `Destaque` | Título, filete, chamada e texto | escuro |
| `Encerramento` | Logotipo completo e contato | escuro |
| `Marca` | Catálogo de logotipos e fonte (uso interno) | cinza |

Sequência típica: Capa → Frase → Colunas (escuro) → Colunas (claro) → Texto → Destaque → Encerramento. Cada layout tem seu README com a marcação HTML e o que você precisa fornecer.

## Logotipo

- **Sigla** (CAH LAW) é a versão principal. **Completo** (Carneiro & Hannemann Law) vai na capa formal e no encerramento.
- Sobre `azul-fundo`, use sempre a versão negativa; sobre fundo claro, a positiva.
- Área de proteção: uma margem livre igual à largura do "W" de LAW em todos os lados. Redução máxima: completo 35 × 15mm, sigla 21 × 12mm.
- Nunca redesenhe, recolora, gire, distorça, contorne ou aplique sombra no logotipo. Use os arquivos de `assets/Logotipos/`.
- O selo 10 anos é comemorativo: use o arquivo do selo ao lado da sigla, ou as versões `*-10anos-*`, nunca os dois juntos.

## Iconografia

A marca não tem um sistema de ícones. O único elemento gráfico além do logotipo é o símbolo da águia com estrelas (`cah-icone.svg`) e as faixas douradas. Não use emoji, ícones de bibliotecas (Material, Font Awesome etc.) nem ilustrações. Se um conteúdo pedir pictogramas, monte com tipografia (número em `titulo-secao`, palavra em `destaque`).

## Como usar

1. Carregue `tokens.css` (cores, a família `--font-arsenal`, as classes de estilo de texto como `.titulo-secao` e `.corpo`) e `components/bundle.css` (os layouts `cah-*`).
2. Cada slide é um `<section class="cah-slide cah-<layout>" data-theme="escuro|claro">` com 1920 × 1080; escale o slide inteiro com `transform: scale()` para caber na tela.
3. Copie os logotipos, as faixas e as fotos da águia de `assets/` para o seu projeto. Os SVGs têm a cor gravada: escolha positivo ou negativo pelo fundo.
