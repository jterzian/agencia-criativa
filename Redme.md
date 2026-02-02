# Agência Criativa Web - Refatoração com SASS

Este projeto é uma landing page moderna para a "Agência Criativa Web", focada em demonstrar a refatoração de um código CSS tradicional para uma estrutura modular, escalável e organizada utilizando **SASS**.

## 🚀 Tecnologias Utilizadas
* **HTML5** para a marcação estrutural.
* **SASS (Syntactically Awesome Style Sheets)** para a estilização avançada.
* **Metodologia BEM** (Block, Element, Modifier) para nomenclatura de classes.
* **Node.js** para compilação do SASS via linha de comando.

## 🏗️ Estrutura do Projeto SASS
Seguindo os requisitos de arquitetura modular, o projeto foi dividido em parciais (`partials`):

* `_base.scss`: Resets globais, tipografia básica e estilos fundamentais.
* `_variaveis.scss`: Definição de paleta de cores, fontes e espaçamentos reutilizáveis.
* `_mixins.scss`: Mixins para centralização com Flexbox e comportamentos repetitivos.
* `_layout.scss`: Estrutura de Header, Hero e alinhamento das seções.
* `_componentes.scss`: Estilos específicos para botões, cards de serviços, formulário e depoimentos.
* `estilos.scss`: Arquivo mestre que importa todos os parciais utilizando `@use`.

## 🛠️ Como rodar o projeto
Para compilar o SASS durante o desenvolvimento:
```bash
sass --watch scss/estilos.scss css/style.css