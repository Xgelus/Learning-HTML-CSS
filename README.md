
Este arquivo README.md explica onde cada requisito foi implementado, fornece informações sobre como visualizar o site e detalha as ferramentas utilizadas.

# Empresa Nesseriana - Site Institucional

Este é o repositório do site institucional da Empresa Nesseriana, cujo objetivo principal é promover a educação no Brasil. Abaixo, estão descritos os requisitos do projeto e onde cada um foi cumprido no site.

---

## **Requisitos do Projeto e Localização**

### **1. Três páginas diferentes**
- **Home (`index.html`):** Página inicial com informações sobre a empresa, incluindo missão, visão e valores.
- **Sobre (`sobre.html`):** Informações detalhadas sobre a história e equipe da empresa, além de uma tabela personalizada.
- **Contato (`contato.html`):** Formulário para visitantes entrarem em contato com a empresa.

---

### **2. Construção semântica do layout**
- Uso de tags semânticas do HTML5:
  - `<header>` para o cabeçalho.
  - `<nav>` para a navegação.
  - `<main>` para o conteúdo principal.
  - `<section>` para organizar informações específicas (missão, visão e valores na Home).
  - `<footer>` para o rodapé.

---

### **3. Responsividade (Flexbox, Grid e Tailwind CSS)**
- **Responsividade garantida por Tailwind CSS**, incluindo:
  - Classes utilitárias como `container`, `mx-auto` e `flex`.
  - Layout flexível para cabeçalhos e navegação com `flex` e `justify-between`.
  - Estruturas adaptáveis com `grid` e `gap` nos formulários e tabelas.

---

### **4. Diversidade nas tipografias**
- **Home (`index.html`):**
  - Uso de fontes variadas com `font-bold`, `font-semibold` e `text-lg`.
  - Diferentes tamanhos de texto com `text-3xl`, `text-2xl`, etc.
  - Cores diversificadas em títulos e parágrafos (ex.: `text-blue-600`, `text-gray-700`).
- **Sobre (`sobre.html`):** Títulos em negrito e textos estilizados para a tabela.
- **Contato (`contato.html`):** Uso de tamanhos e pesos diferentes nas labels e botões.

---

### **5. Variedade de cores**
- **Home (`index.html`):** Uso de diferentes tons da paleta padrão do Tailwind:
  - Azul (`bg-blue-600`, `text-blue-600`).
  - Verde (`bg-green-50`, `border-green-400`).
  - Amarelo (`bg-yellow-50`, `text-yellow-700`).
- **Sobre (`sobre.html`):** Tons de verde para destacar a tabela.
- **Contato (`contato.html`):** Cores vermelhas para o formulário e botões.

---

### **6. Pseudo-classes**
- **Hover:** Aplicado em links e botões para melhorar a experiência do usuário:
  - Exemplo: `hover:underline` nos links do menu de navegação.
  - Exemplo: `hover:bg-red-700` no botão de envio do formulário em `contato.html`.
- **Focus:** Utilizado no formulário da página de contato:
  - Exemplo: `focus:border-red-600` nos campos de texto.

---

### **7. Tabela personalizada**
- Localizada na página **Sobre (`sobre.html`)**:
  - Construída com `table-auto` e estilizada com bordas (`border-green-600`).
  - Uso de pseudo-classes como `hover:bg-green-100` nas linhas para realce ao passar o mouse.
  - Estrutura semântica com `<thead>` e `<tbody>`.

---

## **Como visualizar o site**
1. Faça o download ou clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/empresa-nesseriana.git
2. Abra qualquer um dos arquivos HTML no navegador.


## **Ferramentas Utilizadas**

HTML5: Estruturação semântica.
Tailwind CSS: Estilização, responsividade e pseudo-classes.
CSS personalizado: Ajustes adicionais (opcional).

## **Autor**
Desenvolvido por Gabriel Andrade
