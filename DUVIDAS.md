# DUVIDAS — onde a IA errou

## Onde a IA errou

Durante a auditoria do mapa, identifiquei um excesso real de classificação. A IA classificou **hand tracking isolado para seleção** como uma capacidade “madura para repertórios delimitados”, mas as fontes reunidas não eram suficientes para sustentar essa conclusão com o grau de certeza apresentado.

### 1. O que foi afirmado

No levantamento de candidatos, o hand tracking foi classificado como:

> “maduro para repertórios delimitados”.

A classificação se apoiava principalmente na documentação da Apple sobre interação com olhos e mãos e na documentação do OpenXR.

### 2. Por que a afirmação parecia convincente

A formulação parecia plausível porque hand tracking já aparece em produtos comerciais e possui suporte em infraestrutura padronizada de XR. Além disso, a expressão “para repertórios delimitados” parecia restringir suficientemente a afirmação.

No entanto, disponibilidade comercial e existência de APIs não são, por si só, evidências suficientes para comprovar todos os critérios de maturidade definidos pela própria skill.

### 3. O que mostrou o problema

Ao reler as fontes, percebi que elas sustentavam principalmente dois pontos:

* a Apple demonstra que interações com mãos estão disponíveis em seu ecossistema e descreve como esses dados são tratados;
* a Khronos demonstra que OpenXR oferece infraestrutura padronizada para capacidades de XR.

Essas fontes, porém, não demonstravam de forma suficiente, dentro do levantamento realizado, utilização repetível em diferentes tarefas reais, estabilidade operacional ou adoção consolidada nos usos delimitados considerados no mapa.

O erro foi transformar **disponibilidade comercial e padronização** em evidência suficiente de **maturidade operacional**.

### 4. Como a classificação deveria ser corrigida

Uma formulação mais adequada seria:

> “Hand tracking para seleção: capacidade comercialmente disponível e suportada por infraestrutura XR. A maturidade operacional nos usos delimitados não foi suficientemente demonstrada pelas fontes reunidas; a classificação permanece condicionada a evidências de uso repetido, desempenho e estabilidade nessas tarefas.”

Isso não significa que hand tracking seja necessariamente imaturo. Significa apenas que a pesquisa realizada não forneceu evidência suficiente para apresentar sua maturidade como estabelecida.

Também não significa que ele deva ser promovido a disrupção-raiz. A correção da classificação de maturidade não altera automaticamente seu potencial de ruptura.
