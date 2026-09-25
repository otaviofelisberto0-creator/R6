# Dashboard Conversão ND e BL

## Estrutura
- `index.html`: dashboard completo.
- `dados/manifest.json`: relação dos arquivos JSON publicados.
- `dados/`: pasta em que devem ser enviados os JSONs ND e BL gerados pelo dashboard.

## Publicação
1. Envie todos os arquivos e a pasta `dados` para a raiz do repositório.
2. No GitHub Pages, selecione a branch `main` e a pasta `/ (root)`.
3. Abra o dashboard, carregue os CSVs ND e BL, converta e baixe os JSONs.
4. Envie os JSONs gerados para a pasta `dados`.
5. Atualize `dados/manifest.json` com os nomes exatos dos arquivos.

Exemplo:

```json
{
  "files": [
    "ND-26-09.json",
    "BL-26-09.json"
  ]
}
```
