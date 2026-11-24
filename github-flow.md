# GitHub Flow

## Os seis passos do GitHub Flow

1. **Criar uma branch:** criar uma nova linha de trabalho a partir da main para realizar alterações sem modificar o projeto principal.

2. **Fazer alterações:** editar os arquivos necessários dentro da branch criada.

3. **Fazer commits:** registrar as alterações realizadas, utilizando mensagens que expliquem o que foi modificado.

4. **Abrir um Pull Request:** solicitar que as alterações sejam revisadas antes de serem integradas à main.

5. **Revisar as alterações:** um colega analisa o trabalho, pode pedir correções com Request changes ou aprovar com Approve.

6. **Fazer o merge:** depois da aprovação, juntar as alterações da branch à main.

## Por que não editamos diretamente na main?

Não editamos diretamente na main porque ela é a branch principal do projeto. Trabalhar em branches separadas permite fazer alterações, corrigir erros e receber a revisão de outra pessoa antes de atualizar a versão principal.

## O que significam o vermelho e o verde no diff?

No diff, a cor vermelha representa as linhas que foram removidas ou substituídas, enquanto a cor verde representa as novas linhas adicionadas ao arquivo. Assim, conseguimos identificar facilmente o que mudou entre as versões.
