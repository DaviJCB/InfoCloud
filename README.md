# Sobre a Empresa:
## Quem é a Nimbus Tecnologia?

A Nimbus Tecnologia é uma empresa especializada em monitoramento de condições climáticas em diversas situações. Composta por uma equipe de seis membros, a empresa atualmente atua nos mercados do Rio de Janeiro, São Paulo e Curitiba. Além disso, encontra-se em processo de expansão e possui uma parceria com o Centro de Operações do Rio de Janeiro. Seus clientes variam, atendendo tanto a empresas quanto a indivíduos, como engenheiros, meteorologistas ou qualquer pessoa interessada em acessar essas informações.

Essas empresas ou indivíduos utilizam os dados em diferentes setores, como construção, meteorologia, hospedagem e outros que necessitam de informações climáticas. A maioria das aplicações está relacionada à construção. Normalmente, os clientes utilizam os dados para prevenir acidentes ou atrasos em projetos, e a Nimbus oferece previsões que auxiliam no planejamento. A empresa também presta assistência direta no planejamento com base nos dados coletados.

Geralmente, as empresas buscam essas informações antes do início de um projeto ou quando surge a necessidade. Algumas empresas continuam a utilizar a plataforma mesmo durante a execução do projeto e, desde que o pagamento seja mantido, ela pode ser usada mesmo após a conclusão para fins de monitoramento.

A plataforma da Nimbus monitora principalmente a ocorrência de chuvas, o que ajuda na previsão e adoção de medidas preventivas. Além disso, a plataforma coleta dados meteorológicos, como informações de radares, e é capaz de prever eventos como raios. Ela também integra informações de estações meteorológicas e dados específicos relacionados ao projeto em andamento, oferecendo previsões e auxiliando na tomada de decisões.

A Nimbus utiliza a plataforma Cronos, que funciona como um ecossistema completo. Essa plataforma não apenas fornece informações climáticas de diferentes regiões, mas também se integra a programas de planejamento, permitindo que os clientes visualizem e planejem suas ações com base nos dados coletados. A plataforma é disponibilizada por meio de um modelo de assinatura mensal. O Cronos utiliza uma variedade de fontes de dados locais, apresentando as informações em uma página da web, embora ainda não tenha um aplicativo móvel. Para garantir a segurança, o Cronos emprega autenticação por login e senha, além de um token de segurança para validação de acesso.

---------------------------------------------------------------------------------------------------

# O Propósito:
O propósito do sistema é criar uma página de histórico de dados que seja acessível tanto na web quanto em dispositivos móveis. Essa página irá exibir os dados coletados pela Nimbus de forma dinâmica, utilizando gráficos lineares, de barras e vetores.

Esses gráficos serão interativos, assim como o mapa. Os usuários terão a opção de exportar os dados para formatos como CSV, PDF e PNG.

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
A Nimbus já possui um site por assinatura; no entanto, esse site só serve como uma página de login para ter acesso a download de suas informações. O desafio aqui é remodelar esse site, transformando-o em uma página mais fácil e intuitiva para o usuário, com mais de uma forma de disponibilizar os dados, com tabelas, gráficos e um mapa com marcadores georreferenciados, além de um formulário que servirá como filtro.

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
### Registro de usuário:
- **RU-1:** O sistema deve ser capaz de cadastrar os usuários na plataforma.
- **Ru-2:** O sistema deve permitir os usuários acessem suas contas.
- **RU-3:** O sistema deve permitir que seja cadastrado um cartão de Crédito/Débito válido. 
- **Ru-4:** O sistema deve ter a opção de alterar o cartão de crédito cadastrado
### Novo Histórico de dados:
- **NHD-1:** O sistema receberá os dados através de um formulário.
- **NHD-2:** O sistema deve permitir acesso a página de acesso aos dados.
- **NHD-3:** O sistema disponibilizará um mapa interativo com marcadores que representam os pontos de monitoramento disponíveis. 
- **NHD-4:** O Sistema deverá alterar as cores dos marcadores de acordo com os critérios de criticidade da estação.
- **NHD-5:** O sistema deve ter uma tabela com dados.
- **NHD-6:** O sistema deve ser capaz de exportar as tabelas geradas.
- **NHD-7:** O sistema apresentará gráficos, com base no tipo de dado selecionado.
### Plataformas Mobile:
- **PM-1:** O sistema deve ser igualmente acessível a computadores e dispositivos móveis.


## Requisitos Não-Funcionais:
### Desempenho: 
- **DE-1:** O sistema deve fornecer resultados de pesquisa e atualizações de mapa e gráficos em tempo hábil.

### Usabilidade: 
- **US-1:** A interface do sistema deve permitir que os usuários naveguem facilmente por ele, façam pesquisas e interajam com os gráficos, tabelas e mapas.
- **US-2:** Devem haver marcadores para cada ponto de monitoramento.
- **US-3:** Cores diferentes de pins devem ser usadas no mapa de acordo com os critérios de criticidade.
- **US-4:** Variáveis dos gráficos podem ser selecionadas para serem exibidas simultaneamente.
- **US-4:** O formulário deve ser de facil leitura
