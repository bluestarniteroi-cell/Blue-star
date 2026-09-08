# Blue Star — Controle de Estoque (PWA)

Projeto pronto para publicar no GitHub Pages e instalar pelo Google Chrome no Android.

## Estrutura
- `index.html` — aplicativo
- `manifest.webmanifest` — configuração de instalação PWA
- `service-worker.js` — funcionamento offline/cache
- `offline.html` — página de contingência
- `assets/logo.png` — logo usada no aplicativo
- `icons/icon-192.png` — ícone 192x192
- `icons/icon-512.png` — ícone 512x512
- `.nojekyll` — evita processamento do Jekyll no GitHub Pages

## Publicação no GitHub Pages
1. Crie um repositório público chamado `blue-star` na conta `azulstarniteroi`.
2. Envie **o conteúdo desta pasta**, e não a pasta externa, para a raiz do repositório.
3. Em `Settings` → `Pages`, selecione `Deploy from a branch`.
4. Escolha `main` e `/ (root)` e salve.
5. Aguarde a publicação.

URL esperada:
`https://azulstarniteroi.github.io/blue-star/`

## Instalação no Chrome
Abra a URL no Chrome do Android. Use `⋮` → `Instalar aplicativo` (ou `Adicionar à tela inicial`, conforme a versão do Chrome).

## Logo
`assets/logo.png` está preparado como arquivo de logo do app. Se precisar trocar pela logo oficial, mantenha o nome `logo.png`.

## Dados
Produtos, movimentações e dados da empresa são armazenados localmente no aparelho/browser. Use `Exportar backup` para salvar uma cópia JSON.
