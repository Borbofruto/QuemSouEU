# Etapa 2 — trabalho técnico, leitura inicial de evidências

## Linha temporal declarada

`Linkedin/Atual/Perfil-Linkedin_Gabriel-Nascimento_Main.pdf`: perfil registra simulação industrial na Payback (nov/2025–mai/2026) e desenvolvimento de robótica e automação (mai/2026 em diante). São períodos internos do perfil; data da exportação incerta. Perfil lista Emulate3D, RoboDK, QuickLogic/C# na simulação; UR, JAKA, C#/.NET, Python, RoboDK e integração CLP/IHM no cargo seguinte. Também nomeia paletização, formadora de caixas, soldagem e acabamento superficial como tipos de POC, sem identificar clientes nem estágio de cada aplicação.

## Casos com rastros próprios

1. **Cisa Brasile — lixamento/polimento com UR15.** `Quem Sou Eu/Conversa com gpt Problemas com Trajetória UR15.md` (data incerta): Gabriel descreve montagem de TCP e payload, trajetória em zigue-zague, plano da peça, teste de payload alternativo e espera após ligar a politriz. Relata variação de avanço, força e recuo entre execuções. `Quem Sou Eu/conversa com gpt CLIENTE Cisa Brasile - Aplicação LIxamento e Polimento.md` (conversa com referência interna à V2 de 20/08/2026): histórico coproduzido separa estado da V2, resultados, hipóteses e pendência de instrumentação quantitativa. O texto menciona programas em outra pasta, mas estes não fazem parte do Pacotão; a implementação não foi verificada aqui contra o arquivo do robô.
2. **Emulate3D — transportadores, sensores, pusher e stop.** `Quem Sou Eu/COnversa de intensisvo sobre pushers Emulat3d.txt` (data incerta): Gabriel descreve esteira, zonas MZA, photoeye, blade stop, pusher e tentativas em QuickLogic. Há falhas de configuração e teste reportado de acionamento de pusher. Algumas respostas de um agente chamado Roberto foram inseridas no mesmo bloco textual; não são atribuídas a Gabriel. Não há projeto nativo Emulate3D neste Pacotão que permita confirmar comportamento final.
3. **RoboDK — aprendizado e simulação de paletização.** `Quem Sou Eu/Aprendendo roboDK.txt` (referência interna a vídeo de 25/11/2025, data da conversa incerta): Gabriel relata configurar biblioteca local e UR5e; depois importar estação e garra do Blender, organizar targets e frames, testar um nível de pallet e finalizar uma simulação de processo para a Vale. São relatos de teste e resultado na conversa, não uma validação do projeto nativo, que não foi localizado neste corpus.
4. **Paletização JAKA — ensaios empíricos.** `Automaturgia/Interno/Main/Estudos/Ciclos por minuto - Velocidade de TCP/Testes Empíricos/` contém ensaio A, relatórios B/C/D, planilhas de parâmetros e logs. `Linkedin/Atual/Perfil-Linkedin_Gabriel-Nascimento_Main.pdf` anuncia estudo com 125 condições e cerca de 7.500 ciclos. Números, condições e conclusões precisam ser recalculados dos relatórios/logs antes de entrar no PDF 2.
5. **Arquitetura técnica e alcance de paletização.** `Automaturgia/relatorio_alcance_paletizacao.md` (data incerta) discute alcance nominal versus funcional, pallet, pedestal, offset de garra e configuração de punho. É um documento técnico produzido no corpus, não evidência de implementação ou validação física de todas as recomendações numéricas.

## Pendências

Ler o restante dos documentos técnicos e cruzar as falas com entregáveis. Em cada caso, diferenciar o que Gabriel relatou fazer, o que um documento coproduzido especifica e o que foi medido ou executado. Frases de satisfação, frustração e orgulho serão usadas só quando ligadas a atividade identificável e com data ou data incerta marcada. Sem concluir carreira.

O PDF 2 acrescenta índice complementar dos arquivos técnicos extraídos do Pacotão. A lista documenta existência e volume, não substitui leitura semântica ou validação de código e hardware.
