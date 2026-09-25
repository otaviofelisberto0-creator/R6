# Dashboard Conversão ND e BL - Versão Oficial

A versão oficial do dashboard tem como base o arquivo completo `index_conversao_FINAL_V19.html`, com os ajustes evoluídos na V20.

## Estrutura

- `index.html`: dashboard completo com todas as páginas, análises, tabelas, rankings, comparativos e exportações.
- `dados/manifest.json`: lista dos arquivos JSON publicados.
- `dados/ND-2606.json`: incluir o arquivo ND já gerado.
- `dados/BL-2606.json`: incluir o arquivo BL já gerado.

## Ajustes V20

- Rankings Regional e Cluster lado a lado em telas de computador.
- Títulos dos rankings atualizados conforme o tipo selecionado: Conversão ND, Conversão BL ou Conversão ND + BL.
- Preservação das páginas Conversão, Análise Diária, Acompanhamento Mês x Mês, Dados da Conversão e Tabela de Critério.
- Preservação dos comparativos ND e BL, resumo gerencial, auditoria e exportações.

## Atenção

O `index.html` completo preserva o fluxo de upload e validação dos CSVs da versão V19. Os JSONs compactos atuais permanecem na pasta `dados`, mas a carga automática desses JSONs precisa usar um formato compatível com todos os campos exigidos pelas análises completas.
