# Meaghan Choi: Designing Claude Code (and what's coming next)

*[Read in English](en.md)*

> A design lead do Claude Code abre a cozinha: como ela vai da ideia ao protótipo, valida com stakeholders usando artefatos compartilháveis e leva o resultado até um PR.

| | |
|---|---|
| **Quem** | Meaghan Choi, Design Lead do Claude Code na Anthropic |
| **Onde** | Podcast Dive Club, com Michael Riddering (Ridd) |
| **Link** | https://www.youtube.com/watch?v=jEEbjiC4JE0 |
| **Duração** | ~54 min |
| **Assisti em** | 26/10/2026 |
| **Temas** | processo de design · prototipação · artefatos · design engineering · papel do designer |

## Resumo

- O trabalho do designer não diminuiu, **subiu de nível**: a execução vai para o modelo, o pensamento sobre forma e modelo mental do produto fica com a pessoa.
- **Artefatos** viraram o meio de prototipar, compartilhar e registrar decisões. Começaram como um improviso: as pessoas pediam HTML para o Claude e mandavam umas para as outras.
- O fluxo dela vai do pedido do time ao **artefato**, do artefato aos **componentes reais** e daí ao **PR**, sem a etapa tradicional de repasse para engenharia.
- Mais da metade do código que ela entrega hoje sai de **PRs iniciados pelo Claude**.
- A habilidade central do designer agora é **discernimento**: saber quando automatizar e quando parar para pensar fundo.

## Insights

### 1. Primeiro a forma, depois a tela

Antes de falar de interface, ela usa o Claude como parceiro de produto: traz pesquisa e dados e desenha o fluxo. A primeira pergunta pode ser se o produto precisa de uma UI.

**Por que importa:** o modelo executa uma ideia ruim sem questionar. Decidir a forma do produto e o modelo mental continua sendo trabalho do designer, e é o que dá valor ao resto.

### 2. Protótipo como link vivo, não arquivo estático

Em vez de mandar um arquivo que ninguém abre, ela compartilha um artefato: um link interativo, versionado, que o stakeholder usa como se fosse o produto. Ridd compara com mandar arquivo de Figma para executivos, que raramente abrem.

**Por que importa:** validação rápida depende de baixar o esforço de quem revisa. Um link que funciona no navegador gera feedback mais cedo e mais concreto.

### 3. Do artefato ao PR, num fluxo só

O fluxo que ela mostrou:

1. O time manda um pedido de feature.
2. Ela pede ao Claude um artefato com a proposta.
3. O time itera em cima do artefato.
4. Quando chega em média fidelidade, o Claude reconstrói usando os componentes reais e faz o *check-in* no repositório.
5. Vira um **pull request**, onde a revisão continua junto com engenharia.

**Por que importa:** o protótipo deixa de ser descartável. O que foi validado é o ponto de partida do código, e a conversa com engenharia acontece no PR.

### 4. O artefato também é registro de decisão

Ela pede 3 ou 4 variações, junta um resumo de pesquisa e dados e linka artefatos relacionados. Ela descreve isso como "quase um mini microsite e decision log".

**Por que importa:** qualquer pessoa consegue reconstruir *por que* a decisão foi tomada, não só *o que* foi decidido. Isso substitui parte da documentação que normalmente se perde.

### 5. Delegar a execução tática, com preferências salvas

Polimento de UI, limpeza de código e abertura de PR vão para o modelo. As preferências dela ficam salvas: PR em rascunho, prints de antes e depois, CI rodando. O Claude acompanha conversas no Slack e trabalho já mergeado, propõe mudanças e avisa quando o merge acontece. Ela também está construindo um revisor automático que checa princípios de design.

**Por que importa:** o que é repetitivo vira configuração. O tempo livre vai para problemas ambíguos, como explicar um Claude para a empresa inteira respeitando limites de segurança.

### 6. Respeitar o trabalho de engenharia

Às vezes ela empilha PRs de refinamento em cima do PR de uma pessoa engenheira, em vez de reescrever. Assim o trabalho original fica preservado.

**Por que importa:** designer que entrega código ganha confiança do time quando contribui sem passar por cima de ninguém.

### 7. Saber quando o craft importa

Trabalho experimental não precisa de polimento. O cuidado com acabamento vale mais quando a forma do produto já está definida. E a qualidade é responsabilidade do time: a ideia é facilitar para engenharia e produto identificarem problemas de qualidade e subir o nível juntos.

**Por que importa:** polir cedo demais desperdiça tempo em algo que ainda vai mudar.

### 8. Interfaces fixas e interfaces adaptativas

Login, cobrança e configurações continuam precisando ser estáveis. Outras partes podem se adaptar ao usuário. Cabe ao designer decidir o que fica fixo e o que muda.

### 9. Ferramenta certa para cada momento

Ela continua usando o Figma, com auto layout, quando iterar ali é mais rápido do que no código. A escolha é por velocidade, não por dogma.

### 10. O designer que vai se destacar

Ridd perguntou qual é o perfil do designer que vai ter sucesso no futuro. A primeira habilidade que ela citou não foi técnica: foi **ser aberto e curioso**.

Na prática:

- **Tenha ideias e desenvolva, mas solte quando precisar.** Se não funcionar ou se aparecer um jeito melhor, mude.
- **Atualize tudo o tempo todo:** a forma de pensar, o seu papel e o produto.
- **Se apoie na ambiguidade.** Entenda o que você quer, ache um ponto de partida e siga em frente, mesmo quando o caminho parecer caótico.

Ela completa com mais duas habilidades: discernimento para decidir o que construir e responsabilidade de ponta a ponta. E lembra que ainda estamos no começo, então quem está trabalhando agora ajuda a definir como vai ser.

**Por que importa:** com IA, as ferramentas e o jeito de trabalhar mudam a cada poucos meses. Esperar o cenário ficar claro para começar é ficar para trás.

## O que eu vou aplicar

- [ ] No próximo pedido de feature, mandar um protótipo em artefato (link interativo) em vez de prints ou arquivo estático.
- [ ] Gerar 3 variações da solução com um resumo do racional, e usar isso como registro da decisão.
- [ ] Quando o protótipo estiver validado, levar para o repositório com os componentes reais e abrir um PR em rascunho, com prints de antes e depois.
- [ ] Salvar minhas preferências de PR (rascunho, prints, checklist) num `CLAUDE.md` para não repetir sempre.
- [ ] Antes de abrir qualquer ferramenta, escrever a forma do produto e o modelo mental em poucas linhas.

## Trechos para revisitar

| Minuto | Assunto |
|---|---|
| 01:35 | Entrada na Anthropic e começo do Claude Code |
| 03:14 | Design para linha de comando (CLI) |
| 07:45 | O momento "mágico" e personalidade na ferramenta |
| 10:19 | Artefatos: prototipação, compartilhamento e decision log |
| 19:38 | Claude Tag: um Claude compartilhado pela organização |
| 27:56 | PRs iniciados pelo Claude |
| 31:53 | Delegar execução vs. pensar o design em alto nível |
| 38:48 | Desapegar do craft |
| 42:48 | Interfaces fixas vs. adaptativas |
| 46:53 | Novos desafios e o papel do designer |
