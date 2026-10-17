# Roteiro do Integrante 4: Andon (AP2 de PCP II)

Disciplina: Planejamento e Controle da Produção II (prof. Albertin)
Tema: Andon (serviço e indústria)
Data da apresentação: 20/10/2026
Grupo: Sophia, Jaqueline, Tereza e Kellyson
Papel: integrante 4 (simulador, explicação, pergunta final e fechamento)

## Critérios da AP2

- Slides 1 a 6, nesta ordem: origem, objetivo, descrição, relação com princípios e ferramentas do STP, relação com critérios de desempenho, diagrama visual.
- Depois: casos de aplicação (mínimo 1 por integrante) e uma aplicação prática em sala.
- Entrega dos slides com 24h de antecedência (WhatsApp e Sigaa): até 19/10.
- Individual: postura e horário (1), prova oral (3).
- Grupo: conteúdo e estrutura (2), prazo (1), criatividade (3).
- Foco na aplicação. Sem estudo de caso, sem teoria longa, sem ler slide.

## Papéis na prática

| Integrante | Função |
|---|---|
| 1 | Operador da montagem |
| 2 | Operador da inspeção e apoio à dinâmica |
| 3 | Responsável pela Logística |
| 4 | Controla o simulador e explica o processo |

## Antes de apresentar

Dia anterior:

1. Envie os slides até 19/10, no WhatsApp e no Sigaa.
2. Teste o simulador no computador da apresentação, no Chrome ou Edge.
3. Ensaie a prática completa 2 vezes, com cronômetro.

Na sala, antes de começar:

1. Abra o simulador em uma aba separada.
2. Clique em "Reiniciar demonstração". Os contadores ficam em 0.
3. Teste o som. Clique em "Som: ligado" e confira o volume.
4. Preencha o formulário uma vez para testar. Depois reinicie de novo.
5. Deixe o formulário preenchido com os dados da prática, sem enviar.
6. Monte a mesa: poucas folhas para o operador, folhas extras escondidas com o integrante 3.
7. Não recarregue a página. Isso apaga os chamados.

Dados do formulário:

| Campo | Valor |
|---|---|
| Máquina / área | Posto de montagem P-03 |
| Tipo de ocorrência | Falta de material |
| Prioridade | Alta |
| Responsável chamado | Logística |
| Descrição | Falta de papel na estação de montagem. Produção parada. |

## Bloco 1: exemplo de aplicação (cerca de 1 min)

Cada integrante apresenta um exemplo. Combine com o grupo para não repetir. Garanta exemplos de serviço e de indústria.

Opção de serviço:

> "Meu exemplo é em serviços. Pense em uma central de atendimento. O atendente recebe um cliente com um problema urgente. Ele aciona um alerta no sistema. O supervisor vê o alerta na hora e vai ajudar. O problema é resolvido sem o cliente esperar. Depois, o chamado fica registrado. A equipe vê quais problemas se repetem. É o mesmo princípio do Andon na fábrica: sinalizar, chamar ajuda e registrar."

Opção de indústria:

> "Meu exemplo é na indústria. O operador percebe uma peça fora do padrão. Ele aciona o Andon. A qualidade vem verificar antes de o lote continuar. Isso evita que o defeito avance para a próxima etapa."

## Bloco 2: abertura da prática (30 a 40 s)

Ação: vá até o computador. Mostre a tela do simulador à turma.

> "Agora vamos ver o Andon funcionando. Vamos simular uma linha de montagem. O produto é um triângulo de papel. Eu criei este simulador. Ele tem três partes."
>
> "A primeira é o HTML. Ele cria a estrutura: os campos, os botões, o painel de chamados, a torre de sinalização e o histórico."
>
> "A segunda é o CSS. Ele cuida da aparência: as cores, os painéis, as luzes e a adaptação à tela."
>
> "A terceira é o JavaScript. Ele faz funcionar: abre os chamados, muda os status, atualiza as luzes, conta as ocorrências e registra o histórico."
>
> "Atenção: o simulador é didático. Ele registra os chamados. A reposição do papel e a produção serão feitas por nós, aqui na mesa."
>
> "O integrante 1 é o operador da montagem. O integrante 2 faz a inspeção. O integrante 3 é a Logística. Eu cuido do simulador."

Aponte para a torre de sinalização:

> "A luz está verde. A produção está normal."

## Bloco 3: dinâmica passo a passo

### Etapa 1: início da produção (1 min)

Ação dos outros:

- O integrante 1 dobra os triângulos.
- O integrante 2 confere se estão perfeitos.

Sua fala:

> "Nossa linha está funcionando normalmente. O operador monta. A inspeção confere. Até que ocorre uma situação que impede a continuidade da produção."

Sua ação: fique ao lado do computador. Não clique em nada.

### Etapa 2: identificação do problema (1 min)

Ação dos outros: o papel acaba. O integrante 1 para de dobrar e levanta a mão.

Fala do integrante 1:

> "Atenção! Estamos sem papel na estação de montagem. Não consigo continuar a produção."

Sua fala:

> "O operador parou a linha. Ele não pode resolver sozinho. Ele precisa chamar quem abastece. Como ele faz isso? Aqui entra o Andon."

### Etapa 3: acionamento do Andon (1 min)

Sua ação:

1. Mostre à turma os campos já preenchidos.
2. Leia em voz alta: "Posto de montagem P-03. Falta de material. Prioridade alta. Responsável: Logística."
3. Leia a descrição: "Falta de papel na estação de montagem. Produção parada."
4. Clique em "Enviar chamado".

O que acontece: o som toca, a luz vermelha acende, o contador de abertos vai a 1 e o chamado aparece no painel.

Sua fala:

> "O chamado foi enviado. A luz ficou vermelha. Isso significa ocorrência aberta. O som avisa quem está por perto. O chamado foi direto para a Logística, que é o setor responsável. O painel mostra o chamado aberto e o histórico registrou a ocorrência."

Aponte para a luz, para o contador e para o painel.

Observação: o botão "Acionar Andon" só leva ao formulário. Ele não abre chamado. Use "Enviar chamado".

### Etapa 4: atendimento do chamado (1 a 2 min)

Ação do integrante 3: ele vem até o computador e clica em "Assumir chamado".

O que acontece: o status muda para "Em atendimento" e a luz fica amarela.

Sua fala, durante o clique:

> "A Logística recebeu o chamado. Ela assumiu o atendimento. A luz ficou amarela. Isso significa equipe em atendimento."

Ação do integrante 3: ele pega o papel extra e leva até o operador.

Fala do integrante 3:

> "Recebemos o chamado, identificamos a falta de material e realizamos a reposição para que a produção possa continuar."

### Etapa 5: resolução e conclusão (1 min)

Ação dos outros: o integrante 1 retoma a montagem. O integrante 2 volta a inspecionar.

Ação do integrante 3: ele volta ao computador e clica em "Marcar resolvido".

O que acontece: a luz fica verde, o status muda para "Operação liberada" e o histórico mostra o tempo total da ocorrência.

Sua fala:

> "Com o problema resolvido, a produção foi retomada. A luz voltou ao verde. O histórico registrou quanto tempo levou, do chamado até a solução. Assim conseguimos acompanhar a ocorrência e a resposta do setor responsável."

Aponte para o histórico e leia o tempo registrado.

## Bloco 4: pergunta para a turma (cerca de 1 min)

Sua fala:

> "Agora uma pergunta para vocês. O que poderia acontecer se o operador não tivesse como sinalizar essa falta de material?"

Ação: espere. Conte até 5 em silêncio. Aceite 2 ou 3 respostas.

Complemente, se faltar algo:

> "Isso mesmo. Sem sinalização, o problema demora mais a ser percebido. O tempo de parada aumenta. Os produtos incompletos se acumulam. Tudo isso gera atraso."

## Bloco 5: fechamento (30 s)

> "Essa dinâmica mostrou que o Andon não resolve o problema sozinho. A função dele é sinalizar a ocorrência, facilitar a comunicação e direcionar o chamado para o setor certo. Dessa forma, a equipe age mais rápido e reduz o impacto na produção."
>
> "Para funcionar, a equipe precisa saber três coisas: quando acionar, quem deve responder e como registrar e resolver. Obrigado. Alguma pergunta?"

## Se algo der errado

- **O som não toca.** Continue. A luz e o painel mostram o alerta. Diga: "O alerta sonoro faz parte do sistema, mas o visual já mostra a ocorrência."
- **Você clicou errado.** Clique em "Reiniciar demonstração" e preencha de novo. Diga: "Vamos repetir o registro."
- **O papel não acabou na hora.** O operador diz a fala mesmo assim. Ele finge a falta.
- **A turma não responde.** Reformule: "Pensem na fábrica de vocês. Se ninguém avisa, quem fica sabendo?"
- **O integrante 3 esquece de clicar.** Você clica no lugar dele, sem pausa.

## Tempo total da sua parte

| Bloco | Tempo |
|---|---|
| Exemplo de aplicação | 1 min |
| Abertura da prática | 40 s |
| Etapas 1 a 5 | 5 a 6 min |
| Pergunta à turma | 1 min |
| Fechamento | 30 s |

A prática fica dentro dos 5 a 7 minutos. Se estourar, reduza a explicação de HTML, CSS e JavaScript para 15 segundos.

## Preparação para a prova oral (3 pontos)

| Pergunta | Resposta |
|---|---|
| O que é Andon? | Ferramenta de gestão visual que sinaliza anormalidades e chama ajuda. |
| Origem? | Sistema Toyota de Produção. Antecedente: o tear automático de Sakichi Toyoda, que parava quando o fio quebrava. |
| Para a linha? | Não necessariamente. Depende da regra do processo e da gravidade. |
| Resolve o problema? | Não. Torna visível e direciona. A equipe resolve. |
| Diferença para o Poka-Yoke? | Andon sinaliza. Poka-Yoke previne erro. |
| Relação com o Jidoka? | O Andon torna a anormalidade visível e permite agir. |
| Relação com o Kaizen? | Os chamados registrados mostram problemas que se repetem. |
| Critérios de desempenho? | Qualidade, velocidade, confiabilidade, custo e flexibilidade. |
| Por que registrar? | Medir o tempo de resposta, achar recorrências e melhorar. |
| O simulador é real? | Não. É um protótipo didático, sem ligação com máquinas. |
| Como você fez? | HTML para a estrutura, CSS para a aparência, JavaScript para o funcionamento. |
