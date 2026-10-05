# Verificação dos dossiês — 04/10/2026

## Estado

Os oito dossiês lógicos foram gerados em nove arquivos PDF, porque o PDF 8 foi dividido em `a` e `b`. Estes PDFs são **versões de evidência com cobertura declarada**, não certificação de leitura semântica integral de todos os arquivos. Nenhuma conclusão de carreira foi produzida.

## Checagens reproduzidas por `verificar_saida.py`

- 1.273 arquivos inventariados: 877 com texto extraído, 368 sem extração textual, 26 excluídos por privacidade e 2 arquivos temporários de edição.
- 2.133 falas distintas com marcador explícito; 2.133 têm correspondência textual exata no arquivo de origem.
- 30 trechos entre aspas nas notas dos PDFs 3–7; todos encontrados exatamente no corpus extraído e todos com no máximo 25 palavras. As duas citações do PDF 1 são verificadas pelo gerador contra `falas.jsonl` e pela checagem geral das falas contra a origem.
- Nenhuma data atribuída no inventário ou nas falas carece do campo `origem_da_data`. Datas de modificação em lote não foram tomadas como data de produção ou fala.
- Os nove PDFs têm no máximo 10 páginas cada; `08_dossie_a.pdf` e `08_dossie_b.pdf` são uma divisão lógica do oitavo dossiê.

## Discrepâncias e limites

- O mapeamento enviado pelo usuário tem 1.261 entradas; a contagem local é 1.273 porque inclui também os 12 ZIPs de cópia na raiz. Os dois totais são compatíveis com essa diferença de escopo.
- Citações testadas sem correspondência exata: zero. Conflitos de data confirmados nos marcos examinados: nenhum. **Não houve auditoria cronológica de todos os 877 textos**, portanto isso não certifica inexistência de conflito no corpus.
- O inventário de 877 textos inclui código, XML de SVG, versões, páginas salvas, pesquisas de IA e transcrições agregadas. Extração textual não equivale a leitura semântica, autoria individual ou validação de conteúdo técnico.
- Os PDFs 2-5 apresentam casos e obras selecionados; os PDFs 6-7 registram decisões e episódios selecionados. Muitos itens citados não tiveram revisão semântica linha a linha. O PDF 8 indexa 476 documentos principais; os 401 textos restantes continuam rastreados em `inventario.jsonl` e incluem formatos estruturados, duplicações, transcrições agregadas e arquivos de apoio.

## Sem leitura ou sem interpretação integral

- 368 arquivos sem extração textual, incluindo imagens raster, áudios, modelos Blender e outros formatos binários. Seus caminhos e motivos estão em `sem_extracao.jsonl`; 12 ZIPs da raiz representam cópias das pastas já presentes.
- 26 arquivos omitidos por privacidade: 8 WhatsApp, 16 de temas sensíveis e 2 de chaves. O conteúdo dos arquivos de chaves não foi aberto; os nomes de todos os arquivos excluídos foram mascarados no inventário gerado.
- 2 lockfiles ignorados.
- O texto dos 877 arquivos foi extraído, mas a maior parte ainda não recebeu leitura semântica integral. Imagens, áudio, visual de modelos e artefatos executáveis citados nas conversas não foram validados. Portanto **não é correto afirmar que todo o conteúdo da pasta foi absorvido**.
