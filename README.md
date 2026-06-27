# moneybot-releases

Repositorio de releases do MoneyBot para auto-update.

## Como funciona

O arquivo latest.json e lido pelo app para verificar se ha uma nova versao disponivel.

## Publicar nova versao

1. Gere o instalador: `npm run release`\n2. Crie uma release no GitHub com a tag `vX.Y.Z`\n3. Anexe o arquivo `MoneyBot-Setup-X.Y.Z.exe`\n4. Atualize `latest.json` com a nova versao e URL
