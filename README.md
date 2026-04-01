# 🖼️ Interactive Image Hover Profiles

> Uma galeria de perfis interativa com efeitos de revelação (Hover), desenvolvida puramente com HTML5 e CSS3. Um componente elegante e focado na experiência do usuário (UX).

## 📖 Sobre o Projeto

O projeto **Image Hover** consiste em um componente de interface de usuário (UI) desenhado para apresentar equipes ou listas de contatos de forma limpa e dinâmica. Inicialmente, a interface exibe apenas ícones ou miniaturas de perfil. Ao interagir com o elemento (hover), o cartão se expande de forma fluida para revelar a fotografia completa, o nome e a ocupação do profissional.

Este tipo de microinteração é excelente para otimizar o espaço em tela, garantindo que o layout inicial não fique sobrecarregado com texto, mas mantendo a informação facilmente acessível.

## ✨ Destaques e Arquitetura Técnica

* **Design Modular:** O HTML foi estruturado com base no encapsulamento de componentes, utilizando a classe principal `.icon-image` para envolver tanto o ícone inicial quanto o conteúdo revelado (`.hover-image`).
* **Hierarquia Visual:** Separação clara de responsabilidades no código, com contêineres específicos para os detalhes textuais (`.name` e `.job`), facilitando a manutenção e futuras estilizações.
* **Apresentação Profissional:** O componente já está populado com perfis diversificados (como Designers, Desenvolvedores e Fotógrafos), demonstrando a aplicação prática do elemento em um cenário real.
* **Independência de Scripts:** Todo o comportamento de expansão e transição visual é gerenciado pelo CSS (`css/style.css`), garantindo alta performance no navegador sem a necessidade de JavaScript.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica e aninhamento lógico de contêineres.
* **CSS3:** Estilização de layout, posicionamento de elementos e animações de transição baseadas em pseudo-classes (`:hover`).
