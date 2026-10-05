# Etapa 0 — extração conservadora

Corpus inventariado: 1.273 arquivos no diretório, incluindo os 12 ZIPs de cópia. Foram extraídos textos de 877 arquivos. Outros 368 não tiveram extração textual (mídia, binários, ZIPs e formatos não suportados), 26 foram excluídos por privacidade e 2 eram arquivos temporários de edição.

Foram identificadas 2.133 falas distintas de Gabriel por marcador explícito em 41 arquivos: Artigos 10; Jogos 37; Livros 59; Quem Sou Eu 2.027. Essas falas somam 2.443.151 caracteres. Duas têm data atual explícita (06/02/2025 e 17/12/2025); as demais permanecem com data incerta. A rotina não converte referências a datas mencionadas no corpo de conversas em data da própria fala sem marcador temporal atual explícito. Esse é um limite deliberado para evitar cronologia falsa.

Arquivos de base: `falas.jsonl`, `inventario.jsonl`, `sem_extracao.jsonl` e `resumo_etapa_0.json`. A coluna `autor` só identifica Gabriel quando há marcador explícito. Os demais textos extraídos não receberam atribuição de autoria. Há 140 cópias textuais idênticas e 16 arquivos de segmentação marcados como possível duplicação; não entraram novamente na contagem de falas.

Cobertura: texto extraído de TXT, MD, CSV, JSON, HTML, DOCX, PDF, XLSX, PY, CSS, MJS, PS1, INI e SVG. Áudio, imagens raster, projetos binários, páginas auxiliares e ZIPs não foram interpretados semanticamente. SVG foi lido como XML textual, sem inspeção visual. Conversas WhatsApp e material sensível foram excluídos; a pasta de chaves de API não foi aberta. O inventário mascara os nomes dos arquivos excluídos. Não foram usadas conclusões anteriores como evidência.

**Correção de escopo do usuário:** o material coproduzido com IA é parte central do corpus e será analisado como conteúdo. A autoria é uma etiqueta de evidência para não atribuir elogios ou avaliações da IA a Gabriel; não serve para excluir obras, projetos nem desenvolvimento conjunto.

Pendências antes de afirmar leitura integral: analisar semanticamente os 877 textos, conferir colaboração e autoria de afirmações específicas, datas locais em cada fala, mídias relevantes, equivalência das segmentações e privacidade de cada trecho a citar. A contagem de falas é uma contagem conservadora de marcadores, não uma medida completa de produção própria.
