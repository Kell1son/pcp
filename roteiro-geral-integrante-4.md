# Roteiro geral: integrante 4 (Kellyson), Andon

AP2 de PCP II, prof. Albertin, 20/10/2026.
Arquivo dos slides: `apresentacao-andon.pptx` (as falas também estão nas notas do apresentador).

Minha função: apresentar um exemplo de aplicação, controlar o simulador, conduzir a prática, fazer a pergunta para a turma e fechar a apresentação.

## Visão rápida

A prática agora tem **dois cenários** com a mesma situação (as folhas acabam): primeiro **sem Andon**, depois **com Andon**. Cada cenário usa 5 folhas. As folhas representam a matéria-prima: não importa quantas sejam, uma hora elas acabam.

| Momento | Slide | Tempo | O que eu faço |
|---|---|---|---|
| Exemplo de aplicação | 9 | 1 min | Conto o caso do erro na separação do pedido (logística) |
| Abertura da prática | 10 | 1 min | Explico a ideia dos dois cenários, os papéis e o simulador |
| Cenário 1: sem Andon | 10 (sem clicar) | 1 min 30 s | Cronometro a parada e mostro o simulador zerado |
| Cenário 2: com Andon | 11 + simulador | 2 min 30 s | Narro as etapas e clico em "Enviar chamado" |
| Comparação e pergunta | 12 | 1 min 30 s | Comparo os dois tempos e pergunto para a turma |
| Fechamento | 13 | 30 s | Resumo e agradeço |
| **Total** | | **cerca de 8 min 30 s** | |

Se o tempo apertar: resumir HTML, CSS e JavaScript em 15 segundos e limitar a parada do cenário 1 a 20 segundos.

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
- [ ] Mesa montada: **5 folhas** com o operador para o cenário 1 e **mais 5 folhas** guardadas com o integrante 3 (servem de reposição no cenário 1 e de novo estoque no cenário 2)
- [ ] Cronômetro do celular pronto (para o cenário 1)
- [ ] Combinado com o grupo: no cenário 1, o integrante 3 fica ocupado, longe da mesa, e só vem quando o integrante 2 ou o operador o avisarem. Parada máxima de 30 s.
- [ ] Simulador: **não clicar em nada durante o cenário 1**

## 1. Exemplo de aplicação: erro na separação do pedido (slide 9, 1 min)

Área: logística. No slide 8 é o cartão "Logística: separação".

> "Meu exemplo é na logística, em um centro de distribuição. O colaborador está separando um pedido e percebe um item trocado ou faltando. Em vez de seguir, ele aciona o Andon. A liderança vem até o posto e confere o pedido antes da expedição. O erro é corrigido ali, e não na casa do cliente. Isso evita devolução, reenvio e custo extra. Como o chamado fica registrado, a equipe descobre onde os erros se repetem, por exemplo produtos parecidos guardados lado a lado. É o mesmo princípio do Andon: sinalizar, chamar ajuda e corrigir antes de o problema avançar."

Apontar no slide, da esquerda para a direita: colaborador (vermelho, aciona), liderança (amarelo, confere), expedição (verde, pedido correto) e registro (melhoria).

Ponte para a prática: "Na nossa prática, a Logística também vai ser chamada pelo Andon, só que para repor material."

Se perguntarem:

| Pergunta | Resposta |
|---|---|
| Por que não corrigir sozinho? | O colaborador pode não ter acesso ao estoque ou autorização. E o registro se perde. |
| Qual critério de desempenho melhora? | Qualidade (pedido certo) e confiabilidade (entrega certa, no prazo). Também custo, com menos devolução. |
| Onde entra o Kaizen? | Os chamados mostram onde os erros se repetem, e a equipe ataca a causa. |

## 2. Abertura da prática (slide 10, 1 min)

Vou até o computador.

> "Agora vamos ver o Andon funcionando. Vamos simular uma linha de montagem. O produto é um triângulo de papel, e a folha é a nossa matéria-prima. Não importa quantas folhas o operador tenha: uma hora elas vão acabar."
>
> "Vamos fazer dois cenários com a mesma situação. No primeiro, a folha acaba e a equipe não tem o Andon. No segundo, a folha acaba e a equipe usa o Andon. Em cada um, o operador começa com 5 folhas. No fim, comparamos."
>
> "Eu criei este simulador. O HTML cria a estrutura: campos, botões, painel, torre e histórico. O CSS cuida da aparência: cores e luzes. O JavaScript faz funcionar: abre os chamados, muda os status, atualiza as luzes e registra o histórico. Ele é didático: só registra os chamados. A reposição do papel e a produção são feitas por nós, aqui na mesa."
>
> "O integrante 1 é o operador. O integrante 2 faz a inspeção. O integrante 3 é a Logística. Eu cuido do simulador e do tempo."

Mostro a tela e aponto a torre:

> "A luz está verde e os contadores estão em zero. Vamos começar pelo cenário sem Andon."

## 3. Cenário 1: sem Andon (1 min 30 s)

Regra: o simulador fica como está. Não clico em nada.

| Etapa | Quem age | Eu falo |
|---|---|---|
| 1. Produção | Int. 1 dobra os triângulos com as 5 folhas. Int. 2 confere. Int. 3 está ocupado, afastado da mesa. | "Cenário 1, sem Andon. A linha trabalha normalmente. O operador monta, a inspeção confere." |
| 2. Folhas acabam | Int. 1 para e diz: "Acabou o papel." Sem ferramenta, ele só pode esperar ou procurar alguém. | "Acabou o papel. **Disparo o cronômetro.** O operador não tem como avisar quem abastece. A luz do simulador continua verde e nada está registrado." (aponto a tela) |
| 3. Alguém percebe | Int. 2 nota que não chegam triângulos e vai avisar o Int. 3 (ou o operador sai do posto para procurá-lo). Limite: 30 s. | "Repare: a linha está parada e quem abastece ainda não sabe. A informação anda de boca em boca, no tempo de cada um." |
| 4. Reposição | Int. 3 traz o papel. Int. 1 retoma a montagem. | "Papel chegou. **Paro o cronômetro.**" |

Fecho o cenário:

> "A linha ficou parada **X segundos**. Quem abasteceu só soube porque alguém foi avisar. E o simulador continua zerado: nenhum registro, nenhuma informação para melhorar depois."

Anoto o tempo (X) para comparar. Em seguida o grupo se prepara para o cenário 2: o operador pega mais 5 folhas, o Int. 3 volta para o posto da Logística e eu confiro se o formulário continua preenchido.

## 4. Cenário 2: com Andon (slide 11 como apoio, 2 min 30 s)

> "Cenário 2, com Andon. Mesma situação, agora com a ferramenta."

| Etapa | Quem age | Eu falo | Luz |
|---|---|---|---|
| 1. Produção | Int. 1 dobra com as 5 folhas novas, Int. 2 confere. Eu não clico. | "A linha trabalha normalmente. A luz está verde." | Verde |
| 2. Folhas acabam | Int. 1 levanta a mão: "Atenção! Estamos sem papel na estação de montagem. Não consigo continuar a produção." | "O operador parou a linha. Ele não resolve sozinho. Precisa chamar quem abastece. Aqui entra o Andon." | Verde |
| 3. Acionamento | **Eu** leio os campos e clico em **"Enviar chamado"** (**disparo o cronômetro** junto com o clique) | "Posto de montagem P-03. Falta de material. Prioridade alta. Responsável: Logística. Descrição: falta de papel na estação de montagem, produção parada." Depois do clique: "A luz ficou vermelha: ocorrência aberta. O som avisa quem está por perto. O chamado foi **direto** para a Logística. O painel mostra o chamado e o histórico registrou." | Vermelha |
| 4. Atendimento | Int. 3 clica em **"Assumir chamado"** e leva o papel. Fala: "Recebemos o chamado, identificamos a falta de material e realizamos a reposição para que a produção possa continuar." | "A Logística assumiu. A luz ficou amarela: equipe em atendimento." | Amarela |
| 5. Resolução | Int. 1 retoma a montagem. Int. 2 volta a inspecionar. Int. 3 clica em **"Marcar resolvido"**. | "A produção foi retomada. A luz voltou ao verde. O histórico registrou quanto tempo levou, do chamado até a solução." (leio o tempo do simulador) | Verde |

Atenção: "Acionar Andon" só abre o formulário. O chamado só é aberto em **"Enviar chamado"**.

## 5. Comparação e pergunta para a turma (slide 12, 1 min 30 s)

Comparo os dois cenários (se der, mostro os números nos dedos ou digo em voz alta):

> "No cenário 1, a linha ficou parada X segundos, quem abastece só soube por aviso, e não ficou nenhum registro. No cenário 2, o tempo foi Y segundos, o chamado foi direto para a Logística, e o histórico guardou a ocorrência."

Pergunta:

> "Pensando nos dois cenários: o que mudou, e o que aconteceria se isso se repetisse todo dia em uma fábrica de verdade?"

Conto até 5 em silêncio. Aceito 2 ou 3 respostas. Se ninguém responder: "Pensem na fábrica de vocês. Se ninguém avisa, quem fica sabendo?"

Complemento:

> "Isso mesmo. Sem sinalização, o problema demora mais a ser percebido, o tempo de parada aumenta e os produtos incompletos se acumulam. Com o Andon, a informação vai direto ao responsável e fica registrada. Isso gera atraso a menos e dados para melhorar."

Se os tempos ficarem parecidos (por exemplo, o grupo estava perto da mesa):

> "Aqui a mesa é pequena e a Logística estava a um passo. Em uma fábrica grande, a distância e o número de pessoas fazem a diferença crescer. O ganho do Andon é a **velocidade, o destino certo do chamado e o registro**."

## 6. Fechamento (slide 13, 30 s)

> "Os dois cenários mostraram que o Andon não resolve o problema sozinho. A função dele é sinalizar a ocorrência, facilitar a comunicação e direcionar o chamado para o setor certo. Assim a equipe age mais rápido e reduz o impacto na produção."
>
> "Para funcionar, a equipe precisa saber três coisas: quando acionar, quem deve responder e como registrar e resolver. Obrigado. Alguma pergunta?"

## Plano B

| Problema | O que fazer |
|---|---|
| Som não toca | Seguir. "O alerta sonoro faz parte do sistema, mas o visual já mostra a ocorrência." |
| Cliquei errado | "Reiniciar demonstração", preencher de novo. "Vamos repetir o registro." |
| Papel não acabou na hora | O operador finge a falta e diz a fala. |
| Tempos dos cenários ficaram parecidos | Usar a fala do bloco 5: na fábrica a distância e o número de pessoas aumentam a diferença. O ganho também está no destino certo e no registro. |
| Int. 3 reagiu rápido demais no cenário 1 | Seguir. "Aqui a Logística estava perto. Se estivesse em outro setor, ia demorar mais." |
| Cliquei no simulador por engano no cenário 1 | Dizer "Isso é o que o Andon faz: registra" e seguir. Reiniciar antes do cenário 2. |
| Turma não responde | Reformular a pergunta (ver bloco 5). |
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
| Por que dois cenários? | Para comparar a mesma falta de material sem e com a ferramenta: tempo de parada, quem fica sabendo e o que fica registrado. |
| O que as folhas representam? | A matéria-prima. Qualquer estoque acaba um dia, e o que importa é como a equipe reage. |
| O simulador é real? | Não. É um protótipo didático, sem ligação com máquinas. |
| Como você fez? | HTML para a estrutura, CSS para a aparência, JavaScript para o funcionamento. |
