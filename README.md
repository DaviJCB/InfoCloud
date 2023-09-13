# Sobre a Empresa:
## Quem é a Nimbus Tecnologia?

A Nimbus Tecnologia é uma empresa especializada em monitoramento de condições climáticas em diversas situações. Composta por uma equipe de seis membros, a empresa atualmente atua nos mercados do Rio de Janeiro, São Paulo e Curitiba. Além disso, encontra-se em processo de expansão e possui uma parceria com o Centro de Operações do Rio de Janeiro. Seus clientes variam, atendendo tanto a empresas quanto a indivíduos, como engenheiros, meteorologistas ou qualquer pessoa interessada em acessar essas informações.

Essas empresas ou indivíduos utilizam os dados em diferentes setores, como construção, meteorologia, hospedagem e outros que necessitam de informações climáticas. A maioria das aplicações está relacionada à construção. Normalmente, os clientes utilizam os dados para prevenir acidentes ou atrasos em projetos, e a Nimbus oferece previsões que auxiliam no planejamento. A empresa também presta assistência direta no planejamento com base nos dados coletados.

Geralmente, as empresas buscam essas informações antes do início de um projeto ou quando surge a necessidade. Algumas empresas continuam a utilizar a plataforma mesmo durante a execução do projeto e, desde que o pagamento seja mantido, ela pode ser usada mesmo após a conclusão para fins de monitoramento.

A plataforma da Nimbus monitora principalmente a ocorrência de chuvas, o que ajuda na previsão e adoção de medidas preventivas. Além disso, a plataforma coleta dados meteorológicos, como informações de radares, e é capaz de prever eventos como raios. Ela também integra informações de estações meteorológicas e dados específicos relacionados ao projeto em andamento, oferecendo previsões e auxiliando na tomada de decisões.

A Nimbus utiliza a plataforma Cronos, que funciona como um ecossistema completo. Essa plataforma não apenas fornece informações climáticas de diferentes regiões, mas também se integra a programas de planejamento, permitindo que os clientes visualizem e planejem suas ações com base nos dados coletados. A plataforma é disponibilizada por meio de um modelo de assinatura mensal. O Cronos utiliza uma variedade de fontes de dados locais, apresentando as informações em uma página da web, embora ainda não tenha um aplicativo móvel. Para garantir a segurança, o Cronos emprega autenticação por login e senha, além de um token de segurança para validação de acesso.

---------------------------------------------------------------------------------------------------

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
Apesar de a empresa ter uma plataforma para disponibilizar seus dados, ela é pouco intuitiva e muito "básica", por assim dizer. Eles desejam uma otimização estética em termos de desempenho, responsividade e intuitividade, além de ser possível exportar para CSV e PDF. Dessa forma, a plataforma se tornaria mais atrativa para os usuários.

## Quando?
Geralmente, as empresas buscam os dados antes do início de uma obra ou quando necessário para o planejamento. Algumas empresas recorrem ao sistema durante a execução da obra, e, desde que a pessoa continue pagando, a plataforma pode ser usada mesmo após a conclusão para fins de monitoramento.

## O que?
A Nimbus já possui um site por assinatura; no entanto, esse site só serve como uma página de login para ter acesso a download de suas informações. O desafio aqui é remodelar esse site, transformando-o em uma página mais robusta, com mais de uma forma de disponibilizar os dados, com tabelas, gráficos e um mapa com marcadores georreferenciados, além de um formulário que servirá como filtro.

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

### Registro de usuários:
- **RU-1:** Os usuários devem ser capazes de se cadastrar na plataforma e acessar suas contas.
- **RU-2:** Os usuários devem fornecer um cartão de Crédito/Débito válido para que as cobranças sejam efetuadas corretamente. Eles também devem ter a opção de alterar o cartão de crédito posteriormente.

### Novo Histórico de dados:
- **NHD-1:** Os dados serão recebidos através de um formulário, o qual terá diversos critérios como: Período do histórico indicado pela data do ínicio e a data final, tipo de variável meteorológica, estação ou ponto de monitoramento, frequência (Frequência padrão ou em intervalo personalizado) e operação matemática utilizada (acumulado, média, máximo, mínimo).
- **NHD-2:** Os usuários devem ser capazes de acessar a página de acesso aos dados, onde encontrarão mais de uma forma de acessar as informações:
  1. Mapa: Um mapa interativo com marcadores que representam os pontos de monitoramento disponíveis. Os marcadores devem ter cores personalizadas de acordo com os critérios de criticidade da estação selecionada. Ao selecionar um marcadores, pode ver o histórico de um ou mais pontos selecionando-os com polígonos para escolher vários pontos ou simplesmente clicando em um ponto por vez.
  2. Tabela: A tabela deve apresentar uma otimização estética, melhorando sua visualização e compreensão, além de ser exportável para três outros tipos de arquivo (CSV, PDF E PNG).
  3. Gráficos: Os gráficos devem ser flexíveis, ajustando-se automaticamente à escala de tempo e à amplitude das variáveis com base no tipo de informação desejadas. Você pode interagir com o gráfico e escolher quais variáveis deseja ver ao mesmo tempo.

### Plataformas Mobile:
- **PM-1:** Além de boa performance para computadores, a página também deve ser funcional para dispositivos móveis.

### Suporte:
- **SP-1:** O sistema deve fornecer um suporte para os usuários, permitindo que eles obtenham assistência em caso de problemas, perguntas ou reclamações relacionadas ao serviço.


## Requisitos Não-Funcionais:
### Desempenho: 
- **DE-1:** O sistema deve ser altamente responsivo, fornecendo resultados de pesquisa e atualizações de mapa e gráficos em tempo hábil.

### Usabilidade: 
- **US-1:** A interface do usuário deve ser intuitiva e de fácil navegação, permitindo que os usuários naveguem facilmente pelo sistema, façam pesquisas e interajam com os gráficos, tabelas e mapas.
- **US-2:** Deve haver marcadores para cada ponto de monitoramento.
- **US-3:** Cores diferentes de pins devem ser usadas no mapa de acordo com os critérios de criticidade.
- **US-4:** Variáveis dos gráficos podem ser selecionadas para serem exibidas simultaneamente.
