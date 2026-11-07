# CENARRA — Cena 02 Rua 7 — prompt v5 por personagens cadastrados
**Data:** 07/11/2026  
**Status:** PROPOSTO / NÃO TESTADO NO FLOW.

## Contexto
O responsável confirmou o cadastro de @Mara, @Beto e @Nilo no Flow, conforme descrições individuais. Os testes anteriores de **Frames** confundiram o falante de Beto com Nilo, geraram mão verde em Nilo e mudaram cenário. Não reutilizar as três imagens de cenas completas nem forçar início/fim incompatíveis.

## Modo recomendado
- **Vídeo → Elementos/Ingredientes**, se disponível para o modelo escolhido; 9:16; 8 segundos; uma saída.
- Inserir `@Mara`, `@Beto`, `@Nilo` e selecionar as fichas **reais** do projeto no seletor de @ (não somente palavras literais).
- Sem imagens adicionais dos personagens, pois já há assets salvos. Caso exista uma imagem de **cenário vazio realmente aprovada** e o modo tenha vaga de referência, pode testá-la; não substituí-la por cenário redesenhado.
- Diferenciar referência individual de personagem de frame início/fim. Guia oficial: https://support.google.com/flow/answer/16353334?hl=pt-BR . Cadastro oficial: https://support.google.com/labs/answer/16935308?hl=pt-BR .

## Elenco e turnos canônicos
- **Mara**: tomate mulher vermelha blazer bordô, à esquerda, lado cliente; voz feminina. Para Nilo: `Você não é dono da praça.` ~0–2,15s.
- **Beto**: brócolis homem verde com mãos verdes, camisa cáqui SEM avental, centro-fundo junto ao caixa verde; voz masculina jovem. Para Mara: `Tem vaga nessa banca?` ~2,4–4,45s.
- **Nilo**: laranja homem de barba grisalha, camisa bege e avental azul-marinho, mãos LARANJA, à direita atrás do balcão; voz masculina madura. Para Beto: `Beto! Você trabalha pra mim!` ~4,75–7,75s.
- Pausas de silêncio 2,15–2,4 / 4,45–4,75 / 7,75–8,0. Somente falante move lábios. Beto tem plano exclusivo ao lado do caixa, com Mara/Nilo **fora de quadro** durante a fala; cenários e atores nunca mudam de posição física.
- Sem música/efeitos durante geração, adicionar no CapCut após teste de voz.
- Preservar janela esquerda, samambaia central, alho, prateleiras de madeira, caixa retrô verde-água atrás do balcão, mini banca listrada no mesmo lugar; não reconstruir set.

## QA
Reprovar se Beto não fala sua linha, se Nilo recebe voz de Beto, se há sobreposição, mãos de Nilo esverdeadas, distorção de espécie/figurino, cenário reconstruído, falas extras ou sotaque/idioma errados. O uso de personagens e vozes cadastrados **não garante deterministicamente** três locutores em oito segundos. Após falha recorrente, priorizar vozes independentes na edição sobre re-prompt repetitivo.

**Artefato entregue** (mídia privada, não subir ao GitHub público): `CENARRA_RUA7_CENA02_FLOW_PERSONAGENS_CADASTRADOS_V5.txt` com prompt integral.

Nenhuma geração foi executada por este documento, e as vozes salvas não foram auditadas dentro da conta do Flow.
