# Clínica Vida Saudável - Landing Page

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-blue)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()
[![Made with](https://img.shields.io/badge/made%20with-HTML%2C%20CSS%2C%20JS-orange)]()

Landing page institucional para uma clínica médica fictícia, desenvolvida com foco em boas práticas de front-end, layout moderno e responsividade.

---

## Demonstração

### Desktop
![Preview Desktop](preview/clinica_index.html.png)

### Mobile
![Preview Mobile](preview/clinica_index_mobile.html.png)

---

## Funcionalidades

### Navbar Fixa com Scroll Dinâmico
- Fixa no topo da página
- Alteração de estilo ao rolar (transparente → sólido)
- Navegação suave entre seções

### Hero Section
- Ocupa toda a altura da tela (`100vh`)
- Imagem de fundo com overlay escuro
- Conteúdo centralizado
- Botão de chamada para ação

### Seção de Serviços
- Cards com imagem, título e descrição
- Layout em Flexbox
- Efeito hover com elevação

### Seção da Equipe
- Exibição dos profissionais
- Cards reutilizáveis
- Estrutura consistente com serviços

### Formulário de Contato
- Campos:
  - Nome
  - E-mail
  - Cidade
  - Estado
- Inputs estilizados com foco visual
- Layout adaptável para mobile

### Responsividade
- Media queries para telas menores
- Cards empilhados no mobile
- Ajustes de tipografia
- Correção de overflow horizontal

---

## Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (interações da navbar)

---

## Estrutura do Projeto

CLINICA-LANDING/
├── LINCENSE
├── index.html
├── style.css
├── script.js
├── README.md
├── img/
│ ├── consulta.jpg
│ ├── corpo-clinico.png
│ ├── dr-joao.jpg
│ ├── dr-maria.jpg
│ ├── enfermeira.jpg
│ ├── exames.jpg
│ └── hero.jpg
└── preview/
├── clinica_index.html.png
└── clinica_index_mobile.html.png


---

## Como Executar

### Opção 1: Abrir direto no navegador
Abra o arquivo: index.html

### Opção 2: Servidor local (recomendado)

Terminal: npx live-server

## Boas Práticas Aplicadas:
- Uso de box-sizing: border-box
- Prevenção de overflow horizontal
- Layout responsivo com Flexbox
- Separação clara de responsabilidades
- Componentização com classes reutilizáveis
- Hierarquia tipográfica consistente

## Melhorias Futuras
- Menu hamburger para mobile
- Validação de formulário com JavaScript
- Integração com backend/API
- Animações com scroll
- Acessibilidade (ARIA, navegação por teclado)

## Licença

Este projeto está sob a licença MIT.

## Autor

Lucas Pereira Alves