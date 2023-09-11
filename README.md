# O Propósito:
O propósito do sistema é criar uma página que seja acessível tanto na web quanto em dispositivos móveis. Essa página irá exibir os dados coletados pela Nimbus de forma dinâmica, utilizando gráficos lineares, de barras e vetores.

Esses gráficos serão interativos, permitindo ao usuário escolher quais variáveis deseja visualizar simultaneamente. Além disso, haverá um mapa interativo com marcadores para cada ponto de monitoramento e estações.

A página também utilizará preenchimento de cor para destacar a criticidade de cada critério, facilitando a visualização. Os usuários terão a opção de exportar os dados para formatos como CSV, PDF e PNG.

Além disso, a interação entre os componentes será facilitada, e os usuários poderão acessar o histórico completo de dados através da interação com os marcadores no mapa. Isso pode ser feito através de cliques individuais em cada parte ou desenhando polígonos para selecionar pontos no mapa.

---------------------------------------------------------------------------------------------------

# Sobre o sistema:
## Quem usará o sistema?
Os usuários do sistema serão empresas ou pessoas que geralmente utilizam os dados em obras, áreas de meteorologia, estalagem, ou qualquer outro setor que necessite de cuidados. O maior índice de uso está em obras.

## Onde?
Os usuários que utilizarão o sistema poderão acessá-lo pela web ou pelo celular, seja de casa, na rua ou no trabalho. 

## Por que?
O sistema mostrará dados que poderão ser usados para o planejamento de uma obra ou a continuidade de uma já existente, permitindo aproveitar as condições climáticas a favor.

## Quando?
Geralmente, as empresas buscam os dados antes do início de uma obra ou quando necessário para o planejamento. Algumas empresas recorrem ao sistema durante a execução da obra, e, desde que a pessoa continue pagando, a plataforma pode ser usada mesmo após a conclusão para fins de monitoramento.

## O que?
O sistema combina um mapa interativo com gráficos que exibem diferentes dados. Esses dados podem ser visualizados através de um único clique ou selecionando pontos no mapa usando polígonos.

## Como?
O sistema requer uma assinatura mensal. O usuário se cadastra e, em seguida, pode fazer login. O sistema estará disponível para acesso na web e pode ser acessado sempre que o usuário desejar.

## Quais dados?
O sistema absorve múltiplos tipos de dados para gerar suas previsões, incluindo:
- Dados de Radares
- Dados de raios
- Dados de estações
- Localização da obra em questão

--------------------------------------------------------------------------------------------

# Elicitação:
## Requisitos funcionais:

Registro de usuários:
- RU-1: Os usuários devem ser capazes de se cadastrar na plataforma e acessar suas contas.
- RU-2: Registrar cartão de crédito/Alteração de cartão: Os usuários devem fornecer um cartão de Crédito/Débito válido para que as cobranças sejam efetuadas corretamente. Eles também devem ter a opção de alterar o cartão de crédito posteriormente.

Novo Histórico de dados:
- NHD-1: Formulário: Os dados serão recebidos através de um formulário, o qual terá diversos critérios como: Período do histórico indicado pela data do ínicio e a data final, tipo de variável meteorológica, estação ou ponto de monitoramento, frequência (Frequência padrão ou em intervalo personalizado) e operação matemática utilizada (acumulado, média, máximo, mínimo).
- NHD-2: Disponibilização dos dados: Os usuários devem ser capazes de acessar a página de acesso aos dados, onde encontrarão mais de uma forma de acessar as informações:
  1. Mapa: Um mapa interativo com marcadores que representam os pontos de monitoramento disponíveis. Os marcadores devem ter cores personalizadas de acordo com os critérios de criticidade da estação selecionada. Ao selecionar um marcadores, pode ver o histórico de um ou mais pontos selecionando-os com polígonos para escolher vários pontos ou simplesmente clicando em um ponto por vez.
  2. Tabela: A tabela deve apresentar uma otimização estética, melhorando sua visualização e compreensão, além de ser exportável para três outros tipos de arquivo (CSV, PDF E PNG).
  3. Gráficos: Os gráficos devem ser flexíveis, ajustando-se automaticamente à escala de tempo e à amplitude das variáveis com base no tipo de informação desejadas. Você pode interagir com o gráfico e escolher quais variáveis deseja ver ao mesmo tempo.

Plataformas Mobile:
- PM-1: Além de boa performance para computadores, a página também deve ser otimizada e funcional para dispositivos móveis.

Suporte:
- SP-1: O sistema deve fornecer um suporte para os usuários, permitindo que eles obtenham assistência em caso de problemas, perguntas ou reclamações relacionadas ao serviço.


## Requisitos Não-Funcionais:
### Desempenho: 
- DE-1: O sistema deve ser altamente responsivo, fornecendo resultados de pesquisa e atualizações de mapa e gráficos em tempo hábil.

### Usabilidade: 
- US-1: A interface do usuário deve ser intuitiva e de fácil navegação, permitindo que os usuários naveguem facilmente pelo sistema, façam pesquisas e interajam com os gráficos, tabelas e mapas.
- US-2: Deve haver marcadores para cada ponto de monitoramento.
- US-3: Cores diferentes de pins devem ser usadas no mapa de acordo com os critérios de criticidade.
- US-4: Variáveis dos gráficos podem ser selecionadas para serem exibidas simultaneamente.

### Exportação de Dados: 
- ED-1: Deve permitir que os usuários exportem dados para CSV e PDF de maneira rápida e confiável, mantendo a formatação adequada.
