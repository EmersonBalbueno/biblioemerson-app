# BiblioEmerson PWA para Android

Arquivos principais:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

## Importante
Esta versão foi preparada para ser PUBLICADA e INSTALADA no Android como app.

## Por que não funcionou ao abrir o HTML no celular?
Abrir um arquivo local (`file://`) no Android nem sempre executa tudo corretamente.
Além disso, um app instalável (PWA) precisa de:
- link público
- HTTPS
- manifest
- service worker

## Como publicar
Você pode publicar esta pasta em qualquer hospedagem estática, por exemplo:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- seu próprio domínio

## Como instalar no Android
1. publique esta pasta em um link HTTPS
2. abra o link no Chrome do Android
3. toque no botão **Instalar no Android**
4. se necessário, use o menu do Chrome: **⋮ > Instalar app** ou **Adicionar à tela inicial**

## Observação
Depois que o site abrir ao menos uma vez publicado, o service worker deixa o app pronto para uso offline.
