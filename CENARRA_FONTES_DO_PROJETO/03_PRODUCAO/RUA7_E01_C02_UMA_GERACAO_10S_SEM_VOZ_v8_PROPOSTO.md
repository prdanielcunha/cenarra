# Rua 7 — Cena 02 — v8: uma geração visual de 10 s e dublagem editorial independente

**Data:** 07/11/2026. **Estado:** PROPOSTO, NÃO TESTADO NO FLOW, NÃO APROVADO.

## Motivo e correções
Responsável reafirmou limite desejado de **UMA** geração de vídeo, **10 segundos**, utilizando somente créditos disponíveis sem pagamentos. Planos v6/v7 com três gerações não respeitam a restrição. Testes anteriores de 3 falas nativas em 8 s produziram troca de vozes (Mara/Beto/Nilo), humano extra, trocas de mão/figurino e ghosting. Captura do Flow mostrou limite de **uma referência de áudio** na configuração usada; isso não equivale a limite global de apenas uma voz gerada.

## Fluxo v8 escolhido
1. **Uma única imagem-mestra** original de trio/mercadinho, sem redesenho (no pacote privado: `confronto_no_mercado_da_praça.png` = 941×1672, cópia idêntica `CENARRA_RUA7_REFERENCIA_ORIGINAL_TRIO_PARA_FLOW.png`). Fotograma não foi apresentado como novo desenho nem aprovado para publicação. Mara TOMATE à esquerda cliente, Nilo LARANJA à direita atrás do balcão, Beto BRÓCOLIS centro-fundo junto ao caixa, banca miniatura em cima do balcão, janela esquerda.
2. **Google Flow > Omni Flash 1.2 > Frames > apenas PRIMEIRO frame > vertical 9:16 > 10 s > UMA saída**. Não adicionar último frame, cards @personagens com voz, imagem contraditória ou textão de três falas. Prompt solicita **apenas atuação visual SILENCIOSA**, com reação, eyelines, rack-focus/push-in suave e geografia travada; o vídeo pode ser mutado integralmente na edição, mesmo se houver falas inventadas.
3. **CapCut mobile**: três vozes PT-BR em faixas separadas (texto para fala ou gravação), ordem e palavras canônicas. Usar cortes de reação (plano/contraplano, J/L) e cortes internos de imagem do **mesmo clipe** com reenquadramento moderado (5–10%) para esconder movimento labial imperfeito e criar ritmo de novela. Nenhuma trilha com vozes sobrepostas. CapCut TTS é recurso disponível mas timbres Flow NÃO são automaticamente importáveis para CapCut.
4. Roteiro de edição 10 s: MARA `Você não é dono da praça.` (0–2,55; bravo e declarativo) → 0,5s reação → BETO `Tem vaga nessa banca?` (3,05–5,15; ousado, a Mara) → 0,5s espanto Nilo → NILO `Beto! Você trabalha pra mim!` (5,65–8,35; indignação magoada, a Beto) → 1,65s reação silenciosa. Ajustar janelas à duração real da fala sem acelerar artificialmente.
5. **Qualidade:** não publicar se humano aparecer, mão de Nilo verde, caixa/banca/samambaia duplicar, espécies/vestes mudarem, olhar apontar para alvo errado, cena ficar sem emoção, fala misturada, ou lip-sync em close chamar atenção. Não há garantia de lipsync exato, pois vozes são adicionadas na pós; mostrar ouvintes enquanto falante está fora de quadro é solução de linguagem audiovisual, não substituto técnico de lipsync.

## Créditos e modelos — fontes oficiais (07/11/2026)
- Omni Flash 1.2: 10s em 360p = **10 créditos**; 720p = **30 créditos**, por geração. Verificar custo na própria conta antes de iniciar; 360p não oferece detalhes nativos de 720p e upscale não os cria. Google AI Plus/Pro/Ultra podem fazer upscale de até 10s a 720p/1080p sem créditos adicionais quando disponível.
- Veo 3.1 Lite: até 8s, **não serve para 10s**.
- Links: https://support.google.com/flow/answer/16352836?hl=pt-br ; https://support.google.com/flow/answer/16526234?hl=pt-BR ; https://support.google.com/flow/answer/16353334?hl=pt-BR ; https://www.adobe.com/pt/creativecloud/video/production/cinematography/camera-shots-and-angles/reverse-shot.html ; https://helpx.adobe.com/br/premiere/desktop/edit-projects/trim-clips/perform-j-cuts-and-l-cuts.html ; https://www.capcut.com/pt-br/resource/capcut-voice-over .

## Pacote de trabalho entregue na conversa (MÍDIA PRIVADA NÃO SUBIR AO GITHUB)
`CENARRA_C02_UMA_GERACAO_10S_FLOW_CAPCUT.zip`: uma cópia de PNG do trio original 941x1672; prompt completo para um vídeo **silencioso**; roteiro de voz e cortes no CapCut; leia-primeiro.

**Próxima etapa:** gerar uma vez sob custo exibido, validar **primeiro o visual**, somente depois aplicar TTS/dublagem. Não afirmar que v8 foi testada, aprovada ou publicada.
