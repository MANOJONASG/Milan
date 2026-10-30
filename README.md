# ⚽ AC Milan – Il Diavolo

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Sem dependências](https://img.shields.io/badge/depend%C3%AAncias-0-brightgreen)
![Responsivo](https://img.shields.io/badge/layout-responsivo-c8102e)

Site de fã sobre a **Associazione Calcio Milan**, construído do zero com **HTML, CSS e JavaScript puros**, sem frameworks e sem etapa de build. Reúne informações do clube, história, elenco, troféus, ídolos e o estádio San Siro, com foco em design, responsividade e organização do conteúdo.

🔗 **Demo:** `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`

![Prévia do site](docs/screenshots/02-hero.png)

> Projeto sem vínculo oficial com o AC Milan, feito para estudo e portfólio.

## 🎯 Objetivo

Praticar a construção de uma interface completa e polida usando apenas as tecnologias nativas da web, com atenção a identidade visual, desempenho e boas práticas, desde a estrutura semântica até o tema claro e escuro.

## ✨ Destaques

- **Identidade visual do clube**: paleta vermelho, preto e dourado, com tipografia de impacto nos títulos e fonte limpa no texto.
- **Tema claro e escuro** com botão de alternância na barra de navegação.
- **Barra de navegação fixa** com rolagem suave até cada seção.
- **Seção de abertura (hero)** com escudo, chamadas para ação e números de destaque.
- **Elenco dinâmico**: cartões gerados em JavaScript a partir de uma lista de dados, com filtro por posição.
- **Galeria de troféus** com foto e contagem de títulos.
- **Linha do tempo** da história do clube, de 1899 a 2026.
- **Layout responsivo** em CSS Grid e Flexbox, de celulares a telas grandes.
- **Zero dependências**: nenhuma biblioteca, nenhum `npm install`, nenhum build.

## 🖼️ Galeria

| | |
|---|---|
| ![Abertura](docs/screenshots/02-hero.png) | ![Números e clube](docs/screenshots/03-numeros-e-clube.png) |
| **Abertura** com escudo e chamadas para ação | **Números** de destaque e apresentação do clube |
| ![Ficha do clube](docs/screenshots/04-ficha-do-clube.png) | ![História](docs/screenshots/05-historia.png) |
| **Ficha** com os dados principais | **Linha do tempo** da história |
| ![Elenco](docs/screenshots/07-elenco.png) | ![Troféus](docs/screenshots/08-trofeus.png) |
| **Elenco** com filtro por posição | **Troféus** com fotos e contagem |
| ![Ídolos](docs/screenshots/09-idolos.png) | ![San Siro](docs/screenshots/10-san-siro-tema-escuro.png) |
| **Ídolos** eternos | **San Siro** no tema escuro |

## 🧩 Seções do site

| Seção | Conteúdo |
|-------|----------|
| **Início** | Escudo, apresentação e chamadas para explorar o site |
| **Clube** | Identidade, fundação (1899), rivalidade com a Inter e ficha de dados |
| **História** | Linha do tempo de 1899 a 2026, passando pelas eras Sacchi, Capello e Ancelotti |
| **Elenco** | Jogadores da temporada 2026–27 com filtro por posição |
| **Troféus** | Títulos nacionais e internacionais, com fotos |
| **Ídolos** | Maldini, Baresi, Van Basten, Gullit, Kaká, Shevchenko, Pirlo e Rivera |
| **San Siro** | Sobre o estádio, com foto |

## 🛠️ Decisões técnicas

| Decisão | Motivo |
|---------|--------|
| Variáveis CSS para cores | Permitem trocar o tema inteiro mudando poucas linhas |
| Dados do elenco em um array | Separa conteúdo de apresentação e facilita atualizar o elenco |
| Ícones em SVG | Escalam sem perder qualidade e aceitam as cores do tema |
| Imagens organizadas por seção em `assets/images/` | Facilita localizar, trocar e otimizar cada foto |
| Fontes do Google com fontes de reserva | O site continua legível mesmo se as fontes não carregarem |
| `scroll-padding-top` com menu fixo | Os títulos das seções não ficam escondidos atrás da barra |

## ♿ Acessibilidade e boas práticas

- Atributo `lang="pt-BR"` e meta `viewport` configurados
- Estrutura semântica com `nav`, `header`, `section` e `footer`
- Texto alternativo (`alt`) nas imagens
- Tema escuro para reduzir o cansaço visual
- Botões de filtro e de tema nativos (`<button>`), navegáveis pelo teclado

## 🧠 Habilidades demonstradas

- Estruturação de uma página completa em HTML semântico
- CSS moderno: Grid, Flexbox, variáveis, media queries e `clamp()`
- Manipulação do DOM e geração dinâmica de conteúdo com JavaScript
- Design responsivo e tema claro e escuro
- Organização de assets e documentação de créditos das imagens
- Pesquisa e organização de conteúdo em português
- Versionamento com Git e publicação com GitHub Pages

## 📁 Estrutura do projeto

```
.
├── index.html                  # página do site
├── README.md
├── LICENSE
├── .gitignore
├── assets/
│   ├── CREDITS.md              # origem e licença de cada imagem
│   └── images/
│       ├── README.md           # guia de nomes e tamanhos
│       ├── logo/               # escudo da barra de navegação
│       ├── hero/               # imagem do topo
│       ├── historia/           # banner da linha do tempo
│       ├── trofeus/            # uma foto por troféu
│       ├── elenco/             # fotos dos jogadores (opcional)
│       ├── idolos/             # fotos dos ídolos (opcional)
│       └── estadio/            # foto do San Siro
└── docs/
    └── screenshots/            # capturas de tela usadas neste README
```

## 🚀 Como executar

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
cd SEU-REPOSITORIO
```

Abra o `index.html` no navegador (dois cliques no arquivo). Não é preciso instalar nada.

Se preferir um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## 🌐 Publicar no GitHub Pages

1. Envie o projeto para o GitHub.
2. Vá em **Settings → Pages**.
3. Em **Source**, escolha a branch `main` e a pasta `/ (root)`.
4. Salve e aguarde o endereço do site.

## 🎨 Como personalizar

- **Elenco:** edite a lista de jogadores no bloco `<script>`. Cada item segue o formato `["POSIÇÃO", "Nome", "Descrição"]`.
- **Cores:** altere as variáveis no início do CSS.
- **Fotos:** troque os arquivos em `assets/images/` mantendo os nomes. O guia completo está em [`assets/images/README.md`](assets/images/README.md).
- **Textos e linha do tempo:** edite o HTML de cada seção.

## 🗺️ Próximos passos

- [ ] Criar página individual para cada ídolo
- [ ] Incluir seção com números do Derby della Madonnina
- [ ] Separar CSS e JavaScript em arquivos próprios
- [ ] Consumir os dados do elenco de um arquivo JSON
- [ ] Adicionar fotos dos jogadores do elenco atual
- [ ] Otimizar as imagens para WebP

## 📌 Observações sobre os dados

- Os dados históricos e de troféus refletem a contagem de outubro de 2026.
- O elenco muda a cada janela de transferências. Confira o [site oficial do clube](https://www.acmilan.com) para a lista atualizada.

## ⚖️ Aviso legal e créditos

Projeto de fã, feito para fins educacionais e de portfólio. O nome, o escudo e as cores do AC Milan pertencem ao clube. As fotos pertencem aos seus autores e estão listadas em [`assets/CREDITS.md`](assets/CREDITS.md).

## 👤 Autor

**SEU NOME**

- GitHub: [@SEU-USUARIO](https://github.com/SEU-USUARIO)
- LinkedIn: [seu-perfil](https://www.linkedin.com/in/SEU-PERFIL)
- E-mail: seu-email@exemplo.com

## 📄 Licença

O código é distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE).
