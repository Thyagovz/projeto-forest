# Projeto Forest

Uma página estática simples para apresentação (portfolio/projeto) construída com HTML e CSS com foco em Tailwind.

## Visão geral

- Página principal: [src/index.html](src/index.html)
- Estilos fonte: [src/input.css](src/input.css)
- Estilos gerados/saída: [src/output.css](src/output.css)
- Imagens (parceiros): [src/img/parceiros/](src/img/parceiros/)
- Configurações do projeto: [package.json](package.json)
- Ignorados do repositório: [.gitignore](.gitignore)

## Principais características

- Estrutura simples e leve (HTML + CSS).
- Fluxo com arquivo de entrada CSS ([src/input.css](src/input.css)) e arquivo resultante ([src/output.css](src/output.css)) — permite uso de ferramentas de build como PostCSS, Tailwind ou outro pipeline de CSS.
- Diretório de imagens organizado em [src/img/parceiros/](src/img/parceiros/).

## Tecnologias

- Tailwind
- HTML (página estática): [src/index.html](src/index.html)
- CSS (arquivo fonte e arquivo compilado): [src/input.css](src/input.css), [src/output.css](src/output.css)
- Dependências e scripts de build opcionais em: [package.json](package.json)

## Como executar (local)

Opções rápidas:

1. Abrir direto

- Basta abrir [src/index.html](src/index.html) no navegador.

2. Servir localmente (recomendado para desenvolvimento)

- Se houver um script ou dependências em [package.json](package.json), execute:
  - Instalar dependências:
    ```sh
    npm install
    ```