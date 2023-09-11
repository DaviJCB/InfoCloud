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
## Requisitos Funcionais:
-


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
