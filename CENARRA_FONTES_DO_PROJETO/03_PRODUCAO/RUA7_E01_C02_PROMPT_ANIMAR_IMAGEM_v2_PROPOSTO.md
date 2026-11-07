# Rua 7 — Cena 02: animar a imagem, sem reconstruir o set (v2)
**Data:** 07/11/2026  
**Status:** PROPOSTO / NÃO TESTADO — substitui apenas a proposta de prompt, não altera o roteiro nem canoniza imagens.

## Evidência e motivo
O usuário relatou dois erros críticos no teste de 8 segundos: Mara olhando fora do alvo e falas simultâneas de Beto/Nilo. Três novas imagens com geometria inconsistente fizeram objetos mudar de posição e degradaram a qualidade de câmera. A sugestão externa "Animate this image only" é uma boa técnica de foco, mas não garante preservação absoluta nem lip-sync multiator.

**Fontes oficiais:**
- https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/video/best-practice?hl=pt-BR — usar imagem original nítida e pedir principalmente movimento.
- https://support.google.com/flow/answer/16353334?hl=pt-BR — Frames vs Elementos/Ingredientes; evitar imagens conflitantes.
- https://deepmind.google/models/veo/prompt-guide/ — enquadramento, atuação e diálogo.

## Procedimento proposto para UMA geração de 8 segundos
1. Usar **uma única imagem-mestra original nítida** do mercadinho como **FRAME INICIAL** (de preferência a própria imagem-fonte aceita na Cena 01), **não** três composições inconsistentes. Não reutilizar recortes ampliados do MP4 512x910 como se fossem masters.
2. Preservar set real e posições: Mara cliente à esquerda; Beto centro-fundo junto ao caixa verde; Nilo à direita atrás do balcão; banca listrada diante do balcão. Não deslocar objetos nem mudar o eixo.
3. Pedir só movimentos pequenos: rostos/olhos/boca de quem fala/sobrancelhas/mãos; leve rack focus; câmera quase parada; close extra na edição, não no render.
4. Três falas PT-BR em **turnos exclusivos** com breve silêncio:
   - 0–2,2s **Mara → Nilo**: `Você não é dono da praça.` (firme e incisiva; olha e aponta somente para Nilo).
   - 2,2–2,4s silêncio.
   - 2,4–4,5s **Beto → Mara**: `Tem vaga nessa banca?` (audacioso; olha para Mara, mão aberta, sai de perto de ninguém).
   - 4,5–4,8s silêncio.
   - 4,8–7,7s **Nilo → Beto**: `Beto! Você trabalha pra mim!` (espanto vira indignação; vira olhos/rosto para Beto ao fundo).
   - 7,7–8,0s silêncio; reação muda em Beto.
5. No clipe, somente o falante move os lábios; os outros **boca fechada**. Sem música/efeitos/locução durante geração; adicionar depois no editor.
6. **Porta QA:** três falas na ordem exata, sem simultaneidade, olhos corretos, espécies/vestuário/objetos/forma preservados. Qualquer falha: reprovar, não publicar.

## Riscos e limites
O Flow/Veo não oferece garantia de três vozes distintas em 8s nem de sincronização total só por texto. Vozes iguais à Cena 01 não são recuperáveis de mera descrição. O recurso de voz por referência descrito pelo Flow aplica-se a referência de um falante, conforme a disponibilidade do modelo e do modo. Evitar continuar gastando gerações em imagens de objetos inconsistentes. **Nenhuma execução nem aprovação na conta Flow ocorreu neste registro.**
