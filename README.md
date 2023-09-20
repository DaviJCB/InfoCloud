# Projeto Nimbus

---------------------------------------------------------------------------------------------------

# 🔮 O Propósito:
O propósito do sistema é criar uma página de histórico de dados que seja acessível tanto na web quanto em dispositivos móveis. Essa página irá exibir os dados coletados pela Nimbus de forma dinâmica, utilizando gráficos lineares, de barras e vetores, fazendo com que fique de mais fácil utilização para o usuário.

Esses gráficos serão interativos, assim como o mapa. Os usuários terão a opção de exportar os dados para formatos como CSV, PDF e PNG.

------------------------------------------------------------------------------

# 💻 Sobre o sistema:
## Quem usará o sistema?
Os usuários do sistema serão empresas ou pessoas que geralmente utilizam os dados em obras, áreas de meteorologia, estalagem, ou qualquer outro setor que necessite de cuidados. O maior índice de uso está em obras.

## Onde?
Os usuários que utilizarão o sistema poderão acessá-lo pela web ou pelo celular, seja de casa, na rua ou no trabalho. 

## Por que?
O sistema atualmente apresenta os dados de forma pouco intuitiva. Existe o desejo de aprimorar a plataforma em termos de desempenho, responsividade e usabilidade, além de permitir a exportação para CSV, PDF e PNG.

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
## 🔒 Requisitos funcionais:

- **RF-1:** O sistema receberá os dados que o usuário deseja filtrar através de um formulário. 
- **RF-2:** O sistema deve permitir acesso a página de acesso aos dados.
- **RF-3:** O sistema disponibilizará um mapa interativo com marcadores que representam os pontos de monitoramento disponíveis. 
- **RF-4:** O sistema deverá alterar as cores dos marcadores de acordo com os critérios de criticidade da estação.
- **RF-5:** O sistema deve ter uma tabela com dados filtrados pelo formulário.
- **RF-6:** O sistema deve ser capaz de exportar as tabelas e gráficos gerados em PDF, CSV e PNG.
- **RF-7:** O sistema apresentará gráficos, com base no tipo de dado selecionado.
- **RF-8:** O sistema deve permitir a seleção de mais de um ponto de monitoramento simultâneo.
- **RF-9:** O sistema deve manter um histórico de dados meteorológicos coletados ao longo do tempo para permitir a geração de gráficos de tendência.

## 🔓 Requisitos Não-Funcionais:

- **RNF-1:** O sistema deve fornecer resultados de pesquisa e atualizações de mapa e gráficos em no mínimo [tempo não definido ainda, mas idealmente 2 a 5 segundos].
- **RNF-2** O sistema deve ser capaz de fornecer atualizações de informações meteorológicas em tempo real com uma frequência mínima de [tempo não definido ainda, mas idealmente 15 a 30 minutos].
- **RNF-3:** A interface do sistema deve ser intuitiva e permitir que os usuários naveguem facilmente por ele, fazendo pesquisas e interações com os gráficos, tabelas e mapas de maneira ágil.
- **RNF-4:** Os textos, gráficos e mapas exibidos no sistema devem ser legíveis e de fácil compreensão, mesmo em dispositivos de diferentes tamanhos e resoluções
- **RNF-5:** O sistema deve ser igualmente acessível a computadores e dispositivos móveis, garantindo que a experiência seja consistente em diferentes plataformas.
- **RNF-6:** O sistema deve aderir a padrões de codificação para garantir a manutenibilidade e escalabilidade do código.
- **RNF-7:** O sistema deve estar disponível às 24 horas de todos os dias da semana.



