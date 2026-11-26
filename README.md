# guia-de-revisao-git
Mini guia de revisão de Versionamento e Colaboração.

## Integrantes
- Aluno A: Vitor
- Aluno B: João

## O que tem aqui
- glossario.md: oito termos de versionamento
- github-flow.md: os seis passos do fluxo
- combinados.md: o dia de estudo da dupla

## Nossas respostas
### 1. O diff
No diff, as linhas em vermelho representam o conteúdo removido ou substituído, enquanto as linhas em verde representam o conteúdo adicionado. Ele permite comparar as alterações feitas entre diferentes versões de um arquivo.

### 2. O conflito
Um conflito acontece quando duas pessoas modificam o mesmo trecho de um arquivo de maneiras diferentes.`<<<<<<<` inicia a versão da branch do João, `=======` separa as duas versões e `>>>>>>>` indica o final da comparação com a main. Escolhemos manter terça e quinta-feira como dias de estudo da dupla, para atender a escolha de cada um

### 3. A revisão
O Vitor recebeu uma sugestão para acrescentar um exemplo na definição de merge. O João recebeu uma sugestão para explicar melhor as opções Request changes e Approve. Ambos fizeram as correções em suas branches e receberam aprovação. Request changes solicita alterações no trabalho e Approve aprova as mudanças após a revisão.

### 4. Segurança
Não. Mesmo que a informação seja apagada em um commit seguinte, ela pode continuar registrada no histórico do Git.
