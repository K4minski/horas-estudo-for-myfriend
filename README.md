# Painel de Horas de Estudo

Contador de horas de estudo por área, com níveis a cada 50 h, gráficos e player do Spotify.
É um site estático: só o `index.html`, sem instalação e sem servidor.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub (ex.: `horas-estudo`).
2. Envie o `index.html` (e este README) para a raiz do repositório.
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`, e clique em **Save**.
5. Depois de cerca de 1 minuto, o site fica em `https://SEU-USUARIO.github.io/horas-estudo/`.

## Observações

- Os dados ficam no `localStorage` do navegador: cada navegador/dispositivo tem o seu próprio histórico.
- Limpar os dados do navegador apaga o histórico.
- Spotify: cole o link de uma playlist, álbum ou faixa. Para ouvir as músicas completas, esteja logado no Spotify no mesmo navegador.
