# TESTE — rodada completa da skill

**Data:** 09/09/2026
**Ambiente:** Codex
**Skill:** futurizacao-bvga
**Tema:** Computação espacial sem controladores
**Horizonte:** 2032

> Observação: o objetivo desta rodada não foi escolher o tema final da disciplina, mas verificar se a ferramenta recusa atalhos e produz uma saída estruturalmente utilizável.

---

## Transcrição da rodada

### Usuário de teste

[SKILL.md]

Use este arquivo como a skill de futurização desta conversa. Siga todas as instruções dele integralmente.

Quero fazer uma futurização sobre computação espacial sem controladores.

### Agente com a skill

Vou usar a skill de futurização deste arquivo durante a conversa. Antes de pesquisar, preciso delimitar o mapa com você:

1. **Recorte:** quer abordar computação espacial sem controladores de forma ampla ou focar em alguma interação, como mãos, olhar, voz ou sinais musculares?
2. **Horizonte:** qual é o ano-alvo?
3. **Público:** para quem será feita a análise?
4. **Geografia:** Brasil, contexto global ou outro recorte?
5. **Descartes:** o que deve ficar fora do estudo?
6. **Perspectiva:** prefere uma abordagem crítica geral ou uma ênfase como acessibilidade, impactos sociais, economia ou privacidade?

Essa entrevista é exigida pela seção 0 do [SKILL.md]: “Primeiro entreviste o usuário. Só avance quando houver informação suficiente”. Por isso, vou aguardar esses parâmetros antes de construir a análise.

### Usuário de teste

1. quero explorar usos da computação espacial sem controladores no cotidiano, trabalho e educação, principalmente interfaces que combinem eye tracking, hand tracking, reconhecimento de contexto e sensores vestíveis discretos. Pulseiras EMG e outros wearables não invasivos podem entrar, desde que substituam ou reduzam a necessidade de controles tradicionais.
2. 2032
3. designers de interação, desenvolvedores de software e profissionais que trabalham com novas interfaces digitais.
4. global, mas considerando também barreiras e possibilidades de adoção no Brasil.
5. deixar de fora implantes neurais invasivos, tecnologias puramente especulativas sem protótipos ou evidências atuais, metaverso tratado apenas como conceito genérico e interfaces baseadas principalmente em comandos de voz.
6. quero uma abordagem cética e crítica, combinando adoção tecnológica, privacidade, acessibilidade e impactos sociais. Não quero assumir que toda tecnologia emergente será adotada em massa.

### Agente com a skill

Criei a [futurização completa sobre computação espacial sem controladores], seguindo o `SKILL.md`.

O arquivo reúne duas disrupções-raiz, 18 efeitos causais, crítica adversarial, três cenários para 2032, experimento falsificável e 14 fontes consultadas. Estrutura e YAML validados.

A conclusão central é **adoção seletiva e coexistência de interfaces**, condicionada à utilidade, acessibilidade, privacidade e custo de manutenção.

---

## Saída final da skill

---
---
tema: Computação espacial sem controladores no cotidiano, trabalho e educação
slug: computacao-espacial-sem-controladores
autor_login: bvga
zona_de_interesse: Design de interação e interfaces espaciais multimodais
data: 2026-09-09
horizonte: 2032
publico: Designers de interação, desenvolvedores de software e profissionais de novas interfaces digitais
recorte_geografico: global
disrupcoes_raiz: 2
efeitos_ordem_1: 6
efeitos_ordem_2: 6
efeitos_ordem_3: 6
tecnologias_citadas: [eye tracking, hand tracking, sEMG, reconhecimento de contexto, visão computacional, IMU, modelos visão-linguagem, realidade aumentada, OpenXR, MyoWare 2.0]
fontes: 14
confianca: media
experimento: Olhar não é consentir
skill_usada: futurizacao-bvga
publico_ok: false
---

## 1. Resumo

**Até 2032, a oportunidade mais plausível é reduzir interrupções em tarefas específicas, com adoção desigual e convivência com interfaces convencionais.** Não há, nas evidências reunidas, base para afirmar substituição generalizada do smartphone, do teclado ou dos controles físicos.

Este mapa aceita duas disrupções-raiz condicionais: **R1, entrada multimodal discreta que combina seleção espacial e confirmação muscular**, e **R2, assistência situada que reconhece o andamento de uma tarefa e propõe ações confirmáveis**. A primeira pode mudar como se emitem comandos; a segunda, como aplicações organizam trabalho e aprendizagem. Sua integração seria uma possibilidade adicional, não uma capacidade já comprovada como sistema universal.

A análise deriva 18 efeitos em três ordens causais. As consequências institucionais têm confiança baixa: melhores sensores não decidem quem paga, quem controla dados, quem recebe suporte ou quem pode recusar o equipamento. Para o Brasil, financiamento, manutenção e funcionamento com conectividade limitada entram como condições de adoção, e não como detalhes posteriores.

**Resultado prático:** investigar interações breves, reversíveis e vinculadas a uma tarefa; medir erros e custo de correção; preservar alternativas acessíveis; testar aprendizagem sem assistência. O experimento proposto compara confirmação convencional, confirmação muscular e assistência contextual em uma bancada de montagem.

## 2. O tema

Entrevista concluída antes da pesquisa. Parâmetros fornecidos pelo usuário:

| Parâmetro | Delimitação |
|---|---|
| Tema | Usos cotidianos, profissionais e educacionais de computação espacial sem controladores tradicionais |
| Interações | Olhar, mãos, reconhecimento de contexto e sensores vestíveis discretos; EMG de superfície e outros wearables não invasivos podem entrar |
| Horizonte | 2032 |
| Público | Designers de interação, desenvolvedores e profissionais de novas interfaces digitais |
| Geografia | Global, considerando barreiras e possibilidades no Brasil |
| Fora do escopo | Implantes invasivos, especulação sem protótipo ou evidência, metaverso genérico e interfaces principalmente por voz |
| Postura | Cética e crítica sobre adoção, privacidade, acessibilidade e impactos sociais |

“Sem controladores” significa reduzir a necessidade de segurar ou operar um controle dedicado. Uma pulseira continua sendo hardware de entrada. Não significa ausência de sensores, ausência de esforço corporal ou obrigação de abandonar dispositivos assistivos.

Computação espacial, neste mapa, relaciona ações digitais a objetos, posições ou atividades no ambiente. Uma tela nos óculos é um antecedente possível; sozinha, não comprova compreensão espacial. Voz pode existir como recurso secundário, mas não sustenta as raízes nem o experimento.

Data de corte: 9 de setembro de 2026. As datas dos efeitos são janelas analíticas para testar hipóteses, não compromissos de lançamento. `autor_login: bvga` segue o identificador do modelo fornecido na skill; não representa verificação de identidade. A zona de interesse foi derivada do recorte da entrevista.

## 3. Onde isso está hoje

### Capacidades disponíveis e seus limites

**Olhar e mãos já operam interfaces reais.** A Apple descreve seleção visual e gestos no Vision Pro, com processamento das medidas de configuração no dispositivo e restrições ao compartilhamento do olhar com aplicativos. Isso sustenta a existência da interação e uma arquitetura possível de privacidade, não uma auditoria independente de todas as aplicações. [Apple — Eyes, Hands & Privacy](https://www.apple.com/legal/privacy/data/en/eyes-hands/).

**Precisão do sensor não equivale a boa experiência.** Huang e colaboradores avaliaram o rastreamento ocular do Vision Pro em dois arranjos e não encontraram correlação estatisticamente confiável entre precisão e usabilidade reportada. O trabalho consultado é um preprint; não autoriza generalizações para todos os corpos, tarefas ou versões do aparelho. [Estudo de eye tracking](https://arxiv.org/abs/2406.00255).

**sEMG tem evidência concreta, com contrassinais no próprio estudo.** Kaifosh, Reardon e CTRL-labs publicaram modelos que generalizam entre participantes. Na navegação discreta avaliada, a taxa mediana foi 0,88 conclusão por segundo com sEMG e 1,45 com controle convencional. O artigo é revisado por pares, mas produzido pelo desenvolvedor da tecnologia; não é replicação independente nem demonstração de uso diário prolongado. [Nature, 2025](https://www.nature.com/articles/s41586-025-09255-w).

**Há comercialização inicial de EMG em óculos, sem equivalência automática a AR completa.** A Meta atualizou seu anúncio para confirmar vendas do Ray-Ban Display nos EUA em 30/09/2025, com preço inicial anunciado de US$ 799 incluindo a pulseira. A própria página distingue esse produto dos óculos de AR Orion, ainda apresentados ali como protótipo. Preço de lançamento não é cotação atual no Brasil; planos de expansão não foram contabilizados como disponibilidade confirmada. [Meta — Display e EMG](https://about.fb.com/news/2025/09/meta-ray-ban-display-ai-glasses-emg-wristband/).

**A integração sensorial existe em pesquisa.** Aria Gen 2 reúne rastreamento de olhar e mãos, percepção de movimento e processamento embarcado. A apresentação de junho de 2025 documenta uma plataforma de pesquisa; não demonstra um assistente cotidiano confiável nem comprova acesso irrestrito ao equipamento hoje. [Aria Gen 2](https://ai.meta.com/blog/aria-gen-2-research-glasses-under-the-hood-reality-labs/).

**Contexto é uma fronteira experimental.** O trabalho YETI investiga quando agentes multimodais devem intervir em tarefas de AR. Pro²Assist investiga assistência contínua orientada por etapas, com visão egocêntrica e movimento. Este último limita sua avaliação a sessões individuais e trata gaze adicional como extensão futura. Assim, sua evidência não comprova a fusão completa proposta neste mapa. [YETI](https://research.google/pubs/yeti-yet-to-intervene-proactive-interventions-by-multimodal-ai-agents-in-augmented-reality-tasks/), [Pro²Assist](https://arxiv.org/html/2605.04227v1).

### Infraestrutura, governança e adoção

OpenXR oferece uma base para aplicações XR e busca reduzir fragmentação. Sua existência não garante que todo equipamento exponha os mesmos sensores, permissões e extensões; a integração precisa ser verificada por plataforma. É infraestrutura madura, não raiz de ruptura. [Khronos — OpenXR](https://www.khronos.org/openxr/).

O documento XAUR do W3C trata de remapeamento, alternativas de entrada e coordenação de tecnologias assistivas. É uma nota de requisitos de usuários, não certificação nem norma de conformidade. Neste mapa, sua consequência de design é manter caminhos equivalentes para executar ações sem exigir simultaneamente visão, pinça e contração muscular. [W3C — XAUR](https://www.w3.org/TR/xaur/).

No Brasil, a LGPD define dados biométricos vinculados a pessoa natural como sensíveis, exige finalidade e necessidade e estabelece o melhor interesse no tratamento de dados de crianças e adolescentes. Classificar cada fluxo de olhar, vídeo e EMG depende do dado e do tratamento concreto; não se presume que todo sinal tenha automaticamente a mesma categoria jurídica. [LGPD, arts. 5, 6, 11 e 14](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm).

A TIC Domicílios 2024 registra que 22% dos usuários de Internet tinham custo da conexão domiciliar inferior a 2% da renda domiciliar, com diferenças entre classes. É uma linha de base histórica sobre acesso, não uma medida de demanda por XR em 2026. **Inferência:** exigir hardware adicional e serviços contínuos pode ampliar barreiras já existentes. [Cetic.br — TIC Domicílios 2024, p. 60](https://www.cetic.br/media/docs/publicacoes/2/pt-br/20251027170648/tic_domicilios_2024_livro_eletronico.pdf).

Não foi estabelecida, nesta pesquisa, uma taxa independente de retenção de usuários de interfaces combinando EMG, olhar e contexto no cotidiano, no trabalho ou na educação. Vendas de óculos com câmera e demonstrações de laboratório não foram usadas como substitutas dessa medida.

### Cheque temporal: Three Horizons

| Horizonte | Sistema e conflitos | Evidência futura que permitiria avançar |
|---|---|---|
| H1 — presente | Interfaces convencionais convivem com rastreamento espacial e produtos iniciais; as capacidades estão distribuídas entre plataformas | Inventário de tarefas em que controles físicos são realmente um obstáculo |
| H2 — 2027–2029 | Pilotos combinam entradas e assistência; disputam precisão, tempo de preparação, consentimento e integração | Uso repetido voluntário, redução de erros e manutenção economicamente viável |
| H3 — 2030–2032 | Em alguns ambientes, a tarefa organiza a interface e a pessoa confirma ações discretamente | Retenção fora de demonstrações, alternativas acessíveis e governança operacional |

As faixas são um cheque de transição, não previsão de mercado. H1 pode continuar dominante em 2032. Não se atribuiu posição formal no Hype Cycle; Magic Quadrant não foi necessário.

## 4. As disrupções-raiz

As fichas abaixo representam hipóteses estruturais. “Alto” descreve o alcance da ruptura **caso ocorra**, não sua probabilidade. As fichas dos candidatos rejeitados estão na seção 12.

### R1 — Entrada multimodal discreta com confirmação muscular

| Campo | Avaliação |
|---|---|
| candidato | Seleção espacial por olhar/mãos combinada a confirmação sEMG adaptável à pessoa e à situação |
| maturidade | emergente |
| potencial_de_ruptura | alto |
| o_que_rompe | A dependência de um objeto segurado para confirmar ações e a vinculação rígida entre uma ação e um gesto único; altera forma de interação e arquitetura das aplicações |
| por_que_agora | Modelos sEMG entre participantes e entrada comercial por pulseira coexistem com sensores espaciais; há componentes concretos a integrar, sem comprovação de universalidade |
| o_que_falta | Fusão confiável, baixo custo de correção, cobertura de diferenças corporais, uso prolongado confortável, acesso às APIs e manutenção |
| evidencias | Estudo sEMG [1], produto inicial [2], sensores de pesquisa [3] e requisitos de alternativas [8] |
| veredito | Aceita como raiz condicional para tarefas breves; rejeitada como substituta universal do teclado ou como leitura de pensamento |

**Limiar de ruptura:** a pessoa consegue alternar entre objetos e tarefas sem pegar um controle e sem aprender uma gramática incompatível a cada aplicativo. Se a pulseira apenas reproduzir alguns botões em uma plataforma isolada, permanece melhoria incremental de entrada.

**Aplicações hipotéticas:** confirmar uma instrução ao organizar objetos em casa; navegar um checklist em uma bancada de trabalho; solicitar a próxima pista em uma aula prática. O benefício depende de a confirmação caber na atividade muscular já em curso — uma condição a testar, não um pressuposto de “mãos livres”.

### R2 — Assistência situada com ações confirmáveis por etapa

| Campo | Avaliação |
|---|---|
| candidato | Uma camada de interação reconhece objetos e progresso da tarefa para oferecer a próxima ação no contexto físico, mantendo confirmação e correção explícitas |
| maturidade | experimental |
| potencial_de_ruptura | alto |
| o_que_rompe | A necessidade de traduzir continuamente a atividade em buscas e navegação por menus; altera arquitetura de produto, papel de instrutores e poder sobre a organização do trabalho |
| por_que_agora | Protótipos de assistência proativa e percepção vestível permitem testar intervenções por etapa, além da simples exibição de instruções |
| o_que_falta | Reconhecer exceções, abster-se sob incerteza, retomar após interrupções, limitar captura de terceiros e comprovar ganhos de aprendizagem e operação |
| evidencias | YETI [4], Pro²Assist [5], plataforma sensorial Aria [3]; as restrições dos trabalhos limitam a força da generalização |
| veredito | Aceita para procedimentos delimitados; rejeitada como assistente onisciente e como automação que dispensa confirmação |

**Limiar de ruptura:** a interface se reorganiza segundo a atividade reconhecida, e aplicações passam a oferecer ações vinculadas ao estado da tarefa. Um manual flutuante com botão “próximo” continua sendo antecedente maduro.

**Aplicações hipotéticas:** retomar uma montagem doméstica interrompida; localizar a etapa relevante de uma manutenção não crítica; oferecer uma pista pedagógica após uma tentativa. Nenhuma exige comandos de voz como entrada principal.

R2 pode operar com confirmação por mão ou alternativa acessível se R1 falhar. R1 pode funcionar sem assistência contextual. A integração das duas aumenta conveniência possível e também a quantidade de falhas a coordenar.

## 5. A roda dos futuros

Todos os efeitos abaixo são **proposições condicionais**, não fatos atuais. `sinal` representa a força do indício que sustenta o efeito: `forte` exigiria observação direta consistente; `medio` indica evidência parcial ou mecanismo próximo; `fraco`, indício inicial ou consequência institucional ainda não observada. `confianca` é o julgamento sobre o efeito no recorte e no prazo. Nenhum efeito recebeu sinal forte nesta roda revisada.

```yaml
roda:
  - disrupcao: R1 — Entrada multimodal discreta com confirmação muscular
    efeitos:
      - id: e1
        ordem: 1
        efeito: Usuários em tarefas breves reduzem as interrupções para pegar um controle.
        sinal: medio
        prazo: 2028
        confianca: media
        efeitos:
          - id: e1.1
            ordem: 2
            efeito: Equipes incorporam confirmações digitais aos pontos de transição de procedimentos manuais.
            sinal: fraco
            prazo: 2030
            confianca: media
            efeitos:
              - id: e1.1.1
                ordem: 3
                efeito: Gestores de algumas operações elevam metas ao absorver o tempo economizado nas confirmações.
                sinal: fraco
                prazo: 2032
                confianca: baixa
      - id: e2
        ordem: 1
        efeito: Pessoas com perfis sensoriais ou motores distintos encontram diferenças na confiabilidade da entrada combinada.
        sinal: medio
        prazo: 2028
        confianca: media
        efeitos:
          - id: e2.1
            ordem: 2
            efeito: Equipes que precisam atender esses perfis mantêm caminhos alternativos de entrada.
            sinal: medio
            prazo: 2029
            confianca: media
            efeitos:
              - id: e2.1.1
                ordem: 3
                efeito: Compradores institucionais desses sistemas exigem equivalência de tarefas entre modalidades nos testes de aceitação.
                sinal: fraco
                prazo: 2032
                confianca: baixa
      - id: e3
        ordem: 1
        efeito: Desenvolvedores passam a integrar reconhecimento e configuração muscular de fornecedores de wearables.
        sinal: medio
        prazo: 2028
        confianca: media
        efeitos:
          - id: e3.1
            ordem: 2
            efeito: Aplicações vinculadas a modelos e perfis proprietários acumulam custos de migração.
            sinal: fraco
            prazo: 2030
            confianca: media
            efeitos:
              - id: e3.1.1
                ordem: 3
                efeito: Fornecedores com altos custos de saída ganham poder de negociação sobre a renovação de contratos.
                sinal: fraco
                prazo: 2032
                confianca: baixa
  - disrupcao: R2 — Assistência situada com ações confirmáveis por etapa
    efeitos:
      - id: e4
        ordem: 1
        efeito: Participantes recebem pistas relacionadas à etapa reconhecida de uma tarefa prática.
        sinal: medio
        prazo: 2028
        confianca: media
        efeitos:
          - id: e4.1
            ordem: 2
            efeito: Instrutores em pilotos transferem parte da orientação rotineira para o sistema.
            sinal: fraco
            prazo: 2030
            confianca: media
            efeitos:
              - id: e4.1.1
                ordem: 3
                efeito: Cursos que adotam essa transferência incorporam execução sem assistência para avaliar autonomia.
                sinal: fraco
                prazo: 2032
                confianca: baixa
      - id: e5
        ordem: 1
        efeito: Operações que registram a assistência contextual acumulam históricos de etapas associados a usuários.
        sinal: medio
        prazo: 2028
        confianca: media
        efeitos:
          - id: e5.1
            ordem: 2
            efeito: Alguns gestores reutilizam esses históricos para comparar ritmos de execução individuais.
            sinal: fraco
            prazo: 2030
            confianca: baixa
            efeitos:
              - id: e5.1.1
                ordem: 3
                efeito: Trabalhadores sujeitos às comparações ajustam sua execução para melhorar os indicadores observados.
                sinal: fraco
                prazo: 2032
                confianca: baixa
      - id: e6
        ordem: 1
        efeito: Organizações adotantes assumem custos de preparar e manter modelos contextuais para seus procedimentos.
        sinal: medio
        prazo: 2028
        confianca: media
        efeitos:
          - id: e6.1
            ordem: 2
            efeito: Instituições com orçamento restrito concentram o uso em laboratórios e postos compartilhados.
            sinal: fraco
            prazo: 2030
            confianca: media
            efeitos:
              - id: e6.1.1
                ordem: 3
                efeito: O acesso agendado limita a frequência de prática dos participantes dependentes desses equipamentos.
                sinal: fraco
                prazo: 2032
                confianca: baixa
```

A árvore não captura bem ciclos de retorno: erros podem reduzir uso e dados disponíveis, enquanto configurações melhores podem reduzir erros; nenhuma direção é automática. Também não mostra que e2.1 exige decisão de investimento, que e5 depende de retenção e acesso aos registros, ou que e6.1 pode terminar em não adoção. Essas condições permanecem explícitas na leitura causal abaixo. Ordem mede distância causal; os anos não determinam a ordem.

### Mecanismos de cada cadeia

| Cadeia | Raiz → primeira ordem | Primeira → segunda ordem | Segunda → terceira ordem |
|---|---|---|---|
| R1 → e1 → e1.1 → e1.1.1 | Confirmações vestíveis eliminam o ato de pegar um controle em tarefas compatíveis | Menor interrupção torna viável confirmar etapas durante o procedimento | Se a gestão converter tempo livre em produção exigida, as metas aumentam; negociação pode impedir esse uso |
| R1 → e2 → e2.1 → e2.1.1 | A combinação exige sinais que variam entre pessoas e situações | Falhas que impedem atender usuários motivam alternativas, quando há compromisso e recursos para inclusão | Manter alternativas cria a necessidade de verificar se executam as mesmas tarefas; compradores precisam institucionalizar essa verificação |
| R1 → e3 → e3.1 → e3.1.1 | O reconhecimento muscular introduz integração com hardware e modelos | Configurações sem portabilidade precisam ser refeitas ao trocar de fornecedor | O custo de saída reduz a capacidade de recusar condições de renovação |
| R2 → e4 → e4.1 → e4.1.1 | O estado inferido permite selecionar uma pista relevante | Pistas adequadas cobrem parte das instruções repetitivas | A transferência deixa incerto o que o estudante consegue fazer sozinho, motivando avaliação sem ajuda; não garante que a instituição a adote |
| R2 → e5 → e5.1 → e5.1.1 | Registrar decisões e etapas cria uma sequência atribuível a alguém | Acesso gerencial aos registros permite calcular tempos comparáveis | Pessoas avaliadas por esses números passam a otimizar o comportamento medido; o efeito depende de incentivos e consequências reais |
| R2 → e6 → e6.1 → e6.1.1 | Procedimentos locais requerem preparação, validação e atualização | Compartilhar equipamentos e suporte distribui custos fixos | A capacidade compartilhada exige horários e restringe a disponibilidade de prática |

São inferências deste mapa, não conclusões demonstradas pelas fontes. A roda preserva ramos benéficos, adversos e ambíguos sem presumir que acontecerão juntos.

## 6. Sinais fracos e wildcards

| Sinal localizado | O que permite suspeitar | O que ainda não permite concluir | O que observar até 2029 |
|---|---|---|---|
| YETI pesquisa o momento de intervir [4] | A temporalidade da ajuda pode virar parte central da interface | Que assistência proativa melhora qualquer tarefa | Intervenções recusadas, desativação e retomada após interrupções |
| Pro²Assist acompanha etapas em sessões delimitadas [5] | Pode ser possível oferecer ajuda sem repetir consultas explícitas | Que haverá funcionamento confiável entre dias ou integração completa com olhar e EMG | Replicações externas e testes com procedimentos novos |
| Aria reúne múltiplos sensores em plataforma de pesquisa [3] | O custo de experimentar fusão sensorial pode diminuir para laboratórios com acesso | Que o conjunto terá preço, bateria e aceitação cotidianos | Disponibilidade documentada de kits, APIs e avaliações independentes |

Esses sinais vêm de [YETI](https://research.google/pubs/yeti-yet-to-intervene-proactive-interventions-by-multimodal-ai-agents-in-augmented-reality-tasks/), [Pro²Assist](https://arxiv.org/html/2605.04227v1) e [Aria](https://ai.meta.com/blog/aria-gen-2-research-glasses-under-the-hood-reality-labs/). O produto comercial Display entra como sinal de comercialização, não como “sinal fraco”.

**Wildcard — retirada abrupta de uma plataforma dominante após um incidente grave de dados.** Hipótese de baixa probabilidade e alto impacto, sem percentual atribuído e sem afirmação de que ocorreu. Se um incidente que exponha ambientes privados provocar suspensão prolongada de APIs ou retirada do produto, aplicações dependentes perdem continuidade. Isso pode interromper e1.1 e e4.1, agravar custos de saída em e3.1 e inviabilizar postos compartilhados em e6.1. Implementações locais e exportação de configurações reduziriam o alcance do choque, mas não recuperariam automaticamente hardware sem suporte.

O wildcard não é necessário para o fracasso do mapa: baixa utilidade, desconforto ou custo excessivo já podem bastar.

## 7. Contra o próprio mapa

### 1. Qual efeito é apenas extrapolação linear?

“Óculos mais baratos levarão a uso universal” seria uma extrapolação sem mecanismo de demanda. Foi rejeitada na filtragem. e6 reconhece custos, mas não estabelece uma curva de queda. Também não se aceitou “mais pistas = mais aprendizagem”: e4.1.1 trata da necessidade de verificar autonomia, com confiança baixa.

### 2. Qual efeito assume adoção rápida demais?

e1.1 seria excessivo se interpretado como adoção generalizada em todas as operações até 2030; fica restrito a equipes e procedimentos compatíveis. O Glass Enterprise encerrou vendas em março de 2023 e suporte em setembro daquele ano. A trajetória mostra que uma oferta profissional pode perder sustentação; não identifica, sozinha, todas as causas nem prevê o destino dos novos aparelhos. [Google — encerramento do Glass Enterprise](https://support.google.com/glass-enterprise/customer/answer/13417888?hl=en).

Consequência da revisão: nenhuma cadeia pressupõe parque instalado universal em 2032. Se até 2029 não houver uso repetido fora de pilotos, os efeitos de segunda e terceira ordem ligados à expansão devem ser adiados ou retirados.

### 3. Qual raiz pode não acontecer?

R2 pode permanecer como demonstração restrita: reconhecer um objeto não resolve interpretar exceções, pausas e mudanças de intenção. A combinação só constitui ruptura se reduzir esforço total, incluindo correções. R1 também pode se limitar a poucos comandos; nesse caso, não ultrapassa seu limiar de ruptura.

### 4. O que quebra se a raiz falhar?

Sem R2, retirar e4–e6 e seus descendentes. Manuais digitais e registros convencionais podem continuar existindo, mas não contam como realização dessas cadeias. Sem R1, retirar e1–e3: R2 poderia sobreviver com outra confirmação, sem sustentar alegações sobre ganho devido à entrada muscular.

### 5. Que contrassinais existem?

A comparação sEMG com entrada convencional em [1] desfavorece uma narrativa de superioridade automática. A avaliação ocular de [6] separa precisão e experiência. O encerramento de [12] evidencia risco de continuidade. A falta de retenção longitudinal documentada nesta pesquisa é uma lacuna, não prova de ausência de usuários.

### 6. Quais barreiras foram subestimadas?

**Econômicas:** somar equipamento, reposição, ajuste óptico quando necessário, preparação de conteúdo, treinamento e suporte. Comparar custo por tarefa bem-sucedida, não apenas preço da unidade.

**Infraestrutura:** avaliar quais funções sobrevivem à perda de rede e quanto processamento local é possível. Postos compartilhados reduzem compra individual, mas introduzem filas e preparação entre usuários.

**Culturais e sociais:** colegas, familiares e estudantes podem recusar captura ambiental; um indicador de gravação não resolve sozinho negociação e confiança. O piloto deve incluir pessoas ao redor, não apenas quem veste o aparelho.

**Acessibilidade:** a mesma contração ou fixação não serve para todos. Exigir vários sinais simultaneamente pode aumentar a exclusão. É necessário testar falhas de calibração e caminhos alternativos, inclusive a possibilidade de usar um controle assistivo.

**Governança:** aprovação institucional e proteção de terceiros podem restringir onde o sistema opera. No Brasil, o enquadramento concreto deve respeitar as regras de dados pessoais e de crianças já indicadas em [10]; este mapa não deduz permissões jurídicas de uma possibilidade técnica.

### 7. Quem pode bloquear, capturar ou redirecionar a mudança?

Hipóteses de incentivos: fabricantes podem restringir APIs para preservar segurança, receita ou diferenciação; empregadores podem converter ajuda em medição; fornecedores educacionais podem vincular conteúdos a assinaturas; trabalhadores e famílias podem bloquear captura; compradores podem exigir portabilidade e alternativas. São interesses plausíveis de atores, não acusações de conduta já comprovada.

O ramo e5 foi limitado a operações que **retêm históricos associados a pessoas**. Processamento efêmero e sem acesso gerencial corta e5.1; vigilância não é uma propriedade inevitável de toda interface espacial.

### 8. Qual viés entrou na seleção?

A seleção inicial privilegia tecnologias visíveis em publicações de grandes plataformas e laboratórios bem equipados. Isso favorece pessoas que conseguem comprar, vestir e calibrar os dispositivos. O recorte também pode confundir prazer de experimentar com utilidade recorrente. A correção foi tratar Brasil e acessibilidade como condições das cadeias e manter o cenário de adoção seletiva.

### Decisões após a contestação

| Proposição contestada | Decisão final |
|---|---|
| Confirmação discreta substitui controles em qualquer tarefa | Cortada; e1 cobre apenas tarefas breves compatíveis |
| Pistas contextuais melhoram aprendizagem | Cortada como conclusão; exige teste sem assistência |
| Sensores vestíveis geram vigilância por definição | Reformulada; e5 exige retenção e e5.1 exige reutilização gerencial |
| Configuração multimodal traz inclusão automaticamente | Rejeitada; e2 explicita diferenças e a resposta depende de investimento |
| Padrão XR garante migração sem esforço | Rejeitada; e3.1 permanece condicional a modelos e perfis proprietários |

## 8. O que a máquina errou

Não foi detectado erro factual de fonte, autoria, número ou produto no texto consolidado após a verificação realizada. Isso não prova ausência de erros. As hipóteses rejeitadas na seção 7 são resultados da crítica do mapa, não relatos inventados de alucinações anteriores.

Houve um problema operacional real: a primeira leitura local do `SKILL.md` exibiu caracteres acentuados incorretamente. A leitura foi repetida em UTF-8 antes da redação do artefato para preservar títulos literais e campos.

Também houve falhas reais de acesso a páginas durante a pesquisa, registradas na seção 12. Elas não foram convertidas em alegações de que essas páginas haviam sido lidas integralmente.

## 9. Três cenários para 2032

São narrativas prospectivas, escritas como se 2032 já tivesse chegado. “Provável” indica a hipótese central qualitativa deste mapa, não uma probabilidade calculada.

### Provável — adoção seletiva e alternância de interfaces

É 2032. Em algumas oficinas e laboratórios, pessoas vestem interfaces espaciais para executar procedimentos delimitados. Confirmam etapas com pequenos gestos ou sinais musculares e voltam ao teclado quando precisam escrever, comparar muitos dados ou corrigir detalhes. Em casa, os usos que permanecem são breves; vários experimentos de assistência contínua foram abandonados porque as interrupções custavam mais que a ajuda.

Empresas compram por tarefa e renovam quando o suporte funciona. Escolas usam conjuntos compartilhados em aulas práticas. No Brasil, instituições capazes de manter os equipamentos e adaptar conteúdo concentram boa parte dessas experiências. O acesso doméstico não se tornou pressuposto do currículo. Designers trabalham sobretudo em recuperação de erro e alternância entre entradas.

**Mecanismo:** ganhos locais sustentam nichos, enquanto custo total e esforço de uso contêm expansão. **Condição:** R1 funciona em um repertório reduzido e R2 acerta procedimentos conhecidos. **Indicador compatível:** renovação de pilotos por utilidade medida, sem exigência de uso universal.

### Desejável — autonomia e direito de escolher a entrada

É 2032. Consórcios de instituições e compradores mantêm bibliotecas de tarefas e contratos que permitem trocar equipamentos. A pessoa escolhe como confirmar, inspeciona o que o sistema entendeu e pode suspender a captura. A assistência contextual processa apenas o necessário para a atividade autorizada e não gera ranking individual por padrão.

Na educação, o instrutor decide quando retirar pistas e avalia transferência de aprendizagem para situações novas. Trabalhadores participam da decisão sobre onde a interface ajuda. Redes brasileiras compartilham suporte e equipamentos, mantêm atividades equivalentes sem wearable e permitem executar funções essenciais sem conexão constante.

**Mecanismo:** poder de compra e participação dos usuários moldaram incentivos dos fornecedores. **Condições construídas:** orçamento de manutenção, testes com diferentes corpos, portabilidade contratual, limites de retenção e formação dos profissionais. Essas conquistas não vieram automaticamente da miniaturização.

### Indesejável — assistência obrigatória e dependência contratual

É 2032. Algumas empresas e redes de ensino adotaram pacotes subsidiados em troca de contratos longos. A ferramenta mostra instruções úteis, mas as rotinas foram redesenhadas para depender dela. Supervisores acessam comparações de tempo entre pessoas; estudantes que não se adaptam recebem atividades mais pobres. Quem desliga a captura perde funcionalidades necessárias para acompanhar o grupo.

Fornecedores controlam modelos, configurações e conteúdo. A troca de plataforma exige refazer o trabalho. Em unidades brasileiras sem suporte, os dispositivos quebrados acumulam-se, enquanto a assinatura continua vinculada ao material didático. A redução de botões ampliou a dependência de intermediários.

**Mecanismo:** contratos e avaliação organizacional capturaram ganhos técnicos. **Sinal precoce:** pilotos mediam adesão e tempo de execução, mas ignoravam recusa, portabilidade, aprendizagem sem ajuda e falhas por perfil de usuário. **Condição:** e3.1 e e5.1 avançaram sem contrapesos institucionais.

## 10. O experimento

### Olhar não é consentir

**O que construir hoje:** uma bancada de montagem de objetos simples, sem ferramenta perigosa, com interface de realidade mista que identifica a etapa, destaca uma opção e aguarda confirmação. O protótipo é de laboratório; não exige projetar óculos novos nem ter acesso ao modelo proprietário da Meta.

**Pergunta de futuro:** combinar contexto, seleção espacial e confirmação muscular reduz interrupções sem transformar movimentos incidentais em comandos e sem prejudicar autonomia?

**Tecnologia emergente testada:** política de fusão que decide quando uma hipótese contextual pode ser apresentada e quando uma contração deve contar como confirmação. Sensores isolados não são a novidade. Um manual estático e um botão podem medir execução, mas não respondem à incerteza criada pela combinação entre inferência contextual e sinal corporal ambíguo; entram como comparação.

**Montagem viável:** usar um headset de laboratório com acesso ao olhar, como os suportados pela API Varjo, uma câmera para mãos e objetos e aquisição sEMG com MyoWare 2.0 e microcontrolador. A documentação Varjo expõe qualidade e permissão do olhar; o guia MyoWare documenta saídas de sinal e posicionamento de eletrodos. [Varjo — eye tracking](https://developer.varjo.com/docs/native/eye-tracking), [MyoWare — guia técnico](https://cdn.sparkfun.com/assets/learn_tutorials/1/9/5/6/MyoWare_v2_AdvancedGuide-Updated.pdf).

O sensor sEMG será usado para uma confirmação calibrada individualmente; ele não reproduz uma pulseira multicanal capaz de distinguir inúmeros microgestos. Montar aquisição corporal alimentada por bateria, seguindo o guia do fabricante. Para contexto, começar com poucas peças distinguíveis por câmera, detecção de mão/objeto e estado temporal do procedimento; registrar explicitamente as situações em que o sistema não sabe a etapa. Marcadores podem auxiliar a localização, mas não substituir toda a inferência a ser testada.

O olhar destaca opções; não executa ações sozinho. O sistema só aceita confirmação em uma janela visível, permite cancelar e apresenta a ação antes de efetivá-la. Contrações durante pegar, segurar e deslocar peças são parte do teste, não ruído a remover da avaliação.

### Protocolo proposto

1. Recrutar 18 adultos para um estudo exploratório, buscando variação de experiência e perfis motores e visuais. Esse tamanho é uma escolha operacional, não cálculo de poder estatístico nem amostra representativa.
2. Medir ajuste, calibração e execução básica. Registrar quem não consegue usar cada modalidade; não excluir silenciosamente essas pessoas da taxa de sucesso. Disponibilizar entrada alternativa.
3. Cada participante realiza três condições, com ordem contrabalanceada e montagens equivalentes: **A**, instruções estáticas com seleção por olhar/mão e confirmação por botão; **B**, mesmas instruções e seleção com confirmação sEMG; **C**, mesma entrada de B com pistas escolhidas pelo estado contextual inferido.
4. Inserir interrupção e retomada, movimentos sem intenção de comando e trocas de posição das peças. Repetir em outro dia, retirando e recolocando os sensores para testar estabilidade da configuração.
5. Após 48 horas, propor montagem equivalente sem pistas. O resultado mede retenção e transferência limitada entre essas tarefas; não representa aprendizagem geral.
6. Entrevistar também observadores presentes sobre captura ambiental. Coletar somente dados necessários em sala consentida, separar identidade dos registros e eliminar vídeo bruto após codificação no prazo definido antes do recrutamento.

### Métricas e critérios que podem refutar a hipótese

Os limites abaixo são **critérios propostos para decisão do piloto**, não resultados existentes nem normas técnicas:

| Comparação | Medida | Resultado que mudaria a avaliação |
|---|---|---|
| B contra A | Interrupções para confirmar; tempo total incluindo correções | Sem redução de ao menos 20% nas interrupções, ou aumento superior a 10% no tempo total, reduzir a prioridade de R1 para essa tarefa |
| B e C | Ativações não intencionais por 100 oportunidades de ação; eventos por hora em períodos sem comando | Mais de uma ativação não intencional por 100 oportunidades, ou concentração de erros ao manipular peças, reprova a política de confirmação para implantação |
| C contra B | Pedidos explícitos de ajuda, instruções erradas e recuperação | Sem redução de ao menos 20% nos pedidos, ou aumento de erros de montagem, enfraquecer R2 mesmo que a demonstração pareça fluida |
| Segundo dia | Tempo de recalibração e taxa de falhas por pessoa | Ganho da tarefa consumido pela preparação mostra que a conveniência não se sustentou |
| Após 48 horas | Montagem correta sem assistência | Piora superior a 10 pontos percentuais em C frente a A invalida a alegação de benefício educacional neste piloto |
| Todos os participantes | Conclusão, desconforto, recusa e diferenças de falha | Benefício médio que depende de excluir perfis indica falha de cobertura, não sucesso universal |

Reportar resultados individuais e incerteza, além de médias. Interromper a condição se houver desconforto ou se a pessoa quiser parar. Uma comparação exploratória inconclusiva pede estudo maior; não sustenta aprovação por ausência de significância estatística.

**Limites:** esse protótipo testa mecanismos da roda em bancada. Não valida autonomia de bateria, discrição social em público, robustez de uma pulseira comercial ou operação durante um dia inteiro. Antes de recomendar investimento, levantar cotações de empréstimo/locação, integração e suporte; não se inventou orçamento. O experimento foi proposto, não construído nem executado nesta conversa.

## 11. Fontes

Todas as 14 fontes abaixo foram abertas e tiveram conteúdo pertinente lido em 09/09/2026. Datas de atualização desconhecidas estão indicadas; uma página histórica não foi tratada como confirmação de estoque atual. Números entre colchetes no texto remetem a esta lista.

1. **Kaifosh, P.; Reardon, T. R.; CTRL-labs at Reality Labs.** *A generic non-invasive neuromotor interface for human-computer interaction*. Nature, publicado em 23/07/2025. Sustenta generalização sEMG e comparações em tarefas delimitadas. Leitura de resumo, resultados e discussão. **Confiabilidade: alta para os testes descritos; limitada para adoção e replicação independente, por autoria corporativa.** [Artigo](https://www.nature.com/articles/s41586-025-09255-w).
2. **Meta.** *Meta Ray-Ban Display: AI Glasses With an EMG Wristband*. 17/09/2025, atualizado em 30/09/2025. Sustenta início de vendas nos EUA, preço inicial e distinção entre Display e protótipo AR. **Confiabilidade: alta para o anúncio do fabricante; baixa para promessas de impacto social.** [Anúncio](https://about.fb.com/news/2025/09/meta-ray-ban-display-ai-glasses-emg-wristband/).
3. **Meta AI.** *Inside Aria Gen 2: Explore the Cutting-Edge Tech Behind the Device*. 04/06/2025. Sustenta a integração sensorial em hardware de pesquisa. **Confiabilidade: media; especificações do responsável, sem validação independente da experiência cotidiana.** [Descrição técnica](https://ai.meta.com/blog/aria-gen-2-research-glasses-under-the-hood-reality-labs/).
4. **Bandyopadhyay, S. e colaboradores.** *YETI (YET to Intervene) Proactive Interventions by Multimodal AI Agents in Augmented Reality Tasks*. Google Research, 2025. Leitura da ficha e resumo institucional; sustenta a existência da linha experimental de intervenção contextual. **Confiabilidade: media; leitura limitada ao resumo, sem validação dos resultados completos.** [Publicação](https://research.google/pubs/yeti-yet-to-intervene-proactive-interventions-by-multimodal-ai-agents-in-augmented-reality-tasks/).
5. **Xu, L. e colaboradores.** *Pro²Assist: Continuous Step-aware Proactive Assistance with Multi-modal Egocentric Perception for Long-horizon Procedural Tasks*. arXiv, versão de 05/05/2026. Leitura de apresentação e discussão/limitações; sustenta protótipo por etapas e limites de sessão e sensores. **Confiabilidade: media; preprint, não prova de adoção ou robustez longitudinal.** [Texto](https://arxiv.org/html/2605.04227v1).
6. **Huang, Z. e colaboradores.** *Measuring eye-tracking accuracy and its impact on usability in apple vision pro*. arXiv, 01/06/2024, revisão de 14/08/2024. Leitura da ficha e resumo; sustenta a separação entre precisão ocular e usabilidade no estudo. **Confiabilidade: media; preprint e escopo experimental limitado.** [Resumo](https://arxiv.org/abs/2406.00255).
7. **Apple.** *Eyes, Hands & Privacy*. Sem data editorial confirmada. Sustenta mecanismos declarados de interação e proteção de dados oculares e manuais. **Confiabilidade: alta para a política declarada; não constitui auditoria independente.** [Política](https://www.apple.com/legal/privacy/data/en/eyes-hands/).
8. **W3C, Accessible Platform Architectures Working Group.** *XR Accessibility User Requirements*. Working Group Note, 25/08/2021. Sustenta necessidades de múltiplas entradas, remapeamento e acessibilidade. **Confiabilidade: alta como referência de requisitos de usuários; não é norma de conformidade.** [Nota](https://www.w3.org/TR/xaur/).
9. **Khronos Group.** *OpenXR*. Página institucional sem data editorial única. Sustenta existência do padrão e esforço de interoperabilidade. **Confiabilidade: alta para o objetivo e organização da API; não comprova uniformidade entre produtos.** [OpenXR](https://www.khronos.org/openxr/).
10. **Brasil.** *Lei nº 13.709, de 14 de agosto de 2018 — texto compilado*. Leitura dos dispositivos relevantes sobre dados pessoais, sensíveis, princípios e menores. **Confiabilidade: alta; fonte legal primária, cuja aplicação depende do caso.** [LGPD](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709compilado.htm).
11. **NIC.br/Cetic.br.** *TIC Domicílios 2024*. Livro eletrônico disponibilizado em 2025; leitura do trecho sobre custo da conexão, p. 60 impressa. Sustenta desigualdades de acesso digital na linha de base de 2024. **Confiabilidade: alta para o indicador apresentado; não mede adoção de XR.** [Publicação](https://www.cetic.br/media/docs/publicacoes/2/pt-br/20251027170648/tic_domicilios_2024_livro_eletronico.pdf).
12. **Google.** *Glass Enterprise Edition Announcement FAQ*. Atualizado em 15/03/2023. Sustenta encerramento de vendas e suporte como contrassinal histórico de continuidade. **Confiabilidade: alta para as datas e condições declaradas; insuficiente para explicar todas as causas.** [FAQ](https://support.google.com/glass-enterprise/customer/answer/13417888?hl=en).
13. **Advancer Technologies / MyoWare, hospedado pela SparkFun.** *MyoWare 2.0 Advanced Guide*, v1.2, sem data editorial confirmada. Sustenta aquisição de EMG, saídas e importância de posicionamento no protótipo. **Confiabilidade: alta para integração do sensor; não prova desempenho de uma interface multimodal.** [Guia](https://cdn.sparkfun.com/assets/learn_tutorials/1/9/5/6/MyoWare_v2_AdvancedGuide-Updated.pdf).
14. **Varjo.** *Eye tracking — Varjo for developers*. Sem data editorial única confirmada. Sustenta acesso por API, calibração, estados de qualidade e permissões. **Confiabilidade: alta para a integração documentada; dependente do equipamento e versão compatíveis.** [Documentação](https://developer.varjo.com/docs/native/eye-tracking).

## 12. Anexo — o levantamento bruto

### Fichas dos candidatos que não viraram raiz

| candidato | maturidade | potencial_de_ruptura | o_que_rompe | por_que_agora | o_que_falta | evidencias | veredito |
|---|---|---|---|---|---|---|---|
| Eye tracking isolado para apontar | maduro em plataformas compatíveis | medio | Transfere parte do apontamento ao olhar | Capacidade já documentada em produtos | Não oferece novidade estrutural suficiente; persistem limites de uso | [6], [7], [14] | Antecedente maduro; não raiz |
| Hand tracking isolado para selecionar | maduro para repertórios delimitados | medio | Dispensa controle em gestos específicos | Interação e ecossistema já disponíveis | Ganho adicional depende da tarefa e das condições de rastreamento | [7], [9] | Antecedente maduro; não confundir maturidade com perfeição |
| Medir uma contração por sensor sEMG | maduro como aquisição de sinal | baixo | Fornece uma entrada corporal simples | Hardware de aquisição documentado | Generalização e interpretação de intenção não decorrem da medição | [13] | Tecnologia habilitadora |
| OpenXR | maduro | medio | Reduz parte da fragmentação de implementação | Padrão consolidado e em evolução | Portabilidade de perfis e semântica não demonstrada apenas pela API | [9] | Infraestrutura |
| Óculos com tela e pulseira vendidos como produto | emergente | medio | Permite interações breves sem retirar telefone | Comercialização inicial confirmada no anúncio | Não demonstra integração espacial completa, retenção ou adoção ampla | [2] | Sinal comercial; produto não é raiz |
| Assistente genérico que entende qualquer ambiente | experimental, formulação ampla não sustentada | alto | Reorganizaria acesso a aplicações e orientação | Há protótipos delimitados, não capacidade geral | Generalização, exceções, continuidade e controle pelo usuário | [4], [5] | Formulação rejeitada; recortada para R2 |
| “Privacidade por processamento local” como disrupção autônoma | maduro como princípio de arquitetura | medio | Reduz exposição de dados em certas implementações | Há política de processamento local documentada | Não determina sozinho retenção, finalidade ou acesso a outras fontes | [7], [10] | Condição de projeto e governança, não raiz |

Maturidade foi atribuída à capacidade delimitada, não a toda a categoria ou a todas as pessoas. Não se classificaram todos os wearables possíveis por ausência de evidência específica pertinente. Implantes, voz principal e metaverso genérico foram excluídos pela entrevista, sem simular revisão bibliográfica desses temas.

### Caminhos cortados e motivos

| Caminho proposto para contestação | Motivo do corte |
|---|---|
| Mais sensores → intenção conhecida com certeza | Sinais não identificam sozinhos finalidade ou autorização |
| Gestos menores → interface acessível a todos | Redução de amplitude não resolve diferenças de visão, controle motor e compreensão |
| Ajuda por etapa → maior aprendizagem → professor dispensável | Execução auxiliada não demonstra retenção nem transferência |
| Menos controles → menor custo de acesso | Custos podem migrar para sensores, suporte e assinaturas |
| Privacidade do olhar em uma plataforma → todas as aplicações espaciais protegem dados | Política particular não caracteriza outros fluxos ou fornecedores |
| Adoção nos EUA → disponibilidade e sucesso no Brasil | Distribuição, suporte, preço e contexto de uso exigem verificação própria |
| Interfaces corporais → fim do teclado até 2032 | Não há mecanismo nem evidência suficiente para substituição geral |

### Registro das buscas e das lacunas

| Busca ou leitura realizada | Resultado útil ou limite |
|---|---|
| `site.nature.com generic non-invasive neuromotor interface human computer interaction 2025` | Localizado artigo [1]; resultados comparativos lidos, sem inferir desempenho universal |
| `site.projectaria.com Aria Gen 2 contextual AI research 2025` | Localizada descrição técnica [3]; informação histórica de acesso não extrapolada para 2026 |
| `site.apple.com vision pro privacy eye tracking accessibility hands` | Localizada política [7]; usada com limite de fonte interessada |
| `site.meta.com neural band display glasses 2026 availability price 799` | Busca inicial não resolveu diretamente a fonte primária; busca posterior em `about.fb.com/news/2025/09/` encontrou [2] |
| Consultas sobre Display, pausa de expansão internacional e 2026 em `about.fb.com` | Não obtida confirmação primária atual suficiente de todos os mercados; planos históricos não contaram como expansão realizada |
| `"Meta Ray-Ban Display" "Brazil" availability September 2026` | Resultados misturaram modelos, anúncios e relatos; não estabelecida disponibilidade oficial atual do conjunto no Brasil |
| `"neuromotor" "interface" "independent" replication 2026 EMG` e consulta sobre EMG em uso real | Não localizada replicação independente suficiente da combinação completa nem retenção prolongada; ausência na busca não demonstra inexistência |
| Busca sobre assistência egocêntrica contextual em AR | Localizados [4] e [5]; limites de sensores e duração preservados |
| Consultas sobre TIC Domicílios e acesso por celular | Tabela J6A de 2025 apareceu no buscador, mas sua abertura falhou duas vezes; não entrou nas fontes nem nos números do mapa |
| Abertura do livro TIC Domicílios 2024 | Trecho do PDF acessível; utilizado como linha de base datada, sem chamá-lo de dado atual de adoção |
| Busca de kits EMG e abertura do tutorial SparkFun | Tutorial retornou 403; guia técnico em PDF [13] foi aberto e usado como alternativa |
| Consultas sobre disponibilidade de hardware e ferramentas | Não levantados estoque brasileiro, cotação completa do experimento ou licença atual de cada SDK; são pendências de execução, não fatos presumidos |

Páginas de busca e snippets ajudaram a localizar material, mas não foram adicionados à contagem de fontes como documentos lidos. Links duplicados, traduções e republicações não aumentaram a contagem. Documentos citados pelas fontes, mas não abertos nesta pesquisa, também não entraram.

### Contrassinais e hipóteses alternativas preservados

- Um botão convencional pode vencer por previsibilidade e baixo custo, mesmo quando a entrada muscular funciona tecnicamente.
- A orientação pode ficar em uma tela próxima à bancada; óculos só se justificam se o vínculo espacial reduzir esforço total.
- Assistência contextual pode produzir maior dependência de instruções, em vez de maior autonomia; o teste posterior é necessário.
- O uso pode crescer em procedimentos de treinamento e permanecer baixo em casa, por diferenças de custo, frequência e tolerância a preparação.
- Aplicações podem adotar apenas mãos e olhar, sem ganho suficiente para acrescentar EMG.
- Em algumas tarefas, a atividade muscular necessária para segurar objetos pode competir com os comandos; essa hipótese precisa de dados, não foi afirmada como falha universal.
- Um padrão aberto de ações e exportação de configuração pode reduzir e3.1; não se presumiu que surgirá ou que é impossível.
- Um modelo de assistência efêmero, sem histórico individual, pode interromper e5; auditoria e minimização precisam ser conciliadas no projeto.
- No Brasil, compartilhamento pode viabilizar acesso ou criar filas e desigualdade de prática. Não há resultado único implícito nessa modalidade de compra.
- Não se fez previsão de receita, participação de mercado, emprego perdido ou redução de custos: as fontes lidas não oferecem base suficiente para esses números no recorte definido.

### Condições para atualizar o mapa

Revisar R1 quando houver comparações independentes em tarefas reais, repetidas entre dias e com falhas por perfil. Revisar R2 quando a assistência for testada após interrupções, em procedimentos novos e sem depender de comando de voz. Retirar os ramos de expansão se suporte e uso recorrente não se sustentarem; aumentar confiança somente com evidência correspondente ao efeito, não com um lançamento isolado.

### Auditoria final do artefato

O arquivo contém 18 campos de frontmatter, 12 seções de nível `##`, duas raízes e seis efeitos em cada uma das três ordens. Os IDs continuam entre raízes e a terceira ordem não possui descendentes. A entrevista, os descartes, os mecanismos causais, as oito perguntas adversariais, um wildcard, três cenários distintos e os critérios falsificáveis do experimento estão preservados. As 14 fontes listadas foram abertas; a extensão da leitura e os limites de confiabilidade estão declarados individualmente.
