# Manutenir NCM

Fonte: https://athenas.atlassian.net/wiki/pages/2352447489
Atualizado: 2023-09-26T14:34:05.264Z

O código NCM é utilizado para fins de tributação e identificação do tipo de mercadoria. 
Caminho de Acesso
Portal: Altom.us
Caminho: Gerenciamento → Padões → NCM → Manutenir
Tela: A.0039.00
Descrição das Areas/campos da Tela
Clique na imagem para uma melhor visualização.
1 - Campo filtro
Permite aos usuários restringirem ou filtrarem os dados exibidos na Grid 2, com base em critérios específicos determinados por esta tela. Esses critérios podem ser inseridos nos campos de filtro pelo usuário manualmente, selecionando opções pré-definidas ou inserindo valores específicos em seus respectivos campos mostrados acima.
2 - Campo de resultados do filtro (1)
Exibe os resultados de um filtro aplicado a um conjunto de dados ou informações fornecidas no campo 1. As informações vem do banco de dados do TOS+.
3 - Campo de resultados da Grid 2
De acordo cem os resultados da Grid 1, o usuário pode carregar e pesquisar informações de um dado específico da Grid anterior.
4 - Botões de ação referentes ao filtro
Os botões de ação podem ser acionados quando alguma informação é cedida ao filtro.
O botão de ação PESQUISA pode ser acionado sem nenhuma informação cedida ao filtro. Feito isso, o sistema trará todas as informações referentes a esta tela.
5 - Botões de ação
Referentes as ações possíveis na Grid 2.
Incluir NCM

Alterar NCM

Excluir NCM

6 - Botões de ação que resultam informações na Grid 3.
Cada botão tem uma ação específica, representada nas imagens abaixo.
As ações mudam conforme a aba selecionada.
Aba Grupo NCM
Carregar dados do Grupo NCM

Cadastra Grupo NCM

Alterar Grupo NCM

Excluir Grupo NCM

Aba Propriedades 
Carregar Propriedades

Incluir Propriedades

Excluir Propriedades

Ações Possíveis
Na tela Manutenir NCM - A.0039.00 é possível 
Pesquisar/Filtrar NCM
Para encontrar um NCM, basta inserir as informações desejadas no campo de busca desta tela. Você pode realizar a pesquisa de forma específica, preenchendo os filtros disponíveis, ou de forma geral, deixando o filtro em branco e clicando no botão “PESQUISAR” para obter todas as informações pré-existentes na tela.
Cadastrar NCM
Preencha os campos, conforme descrição abaixo.

Clique no botão Incluir da Grid 2 (+).

obrigatórioRed 
Origem: Este campo refere-se à origem da carga. Escolha entre manifestado, novo lote, sobra e packing list.
Formato Tipo: Este campo indica o formato ou tipo da carga.
Tipo: Solta ou granel.
QTD: quantidade de unidades da carga.
PBM: sigla para Peso Bruto Máximo (Peso Bruto de Mercadorias). Este campo é utilizado para inserir o peso bruto máximo da carga do grupo de mercadorias. 
NCM: sigla para Nomenclatura Comum do Mercosul. Este campo é utilizado para inserir o código NCM que identifica a classificação fiscal da carga do grupo de mercadorias.
 O código NCM é utilizado para fins de tributação e identificação do tipo de mercadoria.
opcionalBlue 
Alterar Carga
Essa funcionalidade permite fazer modificações em uma carga existente no sistema TOS. Pode incluir a atualização de informações como peso, dimensões, status, destino, entre outros.
Basta selecionar a carga que deseja alterar e clicar no botão de ação "Alterar". Isso permitirá realizar as alterações desejadas no registro da carga selecionada.
Excluir Carga
Essa função permite remover uma carga específica do sistema TOS. É útil quando uma carga foi inserida erroneamente ou se tornou irrelevante para o sistema.
Importar Packing Lista
Essa funcionalidade permite importar uma lista de embalagens (packing list) para o sistema TOS. A lista geralmente contém informações sobre as embalagens, como número de contêineres, identificadores de carga, descrição da carga, quantidade, peso e outras informações relevantes. Importar essa lista facilita o registro das cargas no sistema.
Carregar dados do contêiner movimento
Essa funcionalidade permite carregar dados relacionados ao movimento de contêineres no sistema TOS. Pode incluir informações como número do contêiner, tipo de movimento (carga, descarga, transferência), data e hora do movimento, localização e outras informações relevantes.
Carregar cargas desovadas dado o contêiner movimento
Essa função permite carregar as informações das cargas desovadas de um determinado contêiner no sistema TOS. As cargas desovadas são as cargas retiradas de um contêiner específico. Essa funcionalidade pode envolver a atualização de informações relacionadas à carga no sistema, como status, destino, localização, entre outros.
Alterar quantidade prevista
A função de 'Alterar quantidade prevista de carga' permite realizar modificações na quantidade estimada de carga associada a um determinado item ou registro. Essa funcionalidade é útil quando ocorrem mudanças nas quantidades planejadas inicialmente, seja para aumentar ou reduzir a quantidade prevista. 
A carga precisa estar como tipo entrada.
Ao selecionar a carga desejada, o usuário pode acessar a opção de alteração e inserir a nova quantidade prevista, refletindo as atualizações necessárias. 
A quantidade prevista nova deve seguir as seguintes regras:
Se a quantidade prevista nova for maior do que a atual e a quantidade (qtd) for igual à quantidade prevista atual, não será possível salvar as alterações. Isso ocorre quando todo o lote já foi incluído, sendo permitido apenas marcar a carga como entrada, desde que o fluxo de carga não tenha sido fechado para contagem.

Se a quantidade prevista nova for menor do que a atual e essa nova quantidade prevista for menor ou igual à quantidade que já foi registrada (qtd), também não será possível salvar as alterações. Isso ocorre porque a quantidade prevista é menor do que a quantidade já registrada.

Essas restrições garantem a integridade dos registros, evitando inconsistências entre a quantidade prevista e a quantidade real da carga já registrada no sistema. É importante observar e respeitar essas regras ao realizar alterações na quantidade prevista de carga.
