# Produção, set lock e continuidade — SOP

## Pipeline
1. Premissa e Bíblia (status aprovado ou em teste).
2. Roteiro pela [ficha do método editorial](METODO_ROTEIRO_RETENCAO_E_CADENCIA.md): intriga clara para quem chega pelo feed, mudanças de cena, resolução no próprio capítulo e consequência que gera nova curiosidade. Conferir a promessa anterior, o primeiro quadro e os diálogos em voz alta antes do storyboard.
3. Storyboard com tomadas 4–8s como referência, conforme modelo disponível.
4. Imagens-mestras de personagens e set.
5. Geração de tomadas com `SET_LOCK` e `CHARACTER_LOCK`; registrar créditos e falhas.
6. Edição: áudio original/licenciado, legendas, ritmo e controle de montagem.
7. QA editorial, visual, direitos, licença comercial, público e IA disclosure.
8. Publicação nativa e dados por rede em 48h e sete dias.

## Continuidade
**Personagem:** silhueta, proporção, textura/casca/pelagem, olhos, roupa, voz, gestos e relação conhecida.

**Cenário:** posição fixa de portas, janelas, balcão, mesa, props, arquitetura, iluminação e ângulos autorizados.

**História:** objetos transferidos, segredos revelados, relações alteradas e fatos que permanecem verdadeiros no capítulo seguinte.

## Arquivos
Cada episódio: `roteiro.md`, `shotlist.csv`, `prompts.md`, `refs/`, `cenas/`, `audio/`, `master_sem_legenda.mp4`, `final_PTBR.mp4`, `qa.md`, `publicacoes.csv`.

## Orçamento e ferramentas
ChatGPT para roteiro/imagens; Google Flow para animação; CapCut para edição, quando disponíveis no plano. Custo incremental zero. Verificar limites e direitos comerciais atuais antes de usar. Pavo/Agnes são testes até prova de autorização adequada.

## Exportação
Preferência por vertical 9:16, MP4 H.264 e 1080×1920 se a fonte suportar. Não inventar qualidade que o gerador não entregou.

## YouTube Create — protocolo de consistência e correção (18/11/2026)

**Aplicação a todas as séries da Cenarra.** Complementa os locks e o método editorial vigentes, sem mudar cânone, estilo aprovado, roteiros ou pontos de retomada. Resultado da avaliação da análise externa fornecida pelo responsável e da conferência da [Ajuda oficial do YouTube Create](https://support.google.com/youtube/answer/16631240?hl=pt-BR) em 18/11/2026.

### Verificado e limites
- O modo Gerar vídeo com Gemini Omni permite até 10 s, 9:16 ou 16:9, até 900 caracteres, até três referências da galeria, instruções de áudio/fala e opções de luz. O Brasil está listado, mas o recurso é experimental e a disponibilidade pode variar. Usar **9:16, 10 s e até 899 caracteres** no fluxo Cenarra. A opção de animar imagem gerada no próprio app tem duração distinta (8 s); não confundir com Gerar vídeo. Duração de geração não é obrigação de usar o clipe inteiro no corte.
- Editar geração recupera o prompt e as imagens originais e permite nova geração; não garante edição localizada, identidade ou preservação do resultado. Salvar a versão boa antes de tentar e conferir a nova.
- A documentação aceita prompts de vídeo em todos os idiomas. Instruções técnicas em inglês + fala literal em PT-BR nativo são **opção em teste**, não regra comprovadamente superior. Comparar com português sem trocar o sentido, as referências ou a ação; a qualidade do resultado decide.
- Referências reduzem deriva, mas não garantem consistência. Não usar contas alternativas com finalidade de contornar cotas ou restrições; capacidade gratuita e licenças comerciais exigem verificação. [Termos do YouTube](https://www.youtube.com/t/terms) e [IA no YouTube](https://support.google.com/youtube/answer/14772770?hl=pt-BR).

### Antes de cada tomada
1. Consultar roteiro e recuperação do último quadro válido; definir estado inicial/final, intenção, gatilho, enquadramento e emoção. Usar uma ação dramática principal e um eixo por clipe; permitir reações e movimento de câmera simples compatíveis. Preferir um falante visível por clipe e planos/contraplanos quando necessário.
2. Selecionar até três imagens com funções distintas: (A) imagem-base **específica da tomada**, com composição, personagens, cenário e objetos corretos; (B) master aprovado do personagem cuja identidade precisa ser preservada; (C) último quadro válido para continuação direta, ou master de cenário/segundo personagem quando mais relevante. Se houver mudança de plano, tempo ou lugar, não forçar o quadro anterior. Não usar frame com defeito nem deixar uma referência de choro induzir lágrimas em tomada que requer rosto seco. Se só uma imagem bastar, não adicionar referências conflitantes. Ao gerar a imagem-base, consultar todos os locks vigentes, mesmo se a ferramenta de vídeo não aceitar todos simultaneamente.
3. Repetir identificadores visíveis essenciais de personagem/figurino e set; não alterar idade, pinta, joias, espécie, proporção nem aparência com palavras vagas. Descrever um estilo próprio de CGI 3D cinematográfico, não depender de marca de estúdio de terceiros. Manter visual aprovados e naturalidade seletiva de material, luz e atuação. Fotorrealismo só em teste separado autorizado.
4. Prompt em até 899 caracteres: referência + formato + plano; identidade e geografia visíveis; objeto e mão/posição; início imediato da ação; mudanças na atuação e reação final; fala literal PT-BR, intenção, quem fala/quem escuta; som e restrições críticas. Contar caracteres. Não exigir duas falas complexas, múltiplas ações manuais ou vários ângulos em dez segundos. Voz em off pode ser separada na edição.
5. Prever falhas antes de gastar geração. Ex.: um celular só, já na posição adequada quando a ação de pegar/tocar não for essencial; toque de chamada e conexão podem vir do áudio; mostrar estado do objeto antes/depois; mantê-lo fisicamente único. Para papéis e pistas, preservar frase exata e legível; se o texto distorcer, usar insert estático aprovado ou composição na edição, sem regenerar todo o take bom. Evitar pedir movimentos redundantes ou que não contribuem para o conflito.
6. QA do vídeo completo: identidade, número de objetos, mãos, boca única, somente quem fala mexe os lábios, sotaque/voz, direção do olhar, raccord, texto/pista, reação facial/corporal e som. Se falhar, ajustar apenas o problema em prompt/referência; guardar versão anterior; avaliar a nova do início ao fim. Aproveitar trechos ou corrigir por montagem quando seguros e mais simples. Não publicar falhas relevantes.

### Direção editorial (sem reiniciar histórias)
- O visual estilizado ajuda a manter uma identidade, mas não torna erros aceitáveis nem prova maior viralização. A prioridade é acontecimento concreto e compreensível desde o primeiro quadro, escalada real, emoção motivada, resposta dentro do capítulo e nova curiosidade que deriva da consequência. Gancho final precisa mudar a situação, não apenas anunciar uma conversa. Não terminar capítulos sistematicamente sem entregar o prometido. Aplicar o [método editorial](METODO_ROTEIRO_RETENCAO_E_CADENCIA.md); [YouTube sobre o gancho inicial em Shorts](https://blog.youtube/creator-and-artist-stories/youtube-shorts-deep-dive/).
- Rua 7: manter frutas/legumes e mercadinho aprovados; No Escritório: preservar animais e seus ambientes; A Última Ligação: manter adultos em 3D estilizado moderado e a continuidade vigente. Achados do Terminal segue o mesmo protocolo com o próprio lock. Não uniformizar gêneros, reações ou acabamento.
- **A Última Ligação — veto explícito do responsável em 18/11:** rejeitar a versão externa que transforma Clara em viúva de Rafael e introduz acidente de carro, passagem aérea ou ligação sobre morte de Rafael. Rafael é o vizinho de Clara na continuidade registrada; o mistério gira em torno da ligação relacionada a Helena, mãe de Clara. Preservar a [bíblia vigente](../02_SERIES/ULTIMA_LIGACAO/BIBLIA_DE_CONTINUIDADE.md), os roteiros existentes e o ponto de retomada. A solução do mistério continua conforme o estado de aprovação dos arquivos, sem canonizar hipóteses.
- Testar melhorias nos próximos takes necessários sem gerar versões extras só para pesquisa; medir retenção, conclusão, compartilhamentos e tentativas/tempo por clipe nas janelas já definidas. Sem promessa de viralização, mudança de grade ou aumento de custo.
