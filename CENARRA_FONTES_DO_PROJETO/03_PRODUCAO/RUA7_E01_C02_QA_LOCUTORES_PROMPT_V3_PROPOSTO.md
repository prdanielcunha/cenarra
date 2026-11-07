# Rua 7 — Cena 02 — QA de locutores e prompt v3
**Data:** 07/11/2026. **Status:** TESTE RECEBIDO E REPROVADO (vídeo), NOVO PROMPT PROPOSTO NÃO TESTADO (sem novo vídeo).

## Evidência
O responsável forneceu o arquivo privado `Micro-telenovela_scene_dialogue_…_d35a5719.mp4`, com ~7,93s e 512×910. A inspeção visual de fotogramas entre ~2,3s e ~4,1s mostra Nilo (laranja em primeiro plano) com gestos/faces de personagem ativo, enquanto Beto (brócolis verde ao fundo) observa e reage. O responsável confirmou em áudio perceptivo que **Nilo falou a fala de Beto com voz atribuída ao Beto**. A inspeção de fotogramas não comprova identificação acústica isolada; considerar o relato do responsável como evidência vocal, não transcrição automática.

## Diálogo canônico — NÃO alterar
1. MARA (tomate vermelha, blazer vinho, esquerda; voz feminina adulta) → NILO: **Você não é dono da praça.**
2. BETO (brócolis verde, camisa cáqui, junto ao caixa verde no centro-fundo; voz masculina mais jovem) → MARA: **Tem vaga nessa banca?**
3. NILO (laranja barbada, camisa bege, avental azul-marinho, à direita atrás do balcão; voz masculina adulta mais grave) → BETO: **Beto! Você trabalha pra mim!**

## Mudança material proposta
O prompt anterior já distinguia nomes e figurinos, porém manteve Nilo grande e visível durante o turno de Beto, circunstância que coincidiu com a troca de falante. O novo roteiro de câmera mantém uma única geração de 8s, mas solicita um **corte editorial para um plano médio fechado somente de Beto na sua posição original** durante sua pergunta, com Mara e Nilo totalmente fora de quadro. Depois, retorna para Nilo responder. Não usar zoom digital em quadros 512×910; o plano é enquadramento gerado a partir da mesma geometria, não deslocamento de objeto. Os três personagens nunca mudam de posição física.

- 0–2,20s: Mara (tomate) fala com Nilo (laranja) em dois-shot.
- 2,20–2,40s: silêncio e corte de câmera.
- 2,40–4,50s: Beto (brócolis), **único rosto visível**, fala com Mara fora de quadro.
- 4,50–4,75s: silêncio e corte de câmera.
- 4,75–8,00s: Nilo (laranja) repreende Beto ao fundo; Beto fica calado.
- Descrever a espécie, cor, figurino, posição e identidade vocal **imediatamente antes da fala** com `says:` sem aspas; preservar cenário, iluminação e eixo.
- Sem música gerada ou efeitos durante diálogo; controles finais no CapCut.

## Limites
Cortes e três locutores dentro de um vídeo de 8s são instruções ao modelo, **não recursos determinísticos de trilhas isoladas**. A estratégia reduz a ambiguidade mas NÃO garante sucesso ou preservação de voz idêntica à Cena 01. Não gastar novos créditos supondo garantia. Caso o modelo persista em falar com Nilo no turno de Beto, interromper nova rodada de prompts similares e optar por vozes separadas em edição ou reavaliar restrição de um clipe.

**Referências oficiais:** https://deepmind.google/models/veo/prompt-guide/ e https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/video/best-practice .

**Mídias:** MP4 privado não foi enviado ao GitHub público. Artefato de prompt entregue separadamente na conversa: `CENARRA_RUA7_C02_PROMPT_FLOW_3_LOCUTORES_8S_OTIMIZADO.txt`.
