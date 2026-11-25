# 🎨 CSS Lab — Box Model & Flexbox Responsivo

Projeto prático desenvolvido para atender integralmente à **Atividade 01 da Aula 07 (Frameworks CSS)** da disciplina de **Frameworks Front-end** (SENAI).

---

## 🎯 Requisitos Atendidos (Aula 07 — Atividade 01)

1. Utilização dos arquivos `index.html` e `style.css` com vinculação **CSS Externa** através da tag `<link rel="stylesheet" href="style.css" />`;
2. Criação de **20 elementos HTML distintos** (`#el-01` a `#el-20`), cada um com valores definidos para **Content** (`width` / `min-height`), **Padding**, **Border** e **Margin**;
3. Aplicação de **20 propriedades e configurações de Flexbox** para organizar e manipular os elementos de forma responsiva em telas desktop, tablet e mobile.

---

## 📦 Mapeamento dos 20 Elementos (Box Model)

| # | ID | Função na Interface | Content (`width` / `min-height`) | Padding | Border | Margin |
|---|---|---|---|---|---|---|
| 01 | `#el-01` | Cabeçalho principal | `calc(100% - 32px)` / `76px` | `16px 24px` | `2px solid #1e293b` | `16px auto 24px auto` |
| 02 | `#el-02` | Bloco da marca | `210px` / `52px` | `8px 14px` | `1px solid #38bdf8` | `4px` |
| 03 | `#el-03` | Menu de navegação | `auto` / `44px` | `8px 18px` | `1px solid #334155` | `4px 8px` |
| 04 | `#el-04` | Selo institucional | `160px` / `38px` | `8px 12px` | `1px dashed #38bdf8` | `4px` |
| 05 | `#el-05` | Painel Hero principal | `100%` / `180px` | `24px 28px` | `2px solid #0284c7` | `8px 0 20px 0` |
| 06 | `#el-06` | Diagrama do Box Model | `100%` / `180px` | `24px 20px` | `3px double #f59e0b` | `8px 0 20px 0` |
| 07 | `#el-07` | Card camada Content | `220px` / `105px` | `16px 18px` | `2px solid #22c55e` | `6px 0 20px 0` |
| 08 | `#el-08` | Card camada Padding | `220px` / `105px` | `18px 20px` | `2px solid #3b82f6` | `6px 0 20px 0` |
| 09 | `#el-09` | Card camada Border | `220px` / `105px` | `16px 20px` | `3px solid #a855f7` | `6px 0 20px 0` |
| 10 | `#el-10` | Card camada Margin | `220px` / `105px` | `16px 20px` | `2px solid #f97316` | `6px 0 20px 0` |
| 11 | `#el-11` | Demo `flex-direction` | `240px` / `140px` | `18px` | `1px solid #475569` | `6px 0 18px 0` |
| 12 | `#el-12` | Demo `justify-content` | `240px` / `140px` | `20px` | `1px solid #475569` | `6px 0 18px 0` |
| 13 | `#el-13` | Demo `order` & `align-self` | `240px` / `140px` | `20px` | `2px solid #38bdf8` | `6px 0 18px 0` |
| 14 | `#el-14` | Demo `flex-wrap` | `240px` / `140px` | `18px` | `1px solid #475569` | `6px 0 18px 0` |
| 15 | `#el-15` | Card CSS Externo | `250px` / `135px` | `18px 20px` | `1px solid #334155` | `4px 0 18px 0` |
| 16 | `#el-16` | Card Class e ID | `250px` / `135px` | `18px 20px` | `1px solid #334155` | `4px 0 18px 0` |
| 17 | `#el-17` | Card Gap | `250px` / `135px` | `18px 20px` | `1px solid #334155` | `4px 0 18px 0` |
| 18 | `#el-18` | Card Flex Shorthand | `250px` / `135px` | `18px 20px` | `1px solid #334155` | `4px 0 18px 0` |
| 19 | `#el-19` | Banner de Responsividade | `100%` / `110px` | `22px 28px` | `2px solid #6366f1` | `10px 0 28px 0` |
| 20 | `#el-20` | Rodapé institucional | `calc(100% - 32px)` / `68px` | `16px 24px` | `1px solid #1e293b` | `8px auto 24px auto` |

---

## 📐 20 Propriedades e Configurações de Flexbox Aplicadas

1. `display: flex` (`.cabecalho-flex`, `.hero-flex`, `.metricas-flex`)
2. `display: inline-flex` (`.marca-box`)
3. `flex-direction: row` (`.cabecalho-flex`)
4. `flex-direction: column` (`.marca-box` e adaptação mobile)
5. `flex-direction: row-reverse` (`.galeria-flex`)
6. `flex-wrap: wrap` (`.cabecalho-flex`, `.metricas-flex`, `.grade-cartoes-flex`)
7. `flex-wrap: nowrap` (`.menu-flex`)
8. `flex-flow: row wrap` (`.hero-flex`)
9. `justify-content: space-between` (`.cabecalho-flex`, `.rodape-flex`)
10. `justify-content: center` (`.menu-flex`, `.cta-flex`)
11. `justify-content: space-around` (`.galeria-flex`)
12. `justify-content: space-evenly` (`.metricas-flex`)
13. `align-items: center` (`.cabecalho-flex`, `.cta-flex`)
14. `align-items: stretch` (`.hero-flex`, `.grade-cartoes-flex`)
15. `align-items: flex-start` (`.marca-box`)
16. `align-content: space-between` (`.galeria-flex`)
17. `gap`, `row-gap` e `column-gap` (`.cabecalho-flex`, `.menu-flex`, `.metricas-flex`)
18. `flex-grow`, `flex-shrink`, `flex-basis` e shorthand `flex` (`.cartao-conceito`, `#el-05`, `#el-06`)
19. `align-self: center` (`.destaque-ordem`)
20. `order: -1` (`.destaque-ordem`)

---

## 🚀 Como Executar

Basta abrir o arquivo `index.html` diretamente em qualquer navegador moderno ou utilizar uma extensão como **Live Server** no VS Code.

---

## 🎓 Disciplina

**Frameworks Front-end** — SENAI | Prof. Me. Deivison S. Takatu
