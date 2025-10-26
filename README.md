# 💜 Conecta ONG | Plataforma de Voluntariado e Doações

Plataforma web construída para conectar ONGs verificadas a voluntários e doadores. O projeto foi desenvolvido sob um rigoroso conjunto de Especificações Técnicas, utilizando arquitetura modular e padrões modernos de Front-end.

## ✨ Visão Geral do Projeto e Entregáveis

O desenvolvimento foi dividido em três grandes fases, cada uma construindo sobre a anterior:

| Fase | Foco Principal | Metodologia |
| :--- | :--- | :--- |
| **Entrega 1** | Estrutura e Semântica | HTML5, Formulários Complexos e Otimização de Imagens |
| **Entrega 2** | Design e Layout | CSS3, Design System Modular, CSS Grid e Flexbox |
| **Entrega 3** | Aplicação Dinâmica | JavaScript Modular, SPA Básico e Validação de Formulário |

---

## 🚀 Arquitetura e Tecnologia (Entrega 3: JS Avançado)

A aplicação é arquitetada como uma **Single Page Application (SPA)** e é totalmente modularizada para facilitar a manutenção e escalabilidade.

### Código JavaScript Modular
O código foi organizado por funcionalidade (utilizando **ES Modules** `import`/`export`):

| Módulo | Responsabilidade | Tecnologia Chave |
| :--- | :--- | :--- |
| **`router.js`** | Gerenciamento de rotas, permitindo a navegação fluida (SPA) | `history.pushState()`, Manipulação do DOM |
| **`validator.js`** | Sistema de Validação de Formulários e feedback de erro | Validação nativa + Customizada, Manipulação do DOM |
| **`templates.js`** | Geração dinâmica de HTML (cards de ONGs, listas) | JavaScript Template Literals |
| **`ui.js`** | Lógica de interação visual (Menu Hambúrguer, Modal) | Manipulação do DOM, Listeners de Eventos |

---

## 🎯 Conformidade Detalhada com as Especificações

### ✔️ Requisitos Cumpridos na Entrega 3 (JS Modular)
| Requisito Obrigatório | Status e Implementação |
| :--- | :--- |
| **Código JavaScript Modular** | Totalmente modularizado e organizado em 5 módulos (`main.js` e 4 módulos). |
| **Implementar SPA Básico** | Navegação sem recarga via `router.js`. |
| **Validação de Formulário** | Sistema completo de verificação de consistência de dados com aviso visual ao usuário (`validator.js`). |
| **Sistema de Templates JS** | Implementado para renderização dinâmica de dados. |

### ✔️ Requisitos da Base do Projeto (Entregas 1 & 2)
* **Design System:** Desenvolvido com variáveis CSS para paleta de cores (mais de 8), tipografia e espaçamento modular.
* **Layout Responsivo:** Uso de **CSS Grid** (12 colunas) e **Flexbox** com 5 *breakpoints*.
* **Estrutura Semântica:** Uso correto de tags HTML5 (`<main>`, `<article>`, `<figure>`, etc.).
* **Assets:** Imagens otimizadas em múltiplos formatos.

---

## 🛠️ Documentação e Processo (Atividade 4)

O processo de desenvolvimento está totalmente documentado no GitHub, conforme exigido:

* **Repositório Público:** Link configurado como PÚBLICO com todo o código fonte.
* **Histórico de Commits Organizado:** Utilização de *branches* isoladas (`feature/css-modular`, `feature/js-modular-spa`) e prefixos (feat:, refactor:) para descrever o desenvolvimento.
* **Pull Requests Documentados:** Cada fase de entrega (CSS, JS) foi mesclada através de um PR com documentação detalhada dos requisitos.
* **Milestones e Issues:** Utilizados para rastrear e gerenciar o desenvolvimento do projeto.

---

## 🤝 Execução e Contato

### Para Execução (SPA)
O projeto usa ES Modules e `fetch()`, requerendo um servidor local para funcionar corretamente.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/DanielaBarbosadosSantos/Conecta-ONG
    ```
2.  **Execute com Servidor Local:** Use a extensão "Live Server" do VS Code ou execute `python3 -m http.server 8000` na pasta raiz.

### Dúvidas Técnicas
Em caso de dúvidas técnicas sobre o código ou sugestões:

* **Abra uma Issue:** Use a aba **Issues** no repositório.
* **Email:** danielabarbosa.090@gmail.com

## ⚖ Licença
Este projeto está sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
