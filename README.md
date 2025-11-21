# Projeto SCSS - Estilos Globais

Este projeto organiza os estilos em **SCSS** utilizando boas práticas de modularização.

## 📂 Estrutura de pastas

scss/ ├── _variaveis.scss # Definição de variáveis globais ├── _mixins.scss # Mixins reutilizáveis ├── _base.scss
# Reset e estilos básicos ├── _layout.scss
# Estrutura geral da página ├── _componentes.scss
# Estilos de componentes reutilizáveis └── estilos.scss
# Arquivo principal que importa todos os parciais

Código

## 🚀 Como usar

1. Instale as dependências do Sass (se necessário):
   ```bash
   npm install -g sass
Compile o SCSS para CSS:

bash
sass scss/estilos.scss css/estilos.css
Inclua o css/estilos.css no seu HTML:

html
<link rel="stylesheet" href="css/estilos.css">
✨ Recursos
Variáveis centralizadas para cores, tipografia e espaçamento.

Mixins para reutilização de estilos (ex.: flex-center, card).

Estrutura modular para facilitar manutenção e escalabilidade.
