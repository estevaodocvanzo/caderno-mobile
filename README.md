# Caderno de Erros — versão mobile

App de spaced repetition para revisão de questões de residência médica, hospedado em GitHub Pages para acesso pelo celular.

## Como usar

1. Abrir a URL pública (ex: `https://USER.github.io/caderno-mobile`)
2. Em **Configurações**, colar:
   - **GitHub Token** (classic com escopos `repo` + `gist`)
   - **Gist ID** do gist privado com os dados
3. App puxa o estado do Gist e fica em sync

Os dados ficam em **localStorage do navegador** + **GitHub Gist privado**. A URL pública só serve para carregar a interface — sem token, não há acesso aos cards.

## Atualização

A versão fonte está em [`caderno-de-erros/app.html`](https://github.com/estevaodocvanzo/caderno-de-erros). Quando o `app.html` for atualizado, copie por cima do `index.html` daqui e dê push.
