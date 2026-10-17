# Roteiro geral: integrante 4 (Kellyson), Andon

AP2 de PCP II, prof. Albertin, 20/10/2026.
Arquivo dos slides: `apresentacao-andon.pptx` (as falas também estão nas notas do apresentador).

Minha função: apresentar um exemplo de aplicação, controlar o simulador, conduzir a prática, fazer a pergunta para a turma e fechar a apresentação.

## Visão rápida

| Momento | Slide | Tempo | O que eu faço |
|---|---|---|---|
| Exemplo de aplicação | 9 | 1 min | Conto o caso da central de atendimento |
| Abertura da prática | 10 | 40 s | Apresento papéis e o simulador (HTML, CSS, JS) |
| Dinâmica, etapas 1 a 5 | 11 + simulador | 5 a 6 min | Narro cada etapa e clico em "Enviar chamado" |
| Pergunta para a turma | 12 | 1 min | Pergunto, espero, complemento |
| Fechamento | 13 | 30 s | Resumo e agradeço |
| **Total** | | **cerca de 9 min** | |

Se o tempo apertar: resumir a parte de HTML, CSS e JavaScript em 15 segundos.

## Checklist

**Até 19/10:** slides enviados no WhatsApp e no Sigaa. Simulador testado no computador da apresentação (Chrome ou Edge). Prática ensaiada 2 vezes com cronômetro.

**Na sala, antes de começar:**

- [ ] Simulador aberto em outra aba, sem recarregar a página depois
- [ ] "Reiniciar demonstração" clicado (contadores em 0)
- [ ] Som testado ("Som: ligado")
- [ ] Formulário testado uma vez e reiniciado
- [ ] Formulário preenchido, sem enviar:
  - Máquina / área: **Posto de montagem P-03**
  - Tipo: **Falta de material**
  - Prioridade: **Alta**
  - Responsável: **Logística**
  - Descrição: **Falta de papel na estação de montagem. Produção parada.**
- [ ] Mesa montada: poucas folhas com o operador, folhas extras escondidas com o integrante 3

## 1. Exemplo de aplicação (slide 9, 1 min)

> "Meu exemplo é em serviços. Pense em uma central de atendimento. O atendente recebe um cliente com um problema urgente. Ele aciona um alerta no sistema. O supervisor vê o alerta na hora e vai ajudar. O problema é resolvido sem o cliente esperar. Depois, o chamado fica registrado. A equipe vê quais problemas se repetem. É o mesmo princípio do Andon na fábrica: sinalizar, chamar ajuda e registrar."

Se outro integrante já tiver usado serviço, troco pelo exemplo de indústria:

> "O operador percebe uma peça fora do padrão. Ele aciona o Andon. A qualidade vem verificar antes de o lote continuar. Isso evita que o defeito avance para a próxima etapa."

## 2. Abertura da prática (slide 10, 40 s)

Vou até o computador.

> "Agora vamos ver o Andon funcionando. Vamos simular uma linha de montagem. O produto é um triângulo de papel. Eu criei este simulador. Ele tem três partes: o HTML cria a estrutura, com campos, botões, painel, torre e histórico. O CSS cuida da aparência: cores, painéis e luzes. O JavaScript faz funcionar: abre os chamados, muda os status, atualiza as luzes e registra o histórico."
>
> "O simulador é didático. Ele registra os chamados. A reposição do papel e a produção serão feitas por nós, aqui na mesa."
>
> "O integrante 1 é o operador. O integrante 2 faz a inspeção. O integrante 3 é a Logística. Eu cuido do simulador."

Troco para a aba do simulador e aponto a torre:

> "A luz está verde. A produção está normal."

## 3. Dinâmica (slide 11 como apoio, tela no simulador, 5 a 6 min)

| Etapa | Quem age | Eu falo | Luz |
|---|---|---|---|
| 1. Produção | Int. 1 dobra, Int. 2 confere. Eu não clico. | "Nossa linha está funcionando normalmente. O operador monta. A inspeção confere. Até que ocorre uma situação que impede a produção." | Verde |
| 2. Problema | Papel acaba. Int. 1 levanta a mão: "Atenção! Estamos sem papel na estação de montagem. Não consigo continuar a produção." | "O operador parou a linha. Ele não pode resolver sozinho. Precisa chamar quem abastece. Como ele faz isso? Aqui entra o Andon." | Verde |
| 3. Acionamento | **Eu** leio os campos em voz alta e clico em **"Enviar chamado"** | "O chamado foi enviado. A luz ficou vermelha: ocorrência aberta. O som avisa quem está por perto. O chamado foi direto para a Logística. O painel mostra o chamado aberto e o histórico registrou a ocorrência." (aponto luz, contador e painel) | Vermelha |
| 4. Atendimento | Int. 3 clica em **"Assumir chamado"** e leva o papel. Fala: "Recebemos o chamado, identificamos a falta de material e realizamos a reposição para que a produção possa continuar." | "A Logística recebeu o chamado e assumiu o atendimento. A luz ficou amarela: equipe em atendimento." | Amarela |
| 5. Resolução | Int. 1 volta a montar, Int. 2 a inspecionar. Int. 3 clica em **"Marcar resolvido"**. | "Com o problema resolvido, a produção foi retomada. A luz voltou ao verde. O histórico registrou quanto tempo levou, do chamado até a solução." (leio o tempo) | Verde |

Atenção: "Acionar Andon" só abre o formulário. O chamado só é aberto em **"Enviar chamado"**.

## 4. Pergunta para a turma (slide 12, 1 min)

> "O que poderia acontecer se o operador não tivesse como sinalizar essa falta de material?"

Conto até 5 em silêncio. Aceito 2 ou 3 respostas. Se ninguém responder: "Pensem na fábrica de vocês. Se ninguém avisa, quem fica sabendo?"

Complemento:

> "Isso mesmo. Sem sinalização, o problema demora mais a ser percebido. O tempo de parada aumenta. Os produtos incompletos se acumulam. Tudo isso gera atraso."

## 5. Fechamento (slide 13, 30 s)

> "Essa dinâmica mostrou que o Andon não resolve o problema sozinho. A função dele é sinalizar a ocorrência, facilitar a comunicação e direcionar o chamado para o setor certo. Assim a equipe age mais rápido e reduz o impacto na produção."
>
> "Para funcionar, a equipe precisa saber três coisas: quando acionar, quem deve responder e como registrar e resolver. Obrigado. Alguma pergunta?"

## Plano B

| Problema | O que fazer |
|---|---|
| Som não toca | Seguir. "O alerta sonoro faz parte do sistema, mas o visual já mostra a ocorrência." |
| Cliquei errado | "Reiniciar demonstração", preencher de novo. "Vamos repetir o registro." |
| Papel não acabou na hora | O operador finge a falta e diz a fala. |
| Turma não responde | Reformular a pergunta (ver bloco 4). |
| Int. 3 esquece de clicar | Eu clico no lugar dele, sem pausa. |

## Prova oral: respostas curtas

| Pergunta | Resposta |
|---|---|
| O que é Andon? | Ferramenta de gestão visual que sinaliza anormalidades e chama ajuda. |
| Origem? | Sistema Toyota de Produção. Antecedente: tear automático de Sakichi Toyoda, que parava quando o fio quebrava. |
| Sempre para a linha? | Não. Depende da regra do processo e da gravidade. |
| Resolve o problema? | Não. Torna visível e direciona. A equipe resolve. |
| Diferença para Poka-Yoke? | Andon sinaliza. Poka-Yoke previne o erro. |
| Relação com Jidoka? | O Andon torna a anormalidade visível e permite agir. |
| Relação com Kaizen? | Os chamados registrados mostram problemas que se repetem. |
| Critérios de desempenho? | Qualidade, velocidade, confiabilidade, custo e flexibilidade. |
| Por que registrar? | Medir o tempo de resposta, achar recorrências e melhorar. |
| O simulador é real? | Não. É um protótipo didático, sem ligação com máquinas. |
| Como você fez? | HTML para a estrutura, CSS para a aparência, JavaScript para o funcionamento. |
