# 💳 7G BANK — Dashboard Financeiro

> Projeto desenvolvido como atividade avaliativa da disciplina de **View - Fase 4** — Curso de Análise e Desenvolvimento de Sistemas (ADS) · FIAP · 2026

<br>

![7G BANK](https://img.shields.io/badge/GUS%20BANK-Fintech%20Dashboard-7C5CFC?style=for-the-badge&logo=googlechrome&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Glassmorphism](https://img.shields.io/badge/Glassmorphism-Design-9B7DFF?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Concluído-22D3A0?style=for-the-badge)

---

## 📌 Sobre o projeto

O **7G BANK** é uma aplicação Fintech voltada para **gestão financeira pessoal**. Este repositório contém a tela de **Dashboard Principal**, desenvolvida com HTML5, CSS3 e Tailwind CSS como entrega da Fase 4 do projeto acadêmico iniciado na FIAP.

O design adota o estilo **Glassmorphism** — painéis semitransparentes com efeito de desfoque (_backdrop-filter_), orbs de fundo com gradientes suaves e bordas luminosas — criando uma interface moderna e sofisticada, fiel ao protótipo desenvolvido no Figma na Fase 2.

---

## ✨ Funcionalidades

- 📊 **Cards de resumo** — Saldo Total, Despesas e Receitas com indicadores de variação mensal e efeito glass
- 📋 **Tabela de transações** — histórico com categoria, data e valor (verde = receita / vermelho = despesa)
- 🎯 **Painel de objetivos** — barras de progresso com gradiente para metas financeiras
- 📈 **Gastos por categoria** — distribuição visual em barras por área de gasto
- 🔲 **Sidebar de navegação** — menu lateral com glass e item ativo destacado
- 📱 **Layout responsivo** — desktop, tablet e mobile com menu hamburguer

---

## 🎨 Glassmorphism — o que foi aplicado

| Elemento | Técnica Glass |
|---|---|
| Cards de resumo | `backdrop-filter: blur(20px)` + fundo `rgba` + borda translúcida |
| Painéis de conteúdo | Fundo semitransparente + borda superior luminosa |
| Sidebar | `backdrop-filter: blur(16px)` para flutuar sobre o fundo |
| Botão "Nova Transação" | Glass com `box-shadow` colorido e borda brilhante |
| Tags de categoria | Mini glass com borda sutil em cada badge |
| Orbs de fundo | Círculos com `filter: blur(90px)` que criam profundidade |
| Dots de transação | `box-shadow` com brilho da cor correspondente |

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Finalidade |
|---|---|
| **HTML5** | Estrutura semântica da página |
| **CSS3** | Glassmorphism, responsividade e animações |
| **Tailwind CSS** | Framework utilitário para layout e classes auxiliares |
| **Google Fonts** | Inter (corpo) + Syne (títulos display) |

---

## 📂 Estrutura de arquivos

```
gusbank-fintech/
│
├── index.html        # Dashboard principal
│
├── css/
│   └── style.css     # CSS customizado (separado do HTML — critério FIAP)
│
└── README.md         # Documentação do projeto
```

---

## 🚀 Como executar

**Sem instalação.** O Tailwind é carregado via CDN e funciona com qualquer navegador.

```bash
# 1. Clone o repositório
git clone https://github.com/SEU_USUARIO/gusbank-fintech.git

# 2. Acesse a pasta
cd gusbank-fintech

# 3. Abra no navegador
# Clique duas vezes em index.html  OU  use Live Server no VS Code
```

> ✅ Compatível com Chrome, Firefox, Edge e Safari.

---

## 📱 Responsividade

| Breakpoint | Comportamento |
|---|---|
| **Desktop** > 1024px | Sidebar fixa, grid 3 colunas nos cards |
| **Tablet** ≤ 1024px | Colunas colapsam, painel direito vai para baixo |
| **Mobile** ≤ 768px | Sidebar vira menu hamburguer, tabela vira lista |

---

## 🎨 Design System

| Token | Valor |
|---|---|
| Cor primária | `#7C5CFC` — roxo |
| Fundo principal | `#0D0F1A` — azul escuro profundo |
| Receitas | `#22D3A0` — verde água |
| Despesas | `#F75A5A` — vermelho coral |
| Tipografia display | Syne 700 / 800 |
| Tipografia corpo | Inter 400 / 500 / 600 |

---

## 📚 Contexto acadêmico

| Fase | Entrega |
|---|---|
| Fase 1 | Conceito e briefing da Fintech |
| Fase 2 | Prototipação das telas no Figma |
| **Fase 3** | **Desenvolvimento Web — HTML, CSS e Tailwind CSS** ← aqui |

---

## 👨‍💻 Autor

**Luiz Gustavo Miranda**  
Estudante de ADS — FIAP · 2026

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://github.com/Luizgustavo0110)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://www.linkedin.com/in/luizgpmiranda/)
