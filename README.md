<!-- ========================= HERO ========================= -->

<h1 align="center">Richard R. Araújo</h1>

<p align="center">
  <strong>Desenvolvimento Web • Front-End • JavaScript • UI/UX • Dados</strong>
</p>

<p align="center">
  <a href="https://github.com/Richter06">
    <img src="https://img.shields.io/badge/GitHub-Richter06-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://www.linkedin.com/in/richard-r-araújo/">
    <img src="https://img.shields.io/badge/LinkedIn-Richard%20R.%20Araújo-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=20&duration=2800&pause=800&color=7C3AED&center=true&vCenter=true&width=850&lines=Transformando+ideias+em+produtos+web;Interfaces+%2B+lógica+%2B+dados;Do+HTML%2FCSS%2FJS+ao+Node%2FReact%2F3D;Aprendendo+construindo+projetos+reais" alt="Apresentação animada" />
</p>

---

## 👋 Sobre mim

Sou estudante de **Análise e Desenvolvimento de Sistemas** e desenvolvedor em início de carreira, construindo minha base principalmente em **desenvolvimento web**.

Meu caminho começou pelo Front-End e foi avançando para problemas cada vez mais amplos: interfaces responsivas, consumo de APIs, manipulação de dados, CRUD, autenticação, armazenamento de arquivos, análise de código, segurança web, simulações, jogos e experiências 3D no navegador.

Também tenho uma base paralela em **design e UI/UX**, o que influencia bastante a forma como penso meus projetos: não quero apenas fazer uma página funcionar — quero entender **como ela se apresenta, como as pessoas interagem com ela e como o código sustenta essa experiência**.

Hoje meu trabalho prático se concentra em:

- **Front-End:** HTML5, CSS3, JavaScript, responsividade, acessibilidade e UI/UX;
- **React:** componentização, props, estado, hooks, consumo de APIs e construção de SPAs;
- **Back-End:** Node.js, Express, APIs REST e lógica de servidor;
- **Dados:** SQL, MySQL, PostgreSQL, SQLite e Supabase;
- **Web:** autenticação, CRUD, upload de arquivos, segurança básica e deploy;
- **Visual:** Figma, Photoshop, CorelDRAW e Canva;
- **3D/WebGL:** Three.js, React Three Fiber e Drei em projetos experimentais;
- **Ferramentas:** Git, GitHub, Vite, Cloudflare, Vercel e Render;
- **IA no desenvolvimento:** uso de ferramentas de IA para pesquisa, exploração, debugging, documentação e produtividade.

> **Importante:** React, Tailwind, Vue e algumas ferramentas de 3D/motion fazem parte da minha evolução atual. Eu prefiro mostrar isso com honestidade do que me apresentar como especialista em tecnologias que ainda estou aprofundando.

🌎 **Inglês avançado para documentação técnica, GitHub, fóruns e estudos.**

---

## 🧠 Como eu gosto de construir

Meu portfólio não segue um único tipo de projeto.

Eu gosto de alternar entre problemas diferentes porque cada projeto força uma habilidade nova:

```text
INTERFACE
   ↓
INTERAÇÃO
   ↓
LÓGICA
   ↓
DADOS
   ↓
BACK-END
   ↓
SEGURANÇA
   ↓
EXPERIÊNCIA
```

É por isso que meu GitHub tem desde landing pages editoriais até crawler/analisador web, aplicações full-stack, jogos baseados em grafos e interfaces 3D.

---

# 🏆 5 projetos que melhor representam minha evolução

A seleção abaixo considera principalmente:

**complexidade técnica + variedade de conceitos + arquitetura + tecnologias utilizadas + quantidade de problemas resolvidos.**

Não é uma lista baseada apenas em aparência visual.

---

## 01 — Rouxinol

### Experiência digital comercial com React + 3D

<a href="https://github.com/Richter06/rouxinol">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-ROUXINOL-111A4A?style=for-the-badge&logo=github&logoColor=white" alt="Rouxinol no GitHub" />
</a>

**Nível de complexidade: muito alto**

O Rouxinol é o projeto que melhor representa minha fase atual de exploração de **experiências digitais complexas no Front-End**.

A proposta é criar uma marca comercial de presença digital com uma interface autoral, narrativa e orientada à experiência — não uma página convencional de agência.

### O que existe no projeto

- arquitetura em React;
- Vite;
- React Three Fiber;
- Three.js;
- Drei;
- múltiplas cenas/modelos 3D;
- modelos `.glb`;
- desktop, celular e micro-ondas como elementos narrativos;
- animações baseadas em scroll;
- Motion;
- GSAP;
- HLS.js;
- componentes independentes por seção;
- sistema de conteúdo separado da apresentação;
- backgrounds e mídia próprios;
- lazy loading de recursos pesados;
- preocupação com performance de bundles;
- páginas/modelos navegáveis;
- composição visual responsiva.

### Modelos 3D utilizados

```text
desktop.glb
phone.glb
microwave.glb
purple_planet.glb
```

### Tecnologias

```text
React
Vite
JavaScript / JSX
Three.js
React Three Fiber
@react-three/drei
Motion
GSAP
HLS.js
Tailwind CSS / Vite plugin
Lucide React
CSS
WebGL
```

**O principal aprendizado aqui:** transformar tecnologia gráfica em parte da narrativa da interface, em vez de usar 3D apenas como decoração.

---

## 02 — FangyScraper

### Web Scraper + análise estática + segurança

<a href="https://github.com/Richter06/FangyScraper">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-FANGYSCRAPER-111827?style=for-the-badge&logo=github&logoColor=white" alt="FangyScraper no GitHub" />
</a>

**Nível de complexidade: muito alto**

O Fangy começou como um crawler e evoluiu para uma ferramenta de inspeção técnica de páginas web.

Ele recebe uma URL, coleta o conteúdo acessível e transforma esse material em um relatório sobre **HTML, recursos, JavaScript, CSS e indicadores de segurança**.

### O que torna o projeto tecnicamente interessante

- servidor HTTP com Express;
- crawler HTTP/HTTPS;
- parsing de HTML com Cheerio;
- descoberta de recursos externos;
- análise de JavaScript com AST;
- Acorn + acorn-walk;
- análise de CSS com PostCSS;
- Safe Parser para CSS;
- análise de headers e formulários;
- inspeção de recursos;
- proteção contra destinos locais/privados;
- validação de URL;
- limites de tamanho;
- limites de recursos;
- timeout de requisições;
- dashboard para apresentar os resultados;
- arquitetura modular de analisadores.

### Fluxo

```text
URL
 │
 ▼
Validação
 │
 ▼
Crawler HTTP/HTTPS
 │
 ▼
HTML
 ├──────────────► Cheerio ──────► DOM
 │
 ├──────────────► Security ─────► Indicadores
 │
 └── Recursos externos
        │
        ├── JavaScript ──► AST / Acorn
        │
        └── CSS ─────────► PostCSS
                  │
                  ▼
             Relatório
                  │
                  ▼
              Dashboard
```

### Tecnologias

```text
Node.js
Express
Cheerio
Acorn
acorn-walk
PostCSS
postcss-safe-parser
ipaddr.js
JavaScript
HTML
CSS
REST
Web Security
```

**O principal aprendizado aqui:** sair do consumo de páginas para **analisar a estrutura e o código que existe por trás delas**.

---

## 03 — Little Bee • Arte & Pintura

### Aplicação web full-stack com autenticação, CRUD e armazenamento

<a href="https://github.com/Richter06/paginaDeArtesVisuais">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-LITTLE%20BEE-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Little Bee no GitHub" />
</a>

**Nível de complexidade: alto**

O Little Bee começou como um projeto visual e cresceu para uma aplicação com **front-end público + área administrativa + API + autenticação + banco de dados + armazenamento de imagens**.

### O que existe

- galeria dinâmica de obras;
- painel administrativo;
- login;
- sessões;
- proteção de rotas;
- CRUD de pinturas;
- API REST;
- upload de imagens;
- validação de MIME type;
- limite de tamanho de arquivo;
- Supabase Database;
- Supabase Storage;
- Express;
- Multer;
- Helmet;
- rate limiting;
- cookies com atributos de segurança;
- integração com Cloudflare Workers;
- assets estáticos;
- separação entre camada pública e administrativa.

### Arquitetura

```text
                    NAVEGADOR
                       │
                       ▼
              Cloudflare Worker
                 │           │
          API / Auth       Assets
                 │
                 ▼
              Supabase
             ┌────┴────┐
             │         │
          Database   Storage
             │         │
             └────┬────┘
                  │
             pinturas
```

Também mantenho uma implementação local com **Node.js + Express**, permitindo trabalhar com a aplicação fora do ambiente de produção.

### Tecnologias

```text
HTML5
CSS3
JavaScript
Node.js
Express 5
REST API
Supabase
Multer
Express Session
Helmet
Rate Limit
Cloudflare Workers
SQLite
Git
```

**O principal aprendizado aqui:** construir uma aplicação que precisa lidar com **usuários, dados, arquivos, permissões e regras de negócio**, e não apenas com interface.

---

## 04 — Alien Terminal

### Simulação de sobrevivência baseada em grafos

<a href="https://github.com/Richter06/AlienTerminal">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-ALIEN%20TERMINAL-39FF88?style=for-the-badge&logo=github&logoColor=black" alt="Alien Terminal no GitHub" />
</a>

**Nível de complexidade: alto**

Alien Terminal é um jogo de sobrevivência para navegador inspirado em interfaces de computador retrofuturistas.

O projeto parece simples na superfície — um terminal — mas sua lógica é baseada em uma **simulação de estado com movimentação em grafo, aleatoriedade, pathfinding e múltiplos comportamentos da ameaça**.

### Sistemas implementados

- sistema de turnos;
- mapa representado como grafo;
- movimentação da criatura;
- RADAR baseado em última localização conhecida;
- bloqueio de conexões;
- bateria dos bloqueios;
- dispositivos de som;
- perseguição por rota;
- pathfinding;
- sistema de ventilação;
- estado `normal`;
- estado `inVent`;
- eventos aleatórios;
- vitória;
- game over;
- geração procedural de elementos da partida;
- mapa renderizado com React + SVG;
- terminal de comandos.

### Modelo lógico

```text
                    ┌──────────────┐
                    │   GAME STATE │
                    └──────┬───────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
       PLAYER            ALIEN            TURN
          │                │                │
          │         ┌──────┴──────┐         │
          │         ▼             ▼         │
          │      NORMAL         IN VENT     │
          │         │             │         │
          │         └──────┬──────┘         │
          │                ▼                │
          └──────────── GAME ENGINE ─────────┘
                           │
                           ▼
                     React / SVG UI
```

### Tecnologias

```text
React 19
Vite 8
JavaScript
React Hooks
SVG
CSS
Graph / Pathfinding
State-driven simulation
Cloudflare Workers
```

**O principal aprendizado aqui:** separar uma **engine de regras** da interface e modelar comportamentos complexos de forma previsível.

---

## 05 — Pokédex React

### React + API REST + 3D no navegador

<a href="https://github.com/Richter06/pokedexReact">
  <img src="https://img.shields.io/badge/REPOSITÓRIO-POKÉDEX%20REACT-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="Pokédex React no GitHub" />
</a>

**Nível de complexidade: médio/alto**

Foi um dos projetos em que comecei a aprofundar **React de verdade**, combinando componentização, estado, consumo de API e renderização 3D.

### Funcionalidades

- pesquisa de Pokémon;
- consumo da PokéAPI;
- estados de loading e erro;
- componentização;
- props;
- hooks;
- dados dinâmicos;
- estatísticas;
- habilidades;
- movimentos;
- sistema visual por tipo;
- Pokébola 3D;
- modelo `.glb`;
- rotação e flutuação;
- iluminação;
- sombra de contato;
- interação com ponteiro;
- suporte a `prefers-reduced-motion`.

### Arquitetura

```text
App
├── Navbar
│   └── Pokeball3D
├── SearchBar
├── Loading
└── PokemonCard
```

### Tecnologias

```text
React 19
Vite 8
JavaScript / JSX
Three.js
React Three Fiber
Drei
PokéAPI
ESLint
CSS
WebGL
Cloudflare Workers
```

**O principal aprendizado aqui:** transformar dados externos em uma interface React organizada e começar a integrar **renderização 3D em aplicações reais**.

---

# 🎨 Outros projetos que fazem parte da evolução

Os cinco acima são os que melhor representam minha complexidade técnica atual, mas eles não contam a história inteira.

### BRASA
Landing page editorial para um restaurante fictício, construída em React com forte uso de **vídeo, storytelling visual, scroll-driven interactions, IntersectionObserver, requestAnimationFrame, responsividade e microinterações**.

### CUT CLUB
Landing page editorial para uma barbearia fictícia, desenvolvida com **React + Vite**, CSS, IntersectionObserver, parallax, estado local e `prefers-reduced-motion`. O projeto explora direção de arte, tipografia e composição assimétrica sem depender de bibliotecas externas de animação.

### Portfólio pessoal
Projeto que reúne **HTML, CSS, JavaScript, Three.js, WebGL, GLTF, IntersectionObserver, SEO, acessibilidade, responsividade e interação com mídia**.

### Clínica Vita+
Projeto orientado a **CRUD, organização de dados, dashboard, métricas, gráficos, prontuários, consultas e geração de relatórios**, desenvolvido para exercitar lógica de negócio.

### Mayk VS Aliens
Projeto de programação interativa com **JavaScript, Canvas, game loop, movimentação, eventos, pontuação, áudio e lógica de jogo**.

### Mitologias
Um dos meus projetos mais antigos. Hoje ele funciona como um registro importante da evolução: comparar sua versão inicial com meus projetos atuais mostra o quanto a complexidade das minhas soluções aumentou.

---

# 🧰 Tecnologias & ferramentas

## Front-End

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,vite" alt="HTML CSS JavaScript React Vite" />
</p>

**Base:** HTML5, CSS3, JavaScript, DOM, Fetch API, responsividade, acessibilidade, SEO.

**React:** componentização, props, estado, hooks, eventos, consumo de APIs e arquitetura de interfaces.

**Em evolução:** React avançado, Tailwind CSS e Vue.

---

## Back-End & APIs

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express" alt="Node.js Express" />
</p>

- Node.js
- Express
- REST APIs
- autenticação e sessões
- CRUD
- upload de arquivos
- validação
- rate limiting
- headers de segurança
- lógica de servidor

---

## Dados

<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgresql,supabase,sqlite" alt="MySQL PostgreSQL Supabase SQLite" />
</p>

- SQL
- MySQL
- PostgreSQL
- SQLite
- Supabase
- modelagem e consultas
- persistência
- integração aplicação/banco

---

## 3D & experiências interativas

<p>
  <img src="https://skillicons.dev/icons?i=threejs" alt="Three.js" />
</p>

- Three.js
- React Three Fiber
- Drei
- WebGL
- modelos GLB/GLTF
- animação de cena
- iluminação
- interação com ponteiro
- experiências orientadas por scroll

---

## Desenvolvimento & Deploy

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vercel,cloudflare" alt="Git GitHub Vercel Cloudflare" />
</p>

- Git
- GitHub
- Vite
- Cloudflare Workers / Pages
- Vercel
- Render
- npm

---

## Design & UI/UX

<p>
  <img src="https://skillicons.dev/icons?i=figma,photoshop" alt="Figma Photoshop" />
</p>

- Figma
- Photoshop
- CorelDRAW
- Canva
- composição visual
- tipografia
- identidade visual
- UI/UX
- direção de arte para interfaces

---

# 📊 Meu perfil técnico em projetos

A melhor forma de entender minha stack não é uma lista de badges — é observar onde cada tecnologia aparece na prática.

| Área | Na prática |
|---|---|
| **HTML/CSS/JS** | Interfaces, jogos, animações, dashboards e aplicações web |
| **React** | Rouxinol, Alien Terminal, Pokédex, BRASA e CUT CLUB |
| **Node/Express** | FangyScraper e Little Bee |
| **SQL / Dados** | Little Bee, Clínica e projetos de banco |
| **APIs REST** | FangyScraper, Little Bee e Pokédex |
| **3D** | Rouxinol, Pokédex e portfólio |
| **Segurança web** | FangyScraper e Little Bee |
| **UI/UX** | Praticamente todo o ecossistema de projetos |
| **Cloud / Deploy** | Cloudflare, Vercel e Render |
| **IA** | Pesquisa, debugging, exploração, documentação e produtividade |

---

# 📈 GitHub

### Resumo

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Richter06&theme=tokyonight" alt="Resumo do perfil GitHub" />
</p>

### Estatísticas

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Richter06&theme=tokyonight" alt="Estatísticas do GitHub" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Richter06&theme=tokyonight" alt="Linguagens mais utilizadas nos commits" />
</p>

### Linguagens

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Richter06&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Principais linguagens" />
</p>

### Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Richter06&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</p>

### Atividade

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Richter06&theme=tokyo-night&hide_border=true&area=true" alt="Gráfico de atividade do GitHub" />
</p>

### Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Richter06&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&row=1" alt="GitHub trophies" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Richter06&label=Visualizações%20do%20perfil&color=7C3AED&style=flat-square" alt="Visualizações do perfil" />
</p>

---

# 📚 Formação & aprendizado

🎓 **Análise e Desenvolvimento de Sistemas — Estácio**  
2026 — presente

### Certificações e estudos relevantes

- **freeCodeCamp — Responsive Web Design — 300h**
- **Curso em Vídeo — MySQL — 40h**
- **RN Cursos — Design Gráfico — 50h**
- estudos contínuos de React, JavaScript, bancos de dados, APIs, segurança e desenvolvimento web.

Meu processo de aprendizagem é principalmente **orientado por projetos**: aprendo um conceito, aplico em algo concreto, encontro problemas reais e volto para aprofundar o fundamento.

---

# 🔬 O que meus projetos mostram sobre meu aprendizado

Minha evolução pode ser vista em camadas:

```text
MITOLOGIAS
    │
    ▼
HTML + CSS + JavaScript
    │
    ▼
INTERFACES E UI/UX
    │
    ▼
APIs + CRUD + DADOS
    │
    ▼
NODE + EXPRESS
    │
    ▼
SEGURANÇA + ANÁLISE
    │
    ▼
REACT + COMPONENTIZAÇÃO
    │
    ▼
SIMULAÇÕES + GRAFOS
    │
    ▼
3D + WEBGL + EXPERIÊNCIAS
    │
    ▼
PROJETOS COMERCIAIS MAIS COMPLEXOS
```

Não considero essa trajetória encerrada. Ela é justamente o motivo pelo qual continuo criando projetos diferentes.

---

# 🚀 Atualmente

Estou aprofundando principalmente:

- React;
- arquitetura de componentes;
- JavaScript moderno;
- desenvolvimento Back-End com Node.js;
- SQL e modelagem de dados;
- APIs REST;
- testes e homologação;
- experiências 3D para web;
- performance de aplicações;
- acessibilidade;
- boas práticas de desenvolvimento.

Também continuo experimentando projetos independentes para transformar conhecimento em **experiência prática verificável**.

---

# 🤝 Vamos conversar

Estou aberto a **estágio e oportunidades de entrada em desenvolvimento web**, especialmente ambientes onde eu possa contribuir com Front-End, interfaces, lógica de aplicações, dados e continuar evoluindo tecnicamente.

<p align="center">
  <a href="https://github.com/Richter06">GitHub</a>
  •
  <a href="https://www.linkedin.com/in/richard-r-ara%C3%BAjo/">LinkedIn</a>
</p>

---

<p align="center">
  <sub>Construindo, testando, quebrando, entendendo e construindo de novo.</sub>
</p>
