# English Bridge - Mini-site Institucional

Projeto de mini-site institucional para uma escola de ingles hipotetica, desenvolvido em **HTML + CSS puro**, com foco em:
- presenca digital rapida;
- layout moderno e profissional;
- experiencia responsiva;
- estrutura orientada a conversao (captacao de leads).

## 1. Objetivo do projeto

Construir um site simples, funcional e visualmente forte para divulgacao de servicos de ensino de ingles, incluindo:
- apresentacao da marca;
- explicacao da metodologia;
- prova social (relatos);
- canais de contato para conversao.

## 2. Estrutura de arquivos

```text
Escoladeingles/
├── index.html      # Home
├── sobre.html      # Sobre
├── contato.html    # Contato
├── style.css       # Estilizacao global
└── README.md       # Documentacao do projeto
```

## 3. Paginas e conteudo

### `index.html` (Home)
- Hero principal com proposta de valor.
- CTAs em ingles para acao imediata.
- Bloco de metricas (resultado medio de alunos).
- Secao de beneficios.
- Secao de metodologia em etapas.
- Depoimentos hipoteticos.
- CTA final de conversao.

### `sobre.html` (Sobre)
- Historia e posicionamento da escola.
- Missao, visao e valores.
- Detalhamento metodologico.
- Prova social complementar.
- CTA para criacao de plano personalizado.

### `contato.html` (Contato)
- Formulario com `Nome`, `Email` e `Mensagem`.
- Botao de envio.
- Secao de pacotes mais procurados.
- Canais rapidos:
  - Instagram (link externo);
  - Email (`mailto`);
  - Telefone (`tel`).

## 4. Design system (CSS)

O arquivo `style.css` foi desenhado para uma experiencia premium com foco comercial:

- **Paleta em tons de vermelho** (identidade visual forte para performance de marketing).
- **Tipografia branca** para contraste em fundo escuro/gradiente.
- **Cards com borda, sombra e profundidade**.
- **Hover interativo** em menu, botoes e cards.
- **Header sticky** para navegacao constante.
- **Animacoes suaves** (`reveal`) para sensacao de dinamismo.
- **Acessibilidade basica** com estados `:focus-visible`.

## 5. Responsividade

Site preparado para desktop, tablet e mobile com breakpoints principais:
- `@media (max-width: 980px)`
- `@media (max-width: 760px)`
- `@media (max-width: 620px)`

Comportamentos responsivos implementados:
- grid de cards reduz de 3 para 2 e depois 1 coluna;
- menu adapta largura e distribuicao no mobile;
- paddings e tamanhos de texto ajustados para telas pequenas.

## 6. Requisitos atendidos

- Layout centralizado com largura maxima.
- Menu com efeito hover.
- Cards com borda arredondada e sombra.
- Botoes com efeito hover.
- Site responsivo com empilhamento de cards em telas pequenas.
- Estrutura semantica em HTML (`header`, `nav`, `main`, `section`, `article`, `footer`).

## 7. Como executar localmente

Como o projeto e estatico, basta abrir o `index.html` no navegador:

1. Entre na pasta do projeto.
2. Abra `index.html` com duplo clique ou servidor local.

Opcional (servidor local simples):

```bash
python3 -m http.server 5500
```

Depois acesse:

```text
http://localhost:5500
```

## 8. Proximos passos (etapa final)

### Versionamento com Git

```bash
git init
git add .
git commit -m "feat: mini-site institucional English Bridge"
```

### Deploy no Vercel

1. Criar/reutilizar conta na Vercel.
2. Importar repositorio Git.
3. Configurar projeto como site estatico (sem build complexa).
4. Publicar e obter URL final.

## 9. Possiveis evolucoes

- Integracao real do formulario com backend (API / email service).
- Adicao de SEO tecnico (meta tags completas, Open Graph, schema.org).
- Integracao com analytics (GA4/Plausible).
- Pagina de cursos e landing pages por publico.
- Testes de UX/CRO (A/B de titulos e CTAs).

---

Projeto desenvolvido para fins institucionais e educacionais.
