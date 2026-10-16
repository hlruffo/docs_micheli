# Manutenir Sensor

Fonte: https://athenas.atlassian.net/wiki/pages/2371026945
Atualizado: 2023-11-08T10:25:27.159Z

Caminho de acesso
Portal: Altom.us 
Caminho: Gerenciamento → Processos → Operacionais → Dashboard → Sensor →  Manutenir
Tela: A.0092.00
Manutenir Sensor - A.0092.00
Descrição das áreas/campos da Tela
Clique na imagem para uma melhor visualização.
1 - Campo filtro
Permite aos usuários restringirem ou filtrarem os dados exibidos na Grid 2, com base em critérios específicos determinados por esta tela. Esses critérios podem ser inseridos nos campos de filtro pelo usuário manualmente, selecionando opções pré-definidas ou inserindo valores específicos em seus respectivos campos mostrados acima.
1, 2 e 3 - Painéis de resultados
Estes painéis apresentam os resultados com base na sua interação na tela. O painel 2 exibe registros após a aplicação de filtros, enquanto os painéis 3 e 4 mostram resultados após o carregamento de dados, sempre que houver interação.
5 - Botões de ação referentes ao filtro
Os botões de ação podem ser acionados quando alguma informação é cedida ao filtro.
O botão de ação PESQUISA pode ser acionado sem nenhuma informação cedida ao filtro. Feito isso, o sistema trará todas as informações referentes a esta tela.
6, 7 e 8 - Botões de ação
Refentes as ações possíveis nas Grids 6, 7 e 8.
Incluir Sensor

Alterar Sensor

Excluir Sensor

Compilar Sensor

Mudar Estado do Sensor

Silenciar Sensor

Carregar dados

Incluir Sensor Mensagem

Alterar Sensor Mensagem

Excluir Sensor Mensagem

Carregar dados de disparo do Sensor.
Ações Possíveis
Na tela  Manutenir Sensor - A.0092.00 é possível
Pesquisar/Filtrar Sensor

Cadastrar Sensor

Alterar Sensor

Excluir Sensor

Compilar Sensor

Alterar Estado do Sensor

Silenciar Sensor

Carregar dados de Sensor Mensagem

Cadastrar Sensor Mensagem

Alterar sensor Mensagem

Excluir Sensor Mensagem

Carregar dados de Disparo

Pesquisar/Filtrar Sensor
Para encontrar um Sensor, basta inserir as informações desejadas no campo de busca desta tela. Você pode realizar a pesquisa de forma específica, preenchendo os filtros disponíveis, ou de forma geral, deixando o filtro em branco e clicando no botão "PESQUISAR" para obter todas as informações pré-existentes na tela.
Cadastrar Sensor
Para efetuar o cadastro de um sensor com sucesso, é fundamental ter um entendimento sólido sobre fórmulas, condições e outros indicadores necessários para o correto funcionamento do sensor.  
Para obter informações detalhadas, consulte nosso manual no módulo Dashboard em →
https://athenas.atlassian.net/wiki/spaces/2C/pages/2257747995/Manual+TOS+Sensores+Medidas+e+Indicadores#7.-Sensores-e-Disparos
Preencha os campos, conforme descrição abaixo.

Clique no botão Incluir na Grid 2 (+).

Clique em Ok e as informações serão salvas no banco.
obrigatórioRed 
Indicador: Digite o indicador desejado. Por exemplo: SAÍDA CARGA.
Nome: Insira um nome descritivo para o sensor. Por exemplo: SENSOR DE AVARIA SA MERC.
Efeito: Escolha entre “Negativo” ou “Positivo”, dependendo do efeito que o sensor representa.
Grau: Selecione um grau conforme a situação do sensor.
Estado: Escolha entre “Inativo” ou “Ativo” para indicar o estado atual do sensor.
Fórmula: Insira a fórmula que descreve como o sensor calcula seu indicador. Por exemplo: AV*100/(CH+VZ+CGSLT+GERAL+ARMZGM+DPT)
opcionalBlue 
Condições: Descreva as condições que devem ser atendidas para o sensor ativar ou disparar alertas. Por exemplo: A>85, M>70, D>50, N>50.
Descrição: Forneça uma descrição detalhada do indicador monitorado pelo sensor. Por exemplo: PERCENTUAL DE AVARIAS PARA SAÍDA DE MERCADORIA.
Alterar Sensor
Encontre o registro do sensor que deseja modificar. Utilize o campo de filtro para facilitar a busca.

Após localizar o registro do sensor que deseja alterar, clique sobre ele para selecioná-lo.

Localize e clique no botão “ALTERAR” para iniciar o processo de alteração.

O formulário de edição será aberto, e os campos estarão disponíveis para edição. Faça as modificações necessárias nos campos conforme desejado.

Clique em Ok e as informações serão salvas no banco.
Excluir Sensor
Localize o registro do sensor que deseja excluir. Utilize o campo de filtro para facilitar a busca.

Após localizar o registro do sensor que deseja excluir, clique sobre ele para selecioná-lo.

Clique no botão “EXCLUIR” ou na opção equivalente para iniciar o processo de exclusão.

Após a confirmação, o sensor será excluído permanentemente do sistema.

Compilar Sensor
Compilar um sensor é um procedimento importante que permite atualizar e reavaliar o sensor com base nas informações mais recentes. Isso é crucial para manter o sensor funcionando corretamente e gerando resultados precisos.
Localize o registro do sensor que deseja compilar. Clique sobre esse registro para selecioná-lo.

Após selecionar o sensor desejado, clique no botão de ação "COMPILAR".

Aguarde o Processo de Compilação: O sistema iniciará o processo de compilação do sensor. Esse processo envolve a reavaliação das informações e fórmulas associadas ao sensor, garantindo que esteja atualizado e pronto para fornecer resultados precisos.

Compilar um sensor é fundamental para manter seu desempenho ótimo e garantir que os resultados refletem com precisão a situação atual. Isso é especialmente importante em ambientes em constante mudança, onde os dados e as condições podem variar com o tempo. Portanto, realizar a compilação periodicamente é essencial para obter informações confiáveis a partir do sensor.
Alterar Estado do Sensor
Para alterar o estado de um sensor de “Ativo” para “Inativo” ou vice-versa, siga estes passos:
Localize o registro do sensor que deseja modificar. Clique sobre o registro para selecioná-lo.

Após selecionar o sensor desejado, clique no botão “MUDAR ESTADO”.

O sistema processará a solicitação e retornará o sensor com o estado oposto ao anterior, ou seja, se estava “Ativo”, agora estará “Inativo”, e vice-versa.

Silenciar Sensor
Para silenciar um sensor siga este processo:
Encontre o registro do sensor que você deseja silenciar. Clique sobre o registro para selecioná-lo.

Após selecionar o sensor desejado, clique no botão “SILENCIAR”.

O sistema irá solicitar uma confirmação para garantir que você deseja silenciar realmente o sensor.

Confirme a ação e o sensor será silenciado durante o período especificado.

Essa funcionalidade é útil quando você precisa interromper temporariamente as notificações ou alerta de um sensor sem desativá-lo permanentemente. Certifique-se de definir o tempo de silenciamento apropriado para suas necessidades.
Carregar dados de Sensor Mensagem
Para obter os dados de mensagens/eventos do sensor, siga as etapas abaixo:
Primeiro, localize e selecione o registro de sensor o quela deseja visualizar as informações na grid 2.

Role a tela para a grid 3 e clique no botão de ação ‘Carregar’.

O sistema fornecerá dados de Tipo Evento e Hora do sensor selecionado na grid 2.

Cadastrar Sensor Mensagem
Na segunda Grid(Sensor), encontre o registro ao qual deseja associar o sensor mensagem. Selecione esse registro.

Na Grid 3(Sensor Mensagem), clique no botão de ação 'Incluir' (+) para adicionar o sensor mensagem.

Um formulário aparecerá na tela, preencha os campos conforme as especificações abaixo:

Tipo Evento: Selecione o tipo de evento que deve ser previamente cadastrado. Para obter informações sobre como cadastrar um evento, consulte os manuais em → Manual de Configuração para Envio de Mensagem  e Manutenir Evento .

Defina as Horas: Especifique o tempo em horas antes do envio da mensagem. Se a hora for definida como NULA, a mensagem será enviada imediatamente. Se o alarme estiver ligado, a mensagem será enviada após x horas, de acordo com a configuração. Você pode definir 0 para enviar a mensagem imediatamente.

Clique em OK para salvar o Sensor Mensagem.
Alterar sensor Mensagem 
Para modificar as informações de um sensor mensagem, siga este procedimento:
Nota Importante: Certifique-se de que a Grid 3(Sensor Mensagem) já contenha os registros de sensores mensagem para poderem ser editados. Siga as etapas descritas no tópico "CARREGAR DADOS DE SENSOR MENSAGEM" neste manual.
Após carregar os dados na Grid 3, siga as instruções abaixo:
Localize o sensor mensagem na Grid 3 que você deseja editar e clique no botão de ação "Alterar".

Uma janela pop-up será aberta, permitindo a modificação dos dados relacionados ao Tipo de Evento e Horas.

Nesta janela, efetue as alterações desejadas nos campos do Tipo de Evento e Horas, de acordo com as necessidades.

Clique em OK para salvar as alterações no Sensor Mensagem.
Excluir Sensor Mensagem
Para excluir um registro de sensor mensagem, siga este processo:
Nota Importante: Certifique-se de que a Grid 3 contenha os registros de sensores mensagem que podem ser excluídos. Siga as etapas descritas no tópico "CARREGAR DADOS DE SENSOR MENSAGEM" neste manual.
Após ter carregado os dados na Grid 3, siga as etapas a seguir para excluir um registro:
Localize Na Grid 3, encontre o registro de sensor mensagem que você deseja excluir.

Clique no botão de ação "Excluir".

Após a confirmação, o registro de sensor mensagem será excluído permanentemente.

Carregar dados de Disparo 
Para carregar informações de disparo, siga este processo:
Certifique-se de que na Grid 2 Sensores) você tenha o registro do sensor desejado selecionado. Use a função de filtro, se necessário, para localizar o registro específico.

Após encontrar o registro do sensor desejado, clique sobre ele para selecioná-lo.

Agora, vá para a Grid 4 (Disparo), onde você encontrará o botão de ação "Carregar".

Clique sobre o botão "Carregar", e as informações, como Ocorrências, Métrica de Evento e Métrica Derivada, serão exibidas.
