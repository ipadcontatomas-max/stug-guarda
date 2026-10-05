# STUG Guarda — PWA Android

Este pacote transforma o STUG Guarda numa Progressive Web App instalável.

## Ficheiros
- index.html — aplicação
- manifest.webmanifest — configuração PWA
- sw.js — cache/offline da aplicação
- icon-192.png / icon-512.png — ícones Android
- apple-touch-icon.png — ícone para iOS

## Para instalar no Android
1. Coloca TODOS estes ficheiros na mesma pasta de um alojamento HTTPS.
2. Abre o endereço no Google Chrome no Android.
3. Usa "Instalar aplicação" / "Adicionar ao ecrã inicial".
4. A aplicação aparecerá com o nome STUG Guarda.

## Importante
- A localização GPS precisa de HTTPS.
- A pesquisa de locais e os mapas podem precisar de internet.
- O service worker permite abrir a interface da app quando estiver sem internet, mas os mapas/serviços externos não ficam totalmente offline.
