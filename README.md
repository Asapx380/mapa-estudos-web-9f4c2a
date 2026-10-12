# Mapa de estudos — Desenvolvimento Web

Guia visual para estudar HTML, CSS, Git, JavaScript, TypeScript, Node.js e React. Cada item abre um painel com o significado e um exemplo curto.

## Como usar

Abra `index.html` no navegador.

- Busque por nome, por exemplo `imagem`
- Filtre pela tecnologia e, em seguida, pelo assunto
- Use Ctrl/Cmd + P para salvar uma versão em PDF

## Arquivos

```text
index.html    Página do mapa
styles.css    Layout e filtros
script.js     Itens, busca e o painel de detalhe
```

Site estático, sem build.

## Desenvolvimento e validação

Este projeto é estático. Para servir a pasta localmente, com Python instalado:

```bash
python -m http.server 8080
```

Abra `http://localhost:8080/`. Para conferir a sintaxe, com Node.js instalado:

```bash
node --check script.js
```

Teste a busca com e sem acentos, os filtros por tecnologia e assunto, a abertura e o fechamento do painel e a impressão. Confira também a navegação pelo teclado.

A verificação de sintaxe não substitui os testes da interface e das integrações.
