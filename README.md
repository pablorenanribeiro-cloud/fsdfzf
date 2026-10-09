# 🚦 Semáforo da Comunicação Web

Este projeto foi desenvolvido como uma atividade avaliativa, apresentando boas e más práticas de comunicação em interfaces web categorizadas em formato de "semáforo" (Verde, Amarelo e Vermelho).

## 📌 Requisitos Atendidos no Projeto
- [x] Total de 15 cards contendo as práticas;
- [x] Construído com HTML5 semântico;
- [x] Estilizado com CSS3 puro;
- [x] Layout organizado e responsivo para celulares (Mobile First adaptado);
- [x] Uso combinado de cores, símbolos (emojis) e títulos textuais (não depende apenas da cor);
- [x] Textos diretos e objetivos.

## ♿ Práticas de Acessibilidade Implementadas (Mais de 6)
1. **Contraste de Cores:** Combinações de fundo e texto testadas para alta legibilidade.
2. **HTML Semântico:** Utilização correta de `<header>`, `<main>`, `<section>` e `<article>`.
3. **Não dependência de cor:** Todas as informações de estado (🟢, 🟡, 🔴) possuem redundância com texto e símbolos (WCAG 1.4.1).
4. **Foco Navegável:** O CSS utiliza `*:focus-visible` para destacar elementos quando navegados via teclado (tecla TAB).
5. **Aria-Labels e Aria-Hidden:** Ícones decorativos recebem `aria-hidden="true"` para não poluir leitores de tela, e elementos visuais ganham `aria-labelledby` ou `aria-label`.
6. **Hierarquia de Títulos:** Uso de `h1`, `h2` e `h3` de maneira lógica, permitindo saltos consistentes em leitores de tela.
7. **Responsividade Tátil:** Margens, `gap` e paddings calculados para evitar cliques acidentais em dispositivos móveis.

## 🚀 Como acessar (Deploy)
O projeto foi publicado via GitHub Pages e pode ser acessado pelo link:
👉 **[INSERIR SEU LINK DO GITHUB PAGES AQUI]**

## 💻 Instruções para Entrega no Classroom
Para o aluno:
1. Faça o upload das pastas (`index.html`, `style.css` e `README.md`) para o seu repositório GitHub.
2. Acesse a aba **Settings** > **Pages** no seu repositório.
3. Em *Source*, selecione a branch `main` e clique em Save. Em alguns minutos, o link será gerado.
4. Tire um **print** do site aberto no seu navegador.
5. Copie o link do repositório, o link do GitHub Pages e envie junto com o print lá no Google Classroom!
