# GiseleNeuropdg — Landing Page

> Projeto acadêmico desenvolvido em aula no curso de Análise e Desenvolvimento de Sistemas (ADS) da Faculdade Municipal de Palhoça. A landing page foi escolhida para divulgar o trabalho de Gisele Geremias, que atua como neuropsicopedagoga.

## Sobre o projeto

A landing page institucional da **GiseleNeuropdg** apresenta os serviços de Psicopedagogia e Neuropsicopedagogia, explica a abordagem profissional e disponibiliza canais de contato e acesso ao endereço.

## Tecnologias utilizadas

- **HTML5:** estrutura semântica da página, com elementos como `header`, `main`, `section`, `article` e `footer`.
- **CSS3:** estilos incorporados no próprio arquivo HTML, dentro da tag `<style>`.
- **Links externos:** WhatsApp, e-mail, Instagram e Google Maps.
- **Sem dependências externas aparentes:** o código analisado não importa bibliotecas, frameworks, fontes externas ou scripts JavaScript.

## Estrutura da página

### Cabeçalho e navegação
- Identidade visual “GiseleNeuropdg”.
- Links internos para as seções “Sobre”, “Serviços” e “Contato”.
- Botão “Agendar conversa”, direcionado ao WhatsApp.

### Seção inicial
- Chamada principal: “Aprender é um caminho de possibilidades.”
- Apresentação dos atendimentos para crianças, adolescentes e adultos.
- Botões para contato via WhatsApp e acesso aos serviços.
- Ilustração simbólica construída com texto e CSS, sem imagem externa.

### Sobre mim
- Apresentação de Gisele Geremias e de sua atuação.
- Contextualização de Psicopedagogia e Neuropsicopedagogia.
- Destaque para acolhimento, plano individualizado e parceria entre família e escola.
- Elemento visual com a inicial “G”, usado como ilustração, e não como fotografia.

### Serviços
A seção é organizada em dois cartões principais:

- **Psicopedagogia:** avaliação e intervenção psicopedagógica, estimulação e desenvolvimento cognitivo, alfabetização e letramento, intervenção em matemática, acompanhamento escolar e orientação à família e à escola.
- **Neuropsicopedagogia:** avaliação neuropsicopedagógica, dificuldades de aprendizagem e desenvolvimento, observação de funções cognitivas, indicadores do neurodesenvolvimento, intervenção, desenvolvimento das funções executivas, autorregulação, autonomia, aprendizagem e neurodesenvolvimento, relatórios e devolutivas.

Os detalhes de cada serviço podem ser expandidos ou recolhidos usando os elementos HTML `<details>` e `<summary>`, sem necessidade de JavaScript.

### Abordagem profissional
Destaca a escuta acolhedora, o olhar individualizado, as estratégias práticas e a parceria com a família e a escola.

### Contato e localização
- **Telefone/WhatsApp:** (48) 99139-7202
- **E-mail:** gisele.neuropdg@gmail.com
- **Instagram:** @giseleneuropdg
- **Endereço:** Edifício Hogar Corporate, Av. Barão do Rio Branco, 350, Sala 304, Centro, Palhoça–SC, CEP 88130-100.
- Botão para abrir a localização no Google Maps.

### Rodapé
Apresenta o nome da marca, a frase institucional e o aviso de copyright © 2026.

## Identidade visual

As cores principais são definidas por variáveis CSS dentro de `:root`:

| Variável | Valor | Uso |
|---|---|---|
| `--paper` | `#f7f7ff` | Fundo principal |
| `--white` | `#fff` | Cartões e áreas claras |
| `--ink` | `#17171b` | Texto principal |
| `--muted` | `#5c5b64` | Texto secundário |
| `--wine` | `#9b526c` | Destaques, botões e títulos |
| `--wine-dark` | `#793b52` | Efeito hover dos botões |
| `--line` | `#dedde8` | Bordas e divisórias |
| `--soft` | `#efedf6` | Fundos suaves |

A tipografia combina Georgia/Times New Roman nos títulos com Arial/Helvetica nos textos. O visual utiliza cantos arredondados, sombras suaves, espaçamento amplo e detalhes em tons de vinho e lilás.

## Responsividade e acessibilidade

- A meta tag `viewport` permite adaptar a página à largura do dispositivo.
- A regra `@media(max-width:760px)` reorganiza as principais grades em uma coluna e oculta a navegação textual do cabeçalho em telas estreitas.
- A regra `prefers-reduced-motion: reduce` reduz transições e movimento para usuários que preferem movimento reduzido.
- O documento define o idioma como `pt-BR`, inclui descrição para mecanismos de busca e usa `aria-label` na navegação e na ilustração.
- Links externos abertos em nova aba utilizam `rel="noopener"`.

## SEO e metadados

- **Idioma:** português brasileiro (`pt-BR`).
- **Título da página:** `GiseleNeuropdg | Psicopedagogia e Neuropsicopedagogia`.
- **Descrição:** apresenta os serviços e a localização em Palhoça–SC.
- **Cor do navegador:** definida por `theme-color` em dispositivos compatíveis.

## Como executar

1. Mantenha o arquivo da página com a extensão `.html`.
2. Abra o arquivo em um navegador moderno, como Chrome, Edge ou Firefox.
3. Para publicar, envie o arquivo para um serviço de hospedagem de sites estáticos ou para o servidor/domínio escolhido.

## Onde fazer alterações

- **Textos e seções:** edite o HTML dentro de `<body>`.
- **Cores, fontes, espaçamentos e layout:** altere as regras CSS dentro de `<style>`. Para a paleta, comece pelas variáveis em `:root`.
- **Links e contatos:** atualize os atributos `href` dos links de WhatsApp, e-mail, Instagram e Google Maps e os textos exibidos.
- **Serviços:** procure os elementos `<article class="service-card">` e os respectivos blocos `<details>`.
- **Layout para celular:** ajuste com cuidado a media query `@media(max-width:760px)`.
- **Título e descrição para mecanismos de busca:** edite as tags `<title>` e `<meta name="description">` dentro de `<head>`.

## Observações importantes

- O arquivo analisado contém CSS incorporado e não contém JavaScript.
- A arte principal e o círculo com a inicial “G” são construídos com HTML e CSS; não há fotografias incorporadas no código analisado.
- Os textos sobre indicadores de TDAH, TEA e outros transtornos incluem ressalvas sobre os limites da atuação profissional e a articulação com outros profissionais quando necessário.
- Antes de publicar, confira se o telefone, o e-mail, o Instagram, o endereço e todos os links estão corretos e ativos.
