# Sobre a Nimbus:
## 🏢 Quem é a Nimbus Tecnologia? 

A Nimbus Tecnologia é uma empresa especializada em monitoramento de condições climáticas, operando atualmente nos mercados do Rio de Janeiro, São Paulo e Curitiba, com planos de expansão. Seus clientes incluem empresas e indivíduos de diversos setores, como construção e meteorologia, que usam seus serviços para prevenir acidentes, atrasos em projetos e auxiliar no planejamento, com a plataforma Cronos como ferramenta principal. 

Além de monitorar chuvas e prever eventos climáticos, a Nimbus oferece dados detalhados e integra informações de estações meteorológicas, proporcionando suporte à tomada de decisões de seus clientes.

A plataforma Cronos não apenas fornece informações climáticas, mas também se integra a programas de planejamento, permitindo que os clientes visualizem e planejem suas ações com base nos dados coletados. Oferecida através de uma assinatura mensal, a plataforma garante a segurança dos dados com autenticação por login e senha, bem como um token de segurança para validação de acesso, embora ainda não disponha de um aplicativo móvel. 

Com isso, a Nimbus Tecnologia se destaca como uma empresa essencial para aqueles que dependem de informações climáticas precisas em suas atividades diárias.

---------------------------------------------------------------------------------------------------

# 🔮 O Propósito:
O propósito do sistema é criar uma página de histórico de dados que seja acessível tanto na web quanto em dispositivos móveis. Essa página irá exibir os dados coletados pela Nimbus de forma dinâmica, utilizando gráficos lineares, de barras e vetores, fazendo com que fique de mais fácil utilização para o usuário.

Esses gráficos serão interativos, assim como o mapa. Os usuários terão a opção de exportar os dados para formatos como CSV, PDF e PNG.

---------------------------------------------------------------------------------------------------

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
A Nimbus já possui um site por assinatura; no entanto, esse site só serve como uma página de login para ter acesso a download de suas informações. O desafio aqui é desenvolver uma nova página de histórico de dados, tornando-a uma página mais fácil e intuitiva para o usuário, com mais de uma forma de disponibilizar os dados, com tabelas, gráficos e um mapa com marcadores georreferenciados, além de um formulário que servirá como filtro.

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

--------------------------------------------------------------------------------------------

# 🖥️Casos de Uso:

## Caso de Uso: Emitir relatório

Ator Principal: Usuário

Outros Atores: <Nenhum>

Pré-condições: O usuário deve estar logado no sistema e estar na págna de histórico de dados.

Fluxo Básico:

[Passo 1]: O usuário define o local de monitoramento
[Passo 2]: O usuário insere o intervalo, definido por início e fim, no qual deseja receber os dados.
[Passo 3]: O usuário seleciona as variáveis meteorológicas desejadas.
[Passo 4]: O usuário seleciona o tipo de arquivo que deseja exportar, entre CSV, PDF OU PNG.

Fluxo Alternativo: <Nenhum>

Pós-condições: O relatório da ponto de monitoramento é emitido no formato desejado pelo usuário e com as variáveis de sua preferência.

