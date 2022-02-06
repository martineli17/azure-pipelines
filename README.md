# Azure Pipelines
#### Estrutura para montar uma pipeline básica no Azure DevOps

## Como iniciar
- No portal do Azure DevOps, selecione o seu Projeto. Após isso, clique em Pipelines no menu lateral.
- Selecione a opção Pipelines
- Clique em 'New Pipeline'
- Selecione o local e o seu repositório

## Utilização de 'templates'
Templates, dentro do Azure Pipelines, são úteis para a criação de pipelines bases que podem ser compartilhadas entre várias outras pipelines, pois o seu código é igual e, normalmente, o que muda são apenas os valores a serem utilizados.

Sendo assim, utiliza-se os templates para evitar a duplicação de código e centralizar funcionalizades comuns em apenas um local.

## Utilização de Grupos de Variáveis
Grupos de Variáveis são usados para centralizar valores de variáveis utilizados nas pipelines e que podem ser utilizados em mais de uma pipeline.

É útil para evitar a repetição de variáveis e não expor os seus valores nas pipelines.

## Utilização de Environments
Environments são úteis para implementar regras mais especificamente em stages de deploys.

Por exemplo, pode-se implementar uma regra que para realizar o deploy é preciso de uma aprovação. Sendo assim, o deploy irá ser iniciado somente quando um usuário do Azure DevOps aprovar tal ação.
