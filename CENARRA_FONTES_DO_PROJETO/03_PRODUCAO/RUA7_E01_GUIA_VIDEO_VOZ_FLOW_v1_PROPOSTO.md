# CENARRA · RUA7-P01 · Guia de vídeo, vozes e montagem — v1 (PROPOSTO)
**Data:** 2026-11-06. **Estado:** GUIA TÉCNICO PREPARADO, sem prova de geração ou aprovação visual.  
**Roteiro-fonte:** `../02_SERIES/RUA7_P01_A_CONCORRENTE_DA_PORTA_v1_ROTEIRO_PROPOSTO.md` (não alterar diálogos).  
**Referências obrigatórias:** `RUA7_MASTER_LOCK_PERSONAGENS_CENARIO_v1.md` e `../02_SERIES/REFERENCIAS_VISUAIS/LOCKS_MERCADINHO_E01_v1.md`.

## 1 — Objetivo
Animar as imagens individuais existentes de *A concorrente da porta*, em 9:16, mantendo Mara (tomate, blazer vinho, saia grafite e joias), Nilo (laranja barbuda, camisa bege, avental azul-marinho) e Beto (brócolis, cáqui, sem avental). Mercadinho com balcão de madeira, caixa verde-petróleo, janela/luz dourada à esquerda, samambaia, luminária verde e estantes fixas.

**Não afirmar que todos os 14 PNGs estão concluídos.** Em 06/11 o GitHub só documenta lote 01, com 7 imagens reaproveitadas/re-enquadradas ainda não aprovadas; o usuário informa em conversa posterior que possui imagens das cenas, mas os bytes/QA não foram inspecionados nesta tarefa. Conferir arquivos no dispositivo antes de gerar.

## 2 — Escolha de ferramenta e custos oficiais em 06/11/2026
1. **Google Flow, teste de voz controlada:** Omni Flash 1.2, `Vídeo > Elementos/Referências`; adicionar referência visual e `Vozes` (se habilitada no país/conta), usar a **mesma voz** selecionada a cada tomada daquele personagem. Criar voz personalizada quando disponível. Só o modo Elementos permite referência de voz. **Não supor que Frame inicial tenha a mesma função.**
2. **Google Flow, teste de fidelidade de imagem:** Veo 3.1 Lite `Vídeo > Frames > primeiro frame`, 4/6/8s e 720p, 10 créditos/geração para planos não Ultra; permite aproveitar enquadramento, mas **não assegura que a voz se repita entre tomadas**. Não usar a saída de uma cena divergente como master.
3. **Omni Flash 1.2:** 360p = 1 crédito/segundo, 720p = 3 créditos/segundo (até 10s sem assinatura), taxa atual sujeita a mudança. Usar 360p para experimentar vozes/poses e 720p somente após prova satisfatória. 50 créditos gratuitos diários, não acumuláveis; disponibilidade e modelos variam. Ver custo antes do botão Gerar.
4. **Grok Imagine** pode servir para comparação, mas não para padrão principal enquanto limites gratuitos, fidelidade e vozes não forem validados. O Grok pode aplicar marca d'água e a remoção de sinais de proveniência é proibida. **CapCut** para montagem, legendas e som; lip-sync dedicado só como contingência testada, não como garantia de realismo.
5. **Direitos:** conferir termos de ferramenta, vozes, marca-d'água e política de cada plataforma na conta usada antes de publicação/comercialização.

Fontes oficiais:
- https://support.google.com/flow/answer/16352836?hl=pt-BR
- https://support.google.com/flow/answer/16353334?hl=pt-BR
- https://support.google.com/flow/answer/16526234?hl=pt-BR
- https://support.google.com/flow/answer/16353333?hl=pt-BR
- https://docs.x.ai/grok/faq
- https://www.capcut.com/pt-br/help/lip-sync-feature

## 3 — Vozes reutilizáveis propostas (sem imitar indivíduos reais)
- **VOICE_MARA_01:** mulher brasileira adulta, voz médio-grave, firme, ligeiramente rouca, enunciação clara; ironia contida nos primeiros planos, vulnerabilidade sem choro na revelação. Nunca caricata/infantil.
- **VOICE_NILO_01:** homem brasileiro maduro, médio-grave, textura levemente áspera e calor humano; indignação surpresa, depois dor. Não gritar.
- **VOICE_BETO_01:** homem brasileiro jovem adulto, timbre médio, ligeira malícia e naturalidade coloquial; pausas precisas para humor e negociação. Não acelerar.
Salvar identificador de voz escolhido, prévia e parâmetros no armazenamento de produção para todos os futuros episódios.

## 4 — Restrições globais a repetir com todas as imagens
```text
Use EXACTLY the uploaded scene image as the visual anchor. This is a cinematic 3D Brazilian neighborhood microdrama for adult viewers, vertical 9:16. Preserve the exact character species, head silhouette, vegetation, facial features, outfit, accessories, body proportions, scene layout, cash register, counter, light direction and camera axis. Warm golden late-afternoon lighting from camera left. Natural restrained facial acting, small mouth movement only for the one named speaker, subtle breathing and eye movement. Never add/remove characters, furniture, objects, limbs, leaves or accessories. Never change clothing or locations. Only one specified character speaks. Brazilian Portuguese (pt-BR), exact line verbatim, no additional dialogue, no narration, no music, no subtitles, no titles, no logos, no camera flips. The remaining visible characters must stay silent.
```
**Observação:** anexar o frame correto + imagens-mestras físicas (quando ferramenta suportar) a cada geração. Texto sozinho não garante consistência. A menção a pt-BR também não garante voz nem lip-sync exatos — validar ouvido e quadro a quadro.

## 5 — Plano de tomadas / prompts de ação e voz
Cada linha abaixo é um comando COMPLEMENTAR à restrição global, não substitui o uso do PNG correspondente nem dos masters. Sempre **uma única fala por clipe**.

| ID | Tempo roteiro | Ator / fala **EXATA** | Desempenho / câmera / prompt complementar |
|---|---|---|---|
| 01 | 0–3s | MARA: “Amanhã eu abro minha banca na sua frente!” | Começar com Mara já deslizando uma única miniatura de banca sobre balcão, olhar frontal incisivo para Nilo. Leve aproximação, sem introdução. Testar 4s de geração e aparar na edição; se ritmo artificial, retemporizar o corte sem adulterar voz. |
| 02 | 3–8s | NILO: “Dez anos longe daqui... e você volta pra isso?” | Close de Nilo atrás do balcão, sobrancelhas sobem; cabeça inclina um pouco, espanto magoado. Pausa respiratória depois de “daqui”. |
| 03 | 8–12s | MARA: “Você não é dono da praça.” | Close firme de Mara, expressão seca, movimentos mínimos. Mesma identidade e roupa. |
| 04 | 12–16s | BETO: “Tem vaga nessa banca?” | Beto junto ao caixa retrô, vira o olhar com interesse sincero e um meio sorriso; timing leve de humor. |
| 05 | 16–20s | NILO: “Beto! Você trabalha pra mim!” | Nilo vira a cabeça para Beto e abre uma mão em protesto sem agressão, sem sair do lado interno do balcão. |
| 06 | 20–26s | BETO: “E ela paga hora extra, patrão?” | Beto encara Nilo por um instante, depois Mara, ironia discreta e coragem; não repetir a pose exata do 04 se houver alternativa aprovada. |
| 07 | 26–30s | MARA: “Pago. E em dia.” | Mara ergue levemente uma sobrancelha, meio sorriso seco, olhando para Beto, sem perder controle. |
| 08 | 30–35s | BETO: “Então amanhã, às oito?” | Beto se endireita ao lado do caixa e dá um pequeno passo sem trocar de figurino. **Sem tirar avental: ele nunca usou avental.** |
| 09 | inserto sem fala, opcion. | NINGUÉM | Nilo reage em silêncio ao ver a mudança de atitude de Beto. Usar take de reação/aparagem, sem diálogo artificial. |
| 10 | 35–39s | NILO: “Mara... isso é vingança?” | Close, baixo volume, mais dor do que raiva; mãos baixas, olhos fixos em Mara. |
| 11 | transição sem fala | NINGUÉM | Mara inspira, perde momentaneamente o ar confiante, respira antes de responder. |
| 12 | 39–45s | MARA: “Não. Era pra gente ter aberto juntos.” | Close final, voz baixa, fragilidade contida, hesitação delicada em “juntos”, sem lágrimas teatrais. |
| 13 | reação final | NINGUÉM | Close silencioso de Nilo processando revelação, por 0,4–0,8s úteis quando couber. |
| 14 | insert opcional | NINGUÉM | Miniatura de banca no mesmo balcão, única unidade, sem texto. Usar só se não enfraquecer corte dramático final. |

**Decisão editorial:** são 10 falas e 14 imagens/possíveis enquadramentos, NÃO 14 áudios nem 14 gerações obrigatórias. Para economizar créditos, movimento de câmera estático/zoom lento, inserts, reações e silêncio podem ser feitos diretamente no CapCut com imagem intacta.

## 6 — Fluxo enxuto de execução
1. No dispositivo, colocar 01–14 em pasta privada; separar referências originais de cada personagem e do trio; revisar espécies/roupas/objeto/luz.
2. Criar um projeto Flow `CENARRA_RUA7_E01`. Testar **tomada 03 (Mara)** para verificar imagem + fala curta e **tomada 02 (Nilo)** para segunda voz; então repetir Mara no 07 para testar **mesma voz e mesmo rosto em dois clips** antes de gastar em lote.
3. Fluxo A (voz como prioridade): escolher Omni Flash `Elementos > Vozes`, criar/selecionar voz por personagem; anexar referência individual e cenário, inserir prompt global + ação específica. Testar barato (360p) se habilitado; final 720p depois de QC. Fluxo B (visual prioritário): Veo Lite `Frames` com imagem inicial; se voz mudar, **não costurar diálogos contraditórios**; priorizar voz fora da imagem ou áudio em faixa separada.
4. Verificar antes de salvar: fala literal e inteligível, pronúncia BR, sem palavras extras, uma voz por personagem; bocas e silêncios coerentes; não deformar rosto, folhas, mãos ou cenário; não mudar axis/luz/roupa.
5. Exportar áudio e vídeo por tomada quando possível, mantendo arquivos com IDs; não depender da automação da plataforma para preservar ativos.
6. No CapCut: projeto vertical 9:16, cenas pela ordem, cortes por reação, um SFX do objeto pousado e ambiente discreto, sem música se não houver direitos; inserir legendas corrigidas manualmente, manter master sem legendas fixas separado.
7. Conferir direitos/marca-d'água/declaração de IA antes de publicar nas quatro redes. Agendar no lote experimental terça 20h, sexta 19h **somente após aprovação técnica/narrativa**, sem postar imagens extras.

## 7 — Diagnóstico de falhas
- Se a **fala sair errada**: regenerar somente o take curto com uma frase exata; nunca pedir todas as falas em um clipe.
- Se a **voz mudar**: reutilizar o mesmo elemento de voz do Omni ou fazer dublagem externa/licenciada; não publicar como se fosse consistente.
- Se **rosto ou roupa mudarem**: rejeitar. Recomeçar a partir do master original; não usar saída alterada como nova referência.
- Se o **lip-sync ficar artificial**: preferir plano de reação, boca fora do centro de foco ou fala em off, nunca um personagem com boca claramente parada num close de diálogo.
- Se a **qualidade 360p não suportar publicação**: é somente teste; usar 720p se créditos e licença permitirem, ou reduzir planos e quantidade de gerações.

**Status final deste documento:** preparado como guia de produção proposto; nenhuma geração real ou teste de acesso ao Flow/Grok foi executado por este arquivo. As imagens atuais do usuário não foram reanalisadas visualmente nesta sessão.

## 8 — QC do primeiro teste do Flow (06/11/2026): REPROVADO
**Evidência:** usuário enviou vídeo MP4 com aproximadamente 7,93 s, 512×910 pixels (arquivo de compartilhamento; não comprova resolução nativa da geração).
**Achados visuais observáveis:** Nilo virou um homem humano, usando camisa azul e avental verde com nome escrito; Mara apresentou aparência mais lisa e caricata; o mercadinho de bairro virou ambiente varejista moderno com iluminação branca; eixo/enquadramento/layout foram alterados; nomes "Mara"/"Nilo" apareceram no vídeo. São falhas críticas de CHARACTER_LOCK, SET_LOCK e estilo, independentemente de áudio.
**Decisão de QA:** NÃO usar esse take, NÃO avançar para geração em lote.
**Hipótese, não confirmada:** referência foi interpretada como inspiração em vez de frame inicial; é necessário conferir o modo real de geração na conta. Isso não está provado apenas pelo arquivo MP4.
**Ação recomendada:** Google Flow > Vídeo > Frames > Adicionar frame inicial com a imagem original 01 (confirmar miniatura); Veo 3.1 Lite 9:16 x1; ação mínima, câmera literalmente imóvel, sem reestilização ou movimentação complexa de objeto. Testar cena 01 com única fala de Mara e verificar primeiros fotogramas antes de prosseguir. Repetição textual de locks não garante fidelidade.
**Referências oficiais:** https://support.google.com/flow/answer/16353334?hl=pt-BR e https://support.google.com/flow/answer/16352836?hl=pt-BR.
**Status:** falha documentada com evidência de vídeo do responsável; correção de modo/prompt ainda NÃO testada. O arquivo bruto permanece em armazenamento privado da conversa, não foi enviado ao repositório público.

## 9 — QC segundo teste: imagem evoluiu, abertura ainda REPROVADA (06/11/2026)
**Arquivo observado:** segundo MP4 do responsável, cerca de 7,93s, 512×910 no arquivo compartilhado (não assumir resolução nativa). Extraídos quadros distribuídos ao longo de 0,2–7,4 segundos e inspecionado o nível temporal do áudio.
**Visual observado:** Mara tomate, Nilo laranja (com avental azul) e Beto brócolis em mercadinho com balcão, caixa e maquete, luz de fim de tarde; nítida melhora de species/SET_LOCK em relação ao primeiro teste. Porém, todo clipe preserva o mesmo enquadramento frontal de Mara sobre o balcão, Nilo grande em primeiro plano de costas/perfil e Beto ao fundo; postura agressiva de Mara quase não evolui; miniatura permanece sem ação; não há novo plano/contraplano e a dramaturgia visual estagna. **Não confundir composição válida com tomada aprovada**.
**Áudio:** usuário relata fala inicial incompreensível, parecendo idioma estranho. Há energia vocal perceptível nos primeiros ~1s e novos segmentos ao longo do arquivo, mas NÃO foi executada transcrição confiável ou identificação formal de idioma; não declarar transcrição específica. Condição de reprovação: uma única palavra inventada, fala inaudível ou idioma inadequado.
**Causa parcial sob nosso controle:** a instrução anterior de câmera absolutamente imóvel + miniatura não moverem forçou pouca evolução dramática. A regra CORRIGIDA é preservar eixo, geometria, material e identidade, mas permitir acting e pequenas mudanças intencionais; quando se desejar corte real, gerar tomadas separadas e montar no CapCut.
**Imagem inicial/final:** o Veo 3.1 Lite suporta as duas. Somente aplicar ambos ao MESMO take e quase mesmo ângulo, com transformação física leve da pose/olhares. Frames de ângulos diferentes podem gerar interpolação/morphing; não usar quadro de close de Nilo como frame final de plano conjunto de Mara para tentar simular corte. Uma imagem-mestra por personagem e duas poses A/B de shots críticos podem ajudar; não gerar todas indiscriminadamente.
**Custo atualizado:** Veo 3.1 Lite custa 10 créditos por geração de 4, 6 OU 8 segundos (não-Ultra); otimizar créditos não equivale a exigir 8s em toda fala. Dois personagens falando num único clipe de 8s economizam gerações, mas podem trocar vozes/lábios e exigir regravação. Para qualidade, 01 Mara 4s + 02 Nilo 4–6s com cortes, se falas PT-BR forem preservadas. Teste de 8s com duas falas só depois de comprovar idioma e atuação.
**Recomendação operacional:** trabalhar com 2 imagens-mestras da AÇÃO quando necessário (A início, B fim mesma lente/eixo); 2 enquadramentos diferentes = 2 clips separados; montar duração final de 45s com planos aproveitáveis, vozes reutilizáveis (Omni Flash 1.2 > Elementos/vozes, se acessível) e legendas no CapCut. Se voz nativa continuar produzindo balbucio, trocar estratégia de áudio antes de gerar as 10 falas.
**Próximos testes propostos, não realizados:** (1) comparar cenas 01 e 02 originais em frame inicial; (2) para cena 01 gerar vídeo de 4s com Mara fala exata, zero sílabas anteriores; (3) se passar, gerar cena 02 de 4/6s no close de Nilo; (4) depois avaliar bloco de 8s com duas falas, apenas se houver confiabilidade de voz por locutor. Não há autorização para mudança de roteiro canônico.
Fontes: https://support.google.com/flow/answer/16353334?hl=pt-BR ; https://support.google.com/flow/answer/16352836?hl=pt-BR ; https://support.google.com/flow/answer/16526234?hl=pt-BR .
