# InfoCloud
Quem?
Como?
Onde?
Por que?
Quando?
O que?
Nimbus tecnologia, é uma empresa voltada para o monitoramento de construção civil e de cidades.
Possui parceria com o Centro de Operações Rio.
Atua junto de várias obras, vias, lagos, eles monitoram para diminuir a ocorrência de chuvas.
São 6 membros, 4 sócios e 2 da equipe.
A plataforma absorve dados metereológicos como de radar, conseguem prever coisas como raios, dados de estações, dados das obras, com isso ele fornece previsão e ajuda na tomada de decisão, tudo isso ajuda no planejamento da obra.
Solução Cronos: Uma plataforma na web, faz previsão personalizada, faz histórico de dados.
Histórico de dados: Atualmente o histórico de dados armazenados no banco de dados são recuperados através de uma API e exportados.
Endpoint, ver dps sobre.
Desafio: Criar uma página mais robusta, que disponibilie esses dados nos formatos:
Tabelas
Gráficos (linear, barra, vetores)
Marcadores georreferenciados em um mapa.
Botões para exportação para CSV, PDF, PNG.
Interação entre os componentes
Adaptação para mobile.
A parte interessante do Front-End é pegar a requisição para levar a API.
Mapa interativo com marcadores para cada ponto de monitoramento ou estação.
Preenchimento de cor de acordo com criterios de criticidade.
Retorno do histórico de um ou mais pontos mediante a interaçõ com o marcador, seja utilizando polígonos para selecionar um ou mais pontos, seja através de um clique individual.
Gráficos devem ser dinâmicos, adaptando a frequencia temporal (eixo horizontal) e ordem de grandeza
Interagir com o gráfico e selecionar quais variaveis são exibidas simultaneamente.]
Apresentar uma otimização estetica em termos de desempenho, responsividade e intuitividae.
Os eixos se adaptarem no gráfico.
Apresentar uma otimização estética em termos de desempenho, responsiviade e intuitividade. Ser exportável para CSV e PDF.
Clientes: Empresas para empresas, dentro delas há setores que utilizam, dentro há engenheiros, meterologistas, pessoas singulares que utilizam.
Clientes no RJ, curitiba e SP, além de estar em expansão.
Clientes de obra não são feitos ainda, já tem aplicativos de planejamento, fazer a integração do aplicativo com os de planejamento, criando um ecossistema em que a nimbus faz parte.
É uma plataforma paga, usa um modelo de assinatura mensal que utiliza de vários dados para vários locais, com acesso.
Tem clientes que não necessarimente de obra, há estaleiros e mais diversificados, porém o foco principal é o mercado de obras.
O problema principal da tabela é que ela não é exibida no site, no caso a tabela deveria ter um design mais moderno.
Eles não tem o melhor do front-end, o back-end já tem bastante, eles focam mais na API.
Qualquer modernizaçaõ no sistema em front-end é bem vinda.
Como esses dados serão disponibilizados pra gente, para a verificação. dados mocados, dados fakes que usa para verificação, downloads, estações, entre outros, nada impede de ter outros endpoints no sistema, seriam dados fisícos e que não se mutam.
Quais plataformas o cronos roda: Hoje ele roda só web, eles não tem aplicativos mas eles tem demanda de clientes.
Sobre segurança: Eles tem um sistema de credenciamento, que utiliza de um token para segurança.
Formato de dados: Eles podem voltar como Json e dps retorna no formato de arquivos, porém eles podem fazer modificações para a forma json. As váriaveis das estações são diferentes, estações que só detectam chuva, ou sensor de rio que vê o nível do RJ, a lista de variaveis é bem extensa. Sensor diferente, medida diferente.
Não há tabela com as variáveis, eles vão criar uma tabela de variaveis, até passar terá um endpoint. Tem variaveis que eles nem utilizam como radiação solar, deve prever todas as variaveis, com a melhoria com a tabela aí serão enviados pra gente.
Não há documentação ms há um versionamento de sistema que é privado.
Quanto a criatividade, o céu é o limite.
primeiro será feita uma documentação, depois o projeto vai melhorando.
Pode perguntar qualquer coisa sobre meterologia, pq eles entendem que nós não temos informações sobre a base metereológica.
O que eles querem são ideias e conhecer a gente.
Teremos mais contatos com ele.
Endpoint é o endereço da API.
API faz conexões de arquivos diferentes.
Json: É um formato de arquivo de texto que é estruturado, vc transmite dados de forma estruturada que tem forma igual a um dicionário do Python.
Vamos fazer requisição.
O base é o protótipo funcional do que ele pediu, tudo será por pedaços.
https://cronos.nimbusmeteorologia.com.br/login
https://nimbusmeteorologia.com.br/
