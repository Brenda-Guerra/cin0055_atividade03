# Ideias do projeto-experimento — NPCs generativos e mundos vivos

Oct 14, 2026 · @Brenda Guerra

Três ideias de experimento para o tema 11, NPCs generativos e mundos vivos, no Movimento 3 de CIN0055 (Tendências em Mídia e Interação, 2026.2). Minha preferência é a ideia 1, um mod de The Sims 4. A ideia 2 é o plano B e usa a mesma arquitetura. Meu teste com a turma é em 05/11.

## 1. Como fiz o brainstorming

Saíram 6 ideias, em duas rodadas com IA. Delas, 3 foram selecionadas: uma passou intacta e duas nasceram da fusão de outras.

**Ponto de partida.** Usei o meu mapa de futuro do tema 11, o confronto com o mapa do professor e a conversa da aula. Também li o texto do futuro 06, "Sociedades simuladas: a simulação como instrumento de investigação". De lá saiu a pergunta-guia: o que dá para *investigar* com uma sociedade de NPCs generativos, e não só construir?

**Método.** Fiz o brainstorming em conversa com o Claude (Anthropic), em duas rodadas.

1. **Divergência.** Pedi ideias de experimento sobre o tema e uma estimativa de viabilidade de cada uma. Pedi também que uma delas fosse um mod de The Sims 4, um projeto pessoal que eu já queria fazer. As referências usadas foram *Generative Agents* (Park et al., 2023), *Project Sid* (Altera, 2024) e *AI Town* (a16z).
2. **Filtro contra o enunciado.** Reavaliei as 6 ideias com o enunciado do Movimento 3 e o documento de lições da disciplina. Depois reformulei as que sobreviveram.

**Critérios de seleção:**

- **Tecnologia emergente de verdade.** As lições da disciplina registram que "companheiro de nuvem com memória" já foi recusado como maduro. Um NPC que só lembra de você não basta. O emergente está em várias IAs formando uma sociedade, com memória, reflexão e planejamento, acopladas a um mundo com regras próprias.
- **Testável pela turma inteira.** São cerca de 30 pessoas ao mesmo tempo, por 25 minutos, sem eu conduzir.
- **Acessível fora da turma.** Link no ar ou repositório que instala em outra máquina.
- **Cabe no prazo.** Construção a partir de 13/10, teste em 05/11.

**As 6 ideias e o destino de cada uma:**

| Ideia | Destino |
| --- | --- |
| Mod de The Sims 4 com NPCs de memória e reflexão | Selecionada (ideia 1), reformulada: o mod gera os moradores da casa em volta do Sim do jogador |
| Vila 2D onde um boato se espalha entre agentes | Fundida na ideia 2 |
| Humanos convivendo com agentes num mesmo mundo | Fundida na ideia 2 |
| Reproduzir um experimento social clássico com agentes | Selecionada (ideia 3) |
| Simulação longa e "arqueologia" dos logs | Descartada: custo alto de tokens, e 25 minutos não mostram uma rodada longa |
| Um NPC e a deriva da sua personalidade ao longo do tempo | Descartada: um único NPC conversando com uma pessoa fica perto do companheiro com memória, já maduro |

## 2. Ideia 1 — A casa que se gera em volta de você: um mod de The Sims 4

**O que é.** Um mod de The Sims 4 em que o jogador coloca um Sim num lote e o mod gera de 2 a 4 moradores na mesma casa. Um modelo de linguagem escreve cada morador a partir do Sim inicial: nome, idade, traços, aspiração, relação com ele e uma história de fundo. A aparência fica com o sorteador do próprio jogo.

Depois de gerados, os moradores agem com memória e reflexão. No teste, a turma escolhe pelo celular os traços do Sim inicial e vê a casa ser gerada ao vivo. Em seguida, conversa com os moradores, conta segredos e planta boatos.

**Pergunta sobre o futuro.** Quando um mundo vivo se gera em torno do jogador, as pessoas criadas para ele se comportam como uma família, com história e memória próprias, ou como figurantes a serviço do jogador?

**Tecnologia emergente.** Personagens gerados por modelo de linguagem e agentes generativos com memória (Park et al., 2023), dentro de um jogo comercial fechado. O jogo já sorteia Sims, mas eles nascem sem história, sem relação com quem chega e sem memória do que é dito.

**O que espero observar.**

- A turma testa a coerência: pergunta aos moradores sobre o passado deles e procura contradições.
- Os moradores vivem só em função do Sim inicial, ou formam relações próprias entre si.
- Os boatos passam de morador para morador e chegam distorcidos.

**Viabilidade.** Média. Criar Sims por script, com traços e relações, já é feito por mods conhecidos. O risco é os moradores agirem por decisões vindas de fora do jogo. Testo isso até 18/10 e, se falhar, migro para a ideia 2.

## 3. Ideia 2 — A vila em que a turma se muda

**O que é.** Uma vila web em 2D, aberta por link, com 8 a 10 moradores generativos que têm rotina, memória e relações entre si. Cada pessoa da turma entra como um morador novo, com o mesmo visual dos agentes. Os agentes lembram dos humanos e comentam sobre eles entre si.

**Pergunta sobre o futuro.** O que acontece com uma sociedade simulada quando humanos se mudam para ela: a sociedade absorve os humanos ou é dominada por eles?

**Tecnologia emergente.** Uma sociedade de agentes generativos com memória social, rodando junto com dezenas de humanos. NPCs de jogos seguem roteiro e companheiros com memória atendem uma pessoa por vez. Aqui, o que um agente sabe de você chega aos outros.

**O que espero observar.**

- Agentes falam de pessoas com quem nunca conversaram.
- A turma não consegue distinguir quem é humano.
- A turma se junta para influenciar a vila, ou a vila isola alguém.

**Viabilidade.** Alta. Parte de código aberto e reaproveita a ponte da ideia 1. O risco é a cota do modelo com a turma inteira.

## 4. Ideia 3 — A turma como cientista social

**O que é.** Uma página onde duplas da turma rodam mini-sociedades de agentes num dilema clássico: um lago compartilhado, em que cada agente decide quanto pescar por rodada. Cada dupla muda uma variável, como escassez, memória ou comunicação. Também pode rodar uma versão disfarçada, com a mesma matemática e outro vocabulário. Um painel junta os resultados da turma.

**Pergunta sobre o futuro.** Se sociedades simuladas por modelos de linguagem virarem instrumento de investigação social, elas vão revelar comportamento novo, ou só vão encenar o que os modelos leram sobre esses experimentos?

**Tecnologia emergente.** Agentes generativos usados como "sujeitos simulados" em experimentos sociais, uma linha de pesquisa recente (por exemplo, GovSim, 2024). Os modelos clássicos de agentes seguem regras fixas. Eles não negociam em linguagem natural nem carregam o que leram sobre o próprio experimento.

**O que espero observar.**

- Os agentes citam a "tragédia dos comuns" enquanto a vivem.
- A versão clássica e a disfarçada dão resultados diferentes.
- A turma desconfia dos resultados e discute se a variação é ruído ou comportamento.

**Viabilidade.** Alta. O código é pequeno, e o cuidado é limitar o número de chamadas ao modelo.

## 5. Preferência e plano B

Prefiro a ideia 1. Se o mod não estiver funcionando até 18/10, troco para a ideia 2 e mantenho a pergunta.

A troca é barata porque as duas ideias compartilham a página web da turma e a ponte em Python com a memória dos agentes. Só muda o "mundo" em que os agentes agem: o lote do The Sims 4 ou a vila 2D.

| Data | Marco |
| --- | --- |
| até 18/10 | Prova de conceito: o mod faz um Sim executar uma interação pedida de fora. Decisão entre a ideia 1 e a ideia 2. |
| 19–25/10 | Ponte com memória, reflexão e escolha de ações; diário de cada Sim. |
| 26–31/10 | Página da turma ligada à ponte, com fila e limite de taxa. |
| 01–03/11 | Ensaio com 3 a 5 pessoas ao mesmo tempo, vídeo de apoio, instalação testada em outra máquina. |
| 04/11 | Entrega do link, do repositório e do README com o que espero que aconteça. |
| 05/11 | Teste com a turma. |
