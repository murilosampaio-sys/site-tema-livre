# Patas & Bigodes — Website Institucional

## Identificação do Projeto

- **Título do Site:** Patas & Bigodes
- **Tema:** Adopção Responsável e Proteção Animal (Gatos)
- **Aluno:** Murilo Augusto Amaral Sampaio
- **Turma:** DSM3 2025
- **Unidade Curricular:** Desenvolvimento Web / HTML5 Semântico (2026)

---

## Descrição do Projeto

O site da **Patas & Bigodes** é uma plataforma institucional dedicada ao resgate, cuidado e promoção da adopção responsável de felinos. O projeto foi desenvolvido com foco estrito em HTML5 semântico e conformidade com as diretrizes de acessibilidade (WCAG), oferecendo uma navegação clara, inclusiva e estruturada sem dependência de estilização externa.

---

## Como Abrir o Projeto no Navegador

1. Faça o download ou clone este repositório para o seu computador.
2. Navegue até a pasta raiz do projeto onde os arquivos `.html` estão armazenados.
3. Clique duas vezes sobre o arquivo `index.html` para abri-lo diretamente no seu navegador padrão (Google Chrome, Firefox, Edge, etc.).
4. *Opcional:* Se estiver utilizando o **Visual Studio Code**, abra a pasta do projeto, clique com o botão direito sobre o arquivo `index.html` e selecione **"Open with Live Server"**.

---

## Estrutura das Páginas

- **`index.html`**: Página principal com a apresentação da ONG, missão institucional e destaque para a importância da adopção responsável.
- **`sobre.html`**: Guia de cuidados essenciais com felinos, secção de curiosidades com artigos externos e glossário com termos técnicos.
- **`dados.html`**: Apresentação de dados estatísticos de resgates, vacinações e relatórios de transparência organizados em tabelas semânticas.
- **`cadastro.html`**: Formulário interativo completo para o registo de potenciais adotantes e voluntários com múltiplos tipos de inputs.
- **`contato.html`**: Informações de localização com `<address>`, horário de atendimento em lista de definição (`<dl>`), link para mapa e formulário de mensagem.

---

## Recursos de Acessibilidade e Testes de Teclado

### Recursos Aplicados
- **Skip Link (*Pular para o conteúdo*):** Adicionado como primeiro elemento interativo dentro da tag `<body>` em todas as 5 páginas, direcionando o foco diretamente para o `<main id="conteudo-principal">`.
- **HTML5 Semântico:** Utilização rigorosa de cabeçalhos hierárquicos (`<h1>` a `<h3>`), marcos estruturais (`<header>`, `<nav>`, `<main>`, `<section>`, `<aside>`, `<footer>`) e elementos como `<address>` e `<dl>`.
- **Áreas de Toque Otimizadas:** Afastamento horizontal dos links de navegação no cabeçalho através do padrão `<nav><p><a ...> &nbsp;|&nbsp; ...</p></nav>`, garantindo separação visual e tátil adequada em HTML puro.
- **Atributos WCAG:** Aplicação de `aria-current="page"` na navegação ativa de cada página, declaração de idioma `lang="pt-BR"` e atributo `rel="noopener noreferrer"` em links externos.

### Resultado do Teste Manual de Teclado (`TAB` / `Shift + TAB`)
- **Metodologia:** Navegação executada em todas as páginas utilizando exclusivamente as teclas `TAB` para avançar e `Shift + TAB` para recuar.
- **Resultado em `index.html`, `sobre.html` e `dados.html`:** O foco inicia perfeitamente no *Skip Link*, avança ordenadamente pelos 5 links do menu de navegação e percorre sequencialmente os links do corpo da página sem qualquer travamento (*keyboard trap*).
- **Resultado em `cadastro.html` e `contato.html`:** A navegação por formulários segue uma ordem lógica sequencial, passando pelos campos de texto, caixas de seleção, grupos de botões de rádio (`radio`), *checkboxes* e botão de envio, mantendo o indicador visual do navegador visível e bem definido a cada parada.
- **Conclusão:** Aprovado em 100% dos cenários de teste de navegabilidade por teclado.

---

## Fontes Consultadas, Imagens e Licenças

### Fontes Consultadas
- Documentação MDN Web Docs (HTML5 Semântico e Acessibilidade WCAG)
- Diretrizes W3C (W3C Markup Validation Service)
- Inspira Health Network (Informaçoes sobre o ronrom dos felinos)
- Folha de Pernambuco (Artigo sobre comunicação e miados felinos)
- Olhar Digital (Matéria sobre a biologia e função dos bigodes felinos)

### Imagens e Licenças
- *Nota:* O projeto atual é totalmente estruturado em texto, listas, tabelas e formulários em HTML5 puro, com apenas a utilização de ficheiros de imagem externos e utilização de IA para aprender o conceito de Non-Breaking Space (Espaço Sem Quebra), sem a utilização para a criação do código em si.
