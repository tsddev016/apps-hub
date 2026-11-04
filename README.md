# apps-hub

Banco de dados do **Hub de Apps**.

- `manifest.json` lista todos os apps: nome, descri\u00e7\u00e3o, tecnologia, vers\u00e3o e como abrir.
- Cada pasta `<id-do-app>/` guarda a vers\u00e3o mais recente dos arquivos desse app, compactada como `.zip` num Release desta p\u00e1gina (aba "Releases", bot\u00e3o "Create a new release").
- O campo `url_zip` de cada app no manifest.json deve apontar para o link direto desse `.zip` (o link do arquivo anexado no Release).

Este reposit\u00f3rio \u00e9 lido pelo app **Hub de Apps** (Python/tkinter) no PC do usu\u00e1rio, que baixa, instala, abre e desinstala cada app daqui.
