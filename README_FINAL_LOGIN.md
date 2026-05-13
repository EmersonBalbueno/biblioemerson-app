# BiblioEmerson Portal Final com Login Google

Arquivos principais:
- index.html  -> versão PWA/publicável com login Google
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- biblioemerson_mobile_pwa_preview.html -> visualização local simples
- biblioemerson_superapp_final.html -> versão principal em arquivo único

## O que já está implementado
- Login com Google usando Firebase Authentication
- Bloqueio do portal até autenticação
- Botão de logout
- PWA instalável no Android quando publicado em HTTPS
- Cache offline após publicação e primeiro acesso

## Firebase usado no app
const firebaseConfig = {
  apiKey: "AIzaSyC7JokhZKTm29qUUT47hxgss2wubTnOgp8",
  authDomain: "biblioemerson-app.firebaseapp.com",
  projectId: "biblioemerson-app",
  storageBucket: "biblioemerson-app.firebasestorage.app",
  messagingSenderId: "710189853432",
  appId: "1:710189853432:web:441e8bc7f3b7ac67dea90d"
};

## Antes de publicar
No Firebase Console:
1. Authentication > Sign-in method > Google > Enable
2. Authentication > Settings > Authorized domains
3. Adicione o domínio onde o app será publicado

## Para publicar e instalar no Android
1. publique estes arquivos em um link HTTPS
2. abra o link no Chrome do Android
3. faça login com Google
4. toque em “Instalar no Android” ou use o menu do Chrome
