# Dicas para fazer um bom README

# Instruções de criação do Readme para os repositórios

 ![DinoDance](https://static.wikia.nocookie.net/twitch/images/7/72/DinoDance.gif/revision/latest?cb=20230727015815)

<p>Cliente: (Nome do cliente para qual este projeto pertence. Se o projeto for da empresa colocar o cliente como BTI)</p>

## In a line - Fluxo da Aplicação:
<p>(Descrição em uma linha sobre a fluxo ou funcionalidade do projeto. Caso seja um projeto com mais de um fluxo ou objetivos, colocar uma descrição para cada fluxo.)</p>

* (Nome para o fluxo) - (Descrição)

<p>(Exemplo de uma projeto que tenha duas APIs:)</p>
* API Comunicação Banco - Verificar activities novas na umovme, recuperar dados e guardar no banco de dados.

* API Comunicação SAP - Verificar activities no banco de dados que ainda não foram integradas e então enviar para API colombo.
  

## Instruções de instalação:
<p>(Caso o projeto tenha instruções para instalações especificas, adicionar o passo a passo)</p>

* (Exemplo) Executar comando 'npm install' na raiz do projeto.

## Diretórios usados:
<p>(Caso o projeto tenha diretórios especificos utilizados, adicionar os nomes ou a organização das pastas)</p>

* (Exemplo) C:/BTI/nome_projeto - localização principal do projeto.

## Serviços:
<p>(Caso o projeto ultilize um serviço, ou mais, adicionar o nome e uma descrição de para o que é usado)</p>

* (Exemplo) BTI_DESCRICAO - Serviço usado para integrar X processo.

## Banco de Dados:
<p>(Caso o projeto tenha comunicação com um banco de dados, ou mais, adicionar as informações de comunicação)</p>

<p>Propietário banco: (Nome cliente ou BTI)</p>
<p>Tipo banco: (Exemplos: MySql, SqlServer, Postgres etc)</p>
<p>Nome banco de dados: </p>

### Tabelas/Views/Procedures
<p>(Se houver Tabelas usadas nesse projeto, descreve-las aqui. Se houver Viwes, descreve-las aqui, etc)</p>

* (Exemplo) Clientes - Dados cadastrais basicos dos clientes.


### APIs:
<p>(Caso o projeto tenha comunicação com uma API, ou mais, adicionar as informações de comunicação)</p>

#### (Exemplo) API - (Nome) - Lista de activity ID por data inicial: - GET request

<p>Url: (url usada)</p>
(Exemplo) Url: https://url{token cliente}/url{data inicial}&url={numero da pagina}

Exemplo de uso:
<p>(Caso queira acrescentar um exemplo de uso com informações utilizadas)</p>

Retorno API:
<p>(Mensagens de retorno dado pela API em caso de Sucesso)</p>
<p>(Caso queira acrescentar retorno dado pela API em caso de Erro que seja útil deixar documentado)</p>

## Desenhos/Diagramas etc
<p>*Se houver diagramas de bancos, desenhos de fluxo etc, podem ser adicionados a esta documentação também</p>

<p>(Caso deseje acrescentar mais alguma informação que acredite ser pertinente a documentação, pode ficar a vontade)</p>