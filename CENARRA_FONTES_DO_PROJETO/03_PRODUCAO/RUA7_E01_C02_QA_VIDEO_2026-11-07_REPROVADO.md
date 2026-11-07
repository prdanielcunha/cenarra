# Rua 7 — Cena 02 — QC de vídeo recebido (07/11/2026)
**Status: REPROVADO COM EVIDÊNCIA VISUAL.**
**Mídia privada analisada:** `Characters_arguing_in_grocery_store_1934c0a0.mp4` (~7,93s; 512 × 910; 30 fps, H.264/AAC); **não subir MP4 ao GitHub público**.

## Comparação com roteiro oficial
Fonte: `../02_SERIES/RUA7_P01_A_CONCORRENTE_DA_PORTA_v1_ROTEIRO_PROPOSTO.md`.
- 08–12s: MARA, tomate vermelha, enfrenta NILO, laranja, **afirma com firmeza**: `Você não é dono da praça.`
- 12–16s: BETO, brócolis verde de camisa cáqui, vira-se para MARA e pergunta, com humor atrevido: `Tem vaga nessa banca?`
- 16–20s: NILO, laranja de camisa bege e avental azul-marinho, reage ao BETO, indignado: `Beto! Você trabalha pra mim!`
O texto base reserva **12 segundos** para o conjunto. Tentativas anteriores o comprimiram em **8 segundos** (33% menos).

## Constatações visuais no vídeo
- **0,0s em diante**: pessoa **humana** de cabelo castanho e uniforme azul/cinza atrás do balcão/caixa. Continua visível em parte do vídeo, inclusive depois de 5s; não pertence ao trio da Rua 7. QUEBRA DE ELENCO.
- **0,0–1,5s**: Mara à esquerda aponta e encara Nilo à direita; a ação é parcialmente reconhecível, mas o usuário informa entonação **não assertiva/brava** na frase que deveria ser afirmação firme.
- **~1,5–2,0s**: transição por sobreposição/dissolve com ghosting dos personagens, em vez de corte limpo motivado.
- **~2,0–4,5s**: plano próximo do brócolis Beto com boca e mão ativas. Ele parece personagem ativo visualmente, porém **o responsável relata que sua voz é a de Mara**. Não foi executada diarização vocal autônoma, então a identificação acústica específica é relatada pelo usuário, não inferida de imagens.
- **~4,5–5,0s**: segunda sobreposição de planos (ghosting).
- **5,0–7,9s**: plano do trio com pessoa humana adicional; Beto deslocado visualmente para perto de Nilo, cuja mão aponta; Beto encerra com expressão de aparente satisfação em vez de espanto convincente. O usuário relata que **Nilo termina a fala de Beto usando voz de Mara**; precisa ser confirmado pela audição e confronto com trilhas originais.
- Continuidade do set alterada entre enquadramentos (janela, balcão, caixa, toldo e banca em miniatura têm relações visuais que não seguem claramente uma câmera única e planta travada). Em 512 × 910, close digital ampliado reduz detalhes.

## Evidência objetiva da estrutura de áudio
`ffmpeg silencedetect noise=-33dB:d=0.12` apontou intervalos abaixo do limiar:
- 1,5445 a 2,5608s (~1,02s);
- 3,7733 a 4,7946s (~1,02s);
- subsequências fracas/silenciosas entre ~5,39 e ~6,33s;
- 7,4968 a 7,936s (~0,44s).
Isso descreve intensidade do áudio, **não transcreve** palavras ou determina locutores. Em um clipe de 8s, duas pausas de ~1s comprimem ainda mais o diálogo restante.

## Interpretação técnica
A causa exata de confusão de vozes não pode ser demonstrada somente pelo MP4. Há correlação com: três falantes e identidade vocal dentro de 8s, planos com mais de um rosto, fichas de áudio que no Flow mostraram aviso de limite **1 elemento de áudio**, e referências de imagem divergentes. Não afirmar causalidade comprovada de cada fator.
As tentativas anteriores de mudar só o texto não resolveram. **Não aprovar nem publicar.**

## Direção correta / critérios de aceitação
1. Preservar somente Mara (tomate, bordô, mãos vermelhas); Beto (brócolis, cáqui, mãos verdes); Nilo (laranja, bege/azul, mãos laranja); zero humanos ou figurantes.
2. Locutores corretos, três vozes distintas sem trocas, texto literal, PT-BR, pausas naturais e sincronização labial da boca certa.
3. Mara: afirmação seca, indignada, ênfase em `não`, termina em tom **descendente**, olhando para o rosto de Nilo; sem entonação interrogativa.
4. Beto: pergunta atrevida para Mara, ligeiro sorriso, depois perde confiança; não receber voz de Mara nem de Nilo.
5. Nilo: espanto > decepção > indignação; responde **para Beto** em voz masculina mais grave; Nilo não conclui a frase de Beto.
6. Cortes editoriais diretos, eixo e cenário-mestre fixos, maquete única de banca sempre no mesmo lugar; sem ghosting, morphing, humanos ou alterações de objetos.
7. Reconhecer restrição operacional de 8s/geração, mas **não sacrificar o roteiro** nem prometer que três falantes em 8s são confiáveis. Comparar alternativa de controle de vozes em edição ou redistribuir as tomadas antes de novo gasto.

**Próxima ação:** responsável decide nova estratégia de produção. Não executar nova geração sem controle de custo e sem referências aprovadas.
