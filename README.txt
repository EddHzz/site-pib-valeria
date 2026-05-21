# ⛪ Ecossistema Digital - Primeira Igreja Batista em Valéria

Este repositório contém a plataforma web oficial da **Primeira Igreja Batista em Valéria**, instituição com 42 anos de história guiada por Deus em Salvador, Bahia. Este site faz parte de um ecossistema digital estratégico planejado e desenvolvido pelo DECOM (Departamento de Comunicação e Mídia) para centralizar a comunicação, modernizar a liturgia e expandir o alcance da igreja.

> 🌐 **Acesse o site rodando ao vivo:** [eddhzz.github.io/site-pib-valeria/](https://eddhzz.github.io/site-pib-valeria/)

---

## 📌 Sobre o Projeto

O projeto foi desenhado seguindo as melhores práticas de Engenharia de Software e Design de Interface (UI/UX). O ecossistema foi dividido em duas frentes complementares, utilizando como *benchmark* técnico grandes portais eclesiásticos nacionais (como PIB Curitiba e IBAM):

1. **Plataforma Web (Este Repositório):** Canal focado em **Atração e Visibilidade Pública**. É o cartão de visitas digital para visitantes, focado em performance, indexação (SEO) e acessibilidade, hospedado gratuitamente via GitHub Pages.
2. **Aplicativo Mobile "Conecta PIB Valéria" (Em Desenvolvimento):** Canal focado em **Retenção, Ensino e Governança Interna**. Uma aplicação integrada ao Firebase com controle de acesso (Membros vs. Administradores), mural de avisos em tempo real, repositório de pregações e módulos para a EBD e Juventude.

---

## 🛠️ Tecnologias e Recursos Técnicos Utilizados

O site foi construído **do zero, sem templates prontos**, demonstrando domínio em desenvolvimento front-end nativo:

* **HTML5 Semântico:** Estruturação limpa utilizando tags que melhoram a acessibilidade (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) e atributos `aria-*` para leitores de tela.
* **CSS3 Moderno:** Layout construído com **Flexbox** e **CSS Grid** para responsividade total. Uso de **Variáveis CSS** (`:root`) para gerenciamento centralizado da paleta de cores (Azul e Vinho) e tipografia.
* **JavaScript Nativo (Vanilla JS):** * Manipulação de DOM para gerenciamento do menu *toggle* mobile com suporte a acessibilidade (fechamento via tecla `Escape` ou clique externo).
  * Implementação da API nativa `IntersectionObserver` para criar efeitos de animação assíncrona (*reveal*) conforme o usuário rola a página, otimizando o uso de memória do navegador.
* **GitHub Pages:** Configuração de pipeline automatizado para *Deploy Contínuo* (CI/CD) direto a partir do branch principal.

---

## 📂 Estrutura de Arquivos

```text
├── index.html          # Estrutura e conteúdo semântico da página principal
├── style.css           # Arquitetura de estilos, variáveis, layouts e media queries
├── script.js          # Lógica do menu mobile e animações via IntersectionObserver
├── README.md           # Documentação técnica do projeto
├── logo-pib.png        # Identidade visual oficial da instituição
└── instagram-post-*.png # Ativos visuais utilizados na seção de mídia/galeria