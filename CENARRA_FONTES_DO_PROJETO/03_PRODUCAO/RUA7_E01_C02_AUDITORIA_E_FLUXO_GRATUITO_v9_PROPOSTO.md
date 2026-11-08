# O Segredo da Rua 7 — E01 / Cena 02 — Auditoria e fluxo gratuito v9

**Data:** 08/11/2026. **Decidido:** somente contas gratuitas na produção, R$ 0. **Observado:** cinco imagens, a imagem original do trio e três MP4 da Cena 02 revisados. **Proposto:** a montagem abaixo, com até uma nova geração para o bloco e alvo de 10 s. **Pendente:** teste do corte com as três vozes, prova de continuidade e aceite editorial.

## 1. Fontes e continuidade

A versão inicial deste trabalho usa a governança e os locks da branch `main` em `41eca6c`, os anexos de operação e pré-produção, os trechos recuperados da conversa anterior e os arquivos efetivamente recebidos. O histórico integral da conversa não estava disponível. O pacote v8 e seu PNG foram recuperados e conferidos, incluindo a igualdade do PNG avulso com o conteúdo do ZIP. O histórico v6–v8 permanece como registro de experiências.

**Nomear os arquivos de forma inequívoca:** `C02` é o bloco de diálogo a partir de 00:08 do roteiro escrito, com as três falas de Mara, Beto e Nilo. O quadro numerado 02 do storyboard ilustrado é o close anterior de Nilo (“Dez anos longe daqui…”). A versão escrita reserva 12 s para C02. O corte experimental abaixo tem 10 s, preservando as falas. Com esse corte, C02 ocupa 00:08–00:18 e as marcas seguintes são recalculadas no editor.

| Referência | Uso |
|---|---|
| `CENARRA_RUA7_REFERENCIA_ORIGINAL_TRIO_PARA_FLOW.png`, 941×1672 | Matriz visual do elenco e do enquadramento daquele plano. Mara à esquerda do balcão, Nilo à direita e Beto ao fundo junto do caixa. Hash SHA-256 `041740bc6928bccd5443ebcf9ccf8b346b831a482e90c5c3c4987d1e81ae9ff6`. A mídia original fica fora do GitHub público. |
| Storyboard ilustrado, 1536×1024 | Usar para dramaturgia, expressões e ritmo. As espécies e o figurino contradizem o elenco original: ali Mara é abacaxi, Nilo tomate e Beto banana. Não carregar a prancha em nenhum gerador. Seus timecodes não controlam C02. |
| `D9839FC6…` (interior, 864×1536) | Referência de set e possível insert da maquete: janela e luz à esquerda, balcão de madeira, caixa verde-petróleo, prateleiras, samambaia, alho e luminária. A posição exata dos objetos dentro de cada tomada vem do respectivo frame aprovado. Evitar cortar para um plano que pareça mover o caixa ou a maquete. |
| `1FAF3A3E…` (fachada) e `B6CDC6E7…` (praça) | Candidatas à biblioteca de exteriores sem a banca montada. Preservar fachada ocre, toldo listrado, buganvília e direção da luz. A placa vazia pode receber letreiro em pós, quando o exterior entrar. |
| `964FC9CB…` (banca em tamanho real) | Estado futuro ou plano de outro momento. Em E01, a banca anunciada para amanhã é representada pela maquete no balcão. Uma banca pronta diante da loja pode antecipar a virada temporal e gerar confusão. |

**Fichas para conferir lado a lado:** Mara, tomate vermelho, sépalas verdes, blazer vinho, saia grafite e joias douradas; Nilo, laranja robusto, uma folha verde, barba grisalha curta, camisa bege e avental azul-marinho, mãos laranja; Beto, brócolis esguio, copa verde, camisa cáqui, mãos verdes, sem avental. Fixar também olhos, silhueta, volume relativo, escala da maquete e posição do caixa. Uma nova imagem só entra como matriz de tomada depois de passar nessa comparação.

## 2. Auditoria dos três vídeos

Os três anexos têm 7,93 s, 512×910 e 30 fps, com trilha AAC. Houve análise de quadros de 0,5 em 0,5 s, do primeiro quadro em tamanho integral, das mudanças de plano e da presença e dinâmica do áudio. As falas, seus timbres e o lip-sync não foram validados por audição ou transcrição confiável. Quando citadas no QA anterior, trocas de locutor são relato histórico, não confirmação acústica nova. Metadados do arquivo não provam qual modelo, conta ou configuração de geração foi usado.

| Arquivo | O que se observa | Destino |
|---|---|---|
| `330437814_1794003256294327(1).mp4` | Plano contínuo sobre o lado do Nilo, Mara inclina-se contra ele, Beto observa do fundo e a maquete continua sobre o balcão. A luz e o ambiente são legíveis. Espécies e cores-base permanecem reconhecíveis; câmera, pose, expressão e silhuetas já diferem da matriz recuperada no primeiro quadro. O plano favorece Mara; Nilo está de costas/¾ e Beto fica pequeno. | Referência de atuação, tensão e bloqueio. Uso de trecho no episódio só após QA lado a lado com os planos adjacentes e áudio validado. Não alimentar novo vídeo com este MP4. |
| `Characters_arguing_in_grocery_store_1934c0a0(2).mp4` | No primeiro quadro há um humano atrás do caixa, no lugar visual do Beto, e um caixote em destaque onde a maquete deveria ancorar a disputa. Depois há close de Beto; no retorno ao grupo, por volta de 5 s, Beto e o humano coexistem. A escala e a relação entre caixa, balcão e banca mudam. | Reprovar. O erro de elenco começa no primeiro quadro e volta no desfecho. |
| `Characters_speaking_in_grocery_shop_9964e22a(1).mp4` | O primeiro quadro é o mais próximo do PNG-mestre. Por volta de 2,57 s muda o plano; a mão ligada ao braço de camisa bege do Nilo aparece verde no plano intermediário. Por volta de 5,17 s o enquadramento volta a mudar. A alteração de cor/anatomia ocorre apesar do bom começo. | Reprovar como sequência. O PNG original continua sendo a referência de imagem. |

O diagnóstico é de **continuidade durante a animação**, além de validação do quadro inicial. O plano v8 separava vozes, mas ainda pedia três mudanças de foco dramático, gestos de mãos e câmera ao gerador. Essas instruções aumentam o número de elementos em movimento simultâneo; a causa de cada erro individual não é verificável pelo MP4.

## 3. Fluxo de produção proposto

1. **Montagem de prova sem crédito.** Usar o PNG original e referências do set já validadas. Gravar/posicionar as três falas primeiro, cada uma na sua faixa, mesmo com voz-guia temporária. Montar 10 s no CapCut Free com cortes secos, recortes dos ouvintes e insert da maquete. Usar as bocas fora de quadro quando a imagem fixa sugere que o ouvinte está falando; se o rosto não funcionar, mudar o recorte ou voltar ao insert. Um deslocamento sutil de enquadramento é suficiente para os inserts. Verificar ritmo e interlocutores antes de abrir o gerador. A versão pode servir de animático e referência para montagem.
2. **Escolher o único movimento que falta.** Para C02, a sugestão é a reação de Beto: o sorrisinho oportunista desaparece quando recebe a bronca. Preservar a direção do olhar e o eixo existentes. Se houver quadro isolado consistente, ele pode substituir a matriz do trio nesse plano após QA; na ausência dele, o PNG do trio é a entrada. Na imagem do trio, limitar o movimento aos olhos/sobrancelhas de Beto. O editor escolhe os melhores segundos e resolve a troca de foco com corte, som e enquadramento.
3. **Uma tentativa, depois revisão.** Se a montagem mostrar necessidade de animação, usar Flow web, `Frames para vídeo → Primeiro frame`, um PNG, 9:16, 1 saída e `Retornar vídeos sem áudio` nas configurações do projeto. Se a geração em si precisar de 10 s, usar Omni Flash 1.2 em 720p (30 créditos de referência) e só confirmar com o custo visível na conta gratuita. 360p custa 10 créditos e serve para prova de movimento, com limite de detalhe; não planejar gastar de novo automaticamente para reproduzir o mesmo resultado em 720p. Se os 10 s forem a duração da montagem e bastarem 4/6/8 s de movimento, Veo 3.1 Lite 720p custa 10 créditos por saída. Nada de modo texto, storyboard em colagem, cartões de voz, transição entre ângulos, saída dupla ou extensão. Não reenviar o mesmo teste reprovado no mesmo dia.
4. **Conferência em três passagens.** Sem som, comparar quadro inicial, intermediário, final e pontos de transição com a matriz; observar em velocidade normal e inspecionar mãos, bocas, folhas, roupas, caixa, maquete e direção de luz. Com a imagem oculta, confirmar português brasileiro, timbres fixos, palavras e pausas. Com ambos, confirmar quem fala, quem ouve e para onde olha. Reprovar humano, mudança de identidade, boca concorrente evidente, mão de cor errada, objeto duplicado ou corte que quebre o eixo. Se falhar, voltar ao animático e corrigir a entrada/ação; manter a cena bloqueada para publicação até passar. Registrar modelo, plano, quadro de entrada, duração, custo, segundos úteis e motivo da decisão.
5. **Escalar depois de duas tomadas consistentes** do mesmo personagem no mesmo set, já incluindo comparação com a cena vizinha. Reservar movimento generativo para gancho, ações que mudam a história e revelação final. Reusar ambiente, maquete, close de escuta e faixas de som por episódio. Para planejar o piloto, quatro a seis tomadas Lite somam 40–60 créditos se aprovadas na primeira saída; distribuir por dias conforme saldo e medir os segundos realmente usados. A meta operacional segue dois vídeos por semana em lote, sem converter quota diária em meta de consumo.

### Decupagem de C02 — 10 s de montagem

| Relógio de C02 | Áudio | Imagem e atuação |
|---|---|---|
| 0,00–2,55 | **Mara, para Nilo:** “Você não é dono da praça.” | Firme, baixa, final descendente. Ancorar Mara no quadro; sustentar o restante da frase no Nilo recebendo a afronta ou na maquete. |
| 2,55–3,05 | Pausa curta | Nilo absorve. Corte para Beto percebendo a oportunidade; deixar o humor nascer da pausa. |
| 3,05–5,15 | **Beto, para Mara:** “Tem vaga nessa banca?” | Pergunta espontânea, sem voz infantil. Identificar Beto no corte anterior; mostrar Mara ouvindo ou a maquete se a boca dele não estiver sincronizada. |
| 5,15–5,65 | Pausa curta | Nilo percebe que o funcionário está falando sério. A mudança de atenção precede a bronca. |
| 5,65–8,35 | **Nilo, para Beto:** “Beto! Você trabalha pra mim!” | O nome sai como susto, o resto como orgulho ferido. Mostrar Beto ouvindo com boca fechada, sorriso sumindo. |
| 8,35–10,00 | Silêncio | Segurar o constrangimento de Beto e cortar no olhar de Mara, se o quadro passar no lock. |

Janelas são guia. Ajustar pausas ao áudio real e preservar as palavras. Não acelerar a voz para encaixar. Gravar vozes PT-BR autorizadas, ou manter uma voz gratuita por personagem após conferir licença e disponibilidade da voz específica. Guardar cada voz separada e manter uma nota de direção de timbre, volume e cadência. Na passagem para o bloco seguinte, Beto recupera a coragem para falar de hora extra. No final do episódio, voltar à vulnerabilidade de Mara em “Não. Era pra gente ter aberto juntos.”, com reação silenciosa do Nilo. Sem fechar a disputa com uma piada ou com a banca já montada.

### Prompt de teste — reação única, condicionado ao quadro de entrada

```text
Animate the uploaded first frame as one locked-off vertical shot in the same warm-lit grocery store. Keep the same three characters, face shapes, skin and hand colors, outfits, positions and scale. Behind the teal register, Beto, the broccoli in khaki, starts with the faint smile in the reference. His eyes shift subtly toward Nilo on the right and his smile fades into a brief, embarrassed look. Keep his head and hands in place. Mara and Nilo hold their positions. The counter, register, striped miniature stall and light stay fixed. Restrained silent acting. No added characters, gesture, dialogue, camera move, cut or transition.
```

O prompt parte da expressão já presente na matriz. Se o quadro disponível mostrar outra expressão ou posição, atualizar a ação para partir da pose real antes de gerar.

## 4. Ferramentas gratuitas e limites checados

| Ferramenta | Aplicação e limite |
|---|---|
| **Google Flow Free** | Motor principal proposto. Brasil consta como região suportada. A ajuda atual informa 50 créditos diários sem acúmulo, renovação acionada pela primeira geração e possível indisponibilidade para não assinantes no pico de 11h–14h de Brasília. Veo 3.1 Lite: 4/6/8 s em 720p por 10 créditos. Omni Flash 1.2: 3–10 s na modalidade Frames pelo navegador; 1 crédito/s em 360p e 3 créditos/s em 720p. Extensão e upscale oficial dependem de plano elegível. Preço e saída devem ser confirmados na interface da conta gratuita antes de enviar. O Google distingue falha técnica, com devolução em até uma hora, de uma saída entregue com defeito criativo, para a qual não há reembolso presumido. |
| **Grok Imagine Free** | Reserva de teste se a função estiver liberada sem assinatura. A página de preços lista uso gratuito limitado e não documenta uma cota de vídeo gratuita utilizável para planejar a série. Consultar a própria conta para saber se a ferramenta de imagem para vídeo está liberada, qual duração/resolução aparece e qual o limite. A documentação do consumidor descreve marca visível sem ajuste para removê-la e queda de 720p para 480p quando o limite da faixa é atingido. Não planejar a série a partir de um número fixo de vídeos gratuitos ou dos limites/preços da API. |
| **CapCut Free** | Montagem, cortes e gravações próprias, sem crédito de vídeo generativo. Preferir projeto próprio com mídia, vozes e ambiente originais. Usar funções básicas disponíveis na conta gratuita; conferir exportação limpa antes de montar em lote. A licença padrão de “Commercial Sounds” do CapCut não libera automaticamente o mesmo áudio nas quatro redes. |
| **Meta Vibes / Runway Free / Luma Free** | Vibes anuncia animação a partir de imagem e recursos de voz; cota, exportação, acesso efetivo no Brasil e licença do fluxo precisam de verificação antes de virar rotina. Runway Free informa 125 créditos uma única vez e marca visível; é teste pontual. Luma restringe o plano gratuito a uso pessoal, fora do fluxo comercial da Cenarra. |
| **Produção local** | Wan2.2 tem pesos abertos e licença Apache 2.0 no modelo citado, mas o setup e o hardware têm custo operacional e a geração ainda pode deformar personagens. Blender permite reutilizar o mesmo modelo e rig sem créditos de geração; é opção de infraestrutura de longo prazo, com trabalho inicial de modelagem e animação. Não é pré-requisito para o piloto. |

**Direitos e publicação:** a FAQ do Flow remete aos termos completos e o Google declara que não reivindica propriedade sobre conteúdo original gerado. O Flow adiciona SynthID e documenta configuração de marca visível, com regras regionais. Conferir o arquivo exportado e os termos aplicáveis ao plano e a cada insumo, especialmente a voz, antes de usar comercialmente. Registrar direitos e rotulagem IA para as quatro redes. Música pode ser omitida. Este documento verifica documentação pública, não valida os recursos ou licenças concretos da conta do responsável.

### Fontes oficiais consultadas

- [Créditos do Flow](https://support.google.com/flow/answer/16526234?hl=en), [modelos e funções](https://support.google.com/flow/answer/16352836?hl=en), [Frames para vídeo](https://support.google.com/flow/answer/16353334?hl=en), [países e idiomas](https://support.google.com/flow/answer/16353544?hl=pt-BR), [áudio, marcas e uso](https://support.google.com/flow/answer/16353333?hl=en), [termos do Google](https://policies.google.com/terms).
- [Planos Grok](https://x.ai/pricing), [FAQ do consumidor](https://docs.x.ai/grok/faq), [termos do consumidor](https://x.ai/legal/terms-of-service).
- [CapCut: licença de materiais](https://www.capcut.com/clause/material-license-agreement), [quadros-chave](https://www.capcut.com/resource/how-to-add-keyframes-in-capcut).
- [Meta Vibes](https://ai.meta.com/vibes), [Runway Free](https://help.runwayml.com/hc/en-us/articles/50404627334547-Free-plan-details), [Luma: licença](https://lumalabs.ai/learning-hub/licensing), [Wan2.2](https://github.com/Wan-Video/Wan2.2), [Blender: licença](https://www.blender.org/about/license/).
