![image](https://github.com/DaviJCB/InfoCloud/assets/102532061/cd99fc70-a7c1-49fb-bb90-627a288033ff)


# Projeto Nimbus ☁️

O **Projeto Nimbus** é uma plataforma moderna e intuitiva para visualização de dados meteorológicos históricos e em tempo real. Desenvolvido com foco em usabilidade e performance, o sistema atende desde o planejamento de obras até o monitoramento ambiental contínuo.

[Sobre a Nimbus](https://github.com/DaviJCB/InfoCloud/blob/main/Nimbus.md)

---

# 🔮 O Propósito
O sistema funciona como uma central de histórico de dados acessível via web e dispositivos móveis. A interface utiliza **design glassmorphism** e temas escuros modernos para exibir dados de forma dinâmica através de:
- **Gráficos Interativos**: Lineares, de barras e vetores para facilitar a análise.
- **Mapa Georreferenciado**: Visualização espacial dos pontos de monitoramento.
- **Tabelas de Dados**: Listagem detalhada com opções de filtragem.

Os usuários podem exportar as informações em formatos como **CSV**, facilitando a integração com outras ferramentas de análise.

---

# 💻 Sobre o Sistema

## Quem usará o sistema?
Empresas e profissionais dos setores de construção civil, meteorologia, logística e qualquer outro setor que dependa de condições climáticas para operações seguras. O setor de obras é o principal utilizador para planejamento e execução.

## Onde?
Acesso universal via **Web** ou **Mobile**, permitindo o acompanhamento de casa, no escritório ou diretamente no campo de trabalho.

## Por que?
Para transformar dados meteorológicos complexos em informações intuitivas, melhorando a tomada de decisão, a segurança operacional e o cumprimento de cronogramas.

## O que?
Uma evolução da plataforma original da Nimbus, oferecendo uma experiência intuitiva com:
- **Filtros Avançados**: Formulário para seleção de datas e variáveis.
- **Visualização do Mapa**: Pontos de monitoramento georreferenciados.
- **Exportação Flexível**: Download de dados para uso externo.

## Quais dados?
O sistema integra múltiplas fontes para geração de insights:
- Dados de Radares e Raios.
- Informações de Estações Meteorológicas.
- Localização precisa de obras e pontos de monitoramento.

---

# Elicitação

## 🔒 Requisitos Funcionais (RF)
- **RF-1:** Filtragem de dados via formulário (início, fim e variáveis).
- **RF-2:** Página dedicada de visualização de histórico.
- **RF-3:** Mapa interativo com marcadores de pontos de monitoramento.
- **RF-4:** Visualização de criticidade através de cores nos marcadores (em desenvolvimento).
- **RF-5:** Tabela dinâmica com dados filtrados.
- **RF-6:** Exportação de dados (CSV implementado; PDF/PNG em planejamento).
- **RF-7:** Geração de gráficos baseados no tipo de dado selecionado.
- **RF-8:** Histórico completo de dados meteorológicos para análise de tendências.

## 🔓 Requisitos Não-Funcionais (RNF)
- **RNF-1:** Carregamento de dados e mapas em tempo otimizado (idealmente < 5s).
- **RNF-2:** Interface responsiva e legível em desktops e dispositivos móveis (**Mobile First**).
- **RNF-3:** Design intuitivo com foco em acessibilidade e rapidez operacional.
- **RNF-4:** Alta disponibilidade (24/7) para suporte a operações críticas.

---

# 🖥️ Tecnologias Utilizadas

## Frontend
- **React + Vite**: Base do aplicativo para rapidez e modularidade.
- **Vanilla CSS**: Sistema de design personalizado com variáveis CSS e Glassmorphism.
- **Leaflet.js**: Motor de mapa robusto e gratuito (OpenStreetMap).
- **Chart.js**: Biblioteca para geração de gráficos estatísticos.
- **React Table**: Manipulação eficiente de grandes volumes de dados em tabelas.

---

# 👨‍💻 Equipe (Integrantes)
- **Matheus Peçanha**: Exportação, CSS da Tabela e Home Page.
- **Daniel Studart**: Componente do Mapa, Página Sobre Nós, Formulário e Integração de Dados.
- **Daniel Alves**: Design do Gráfico, Responsividade e Casos de Uso.
- **João Paulo Dopcke**: Lógica do Gráfico, Filtros e Exportação.
- **Davi Jacob**: Componente de Tabela e Lógica de Exportação.

![image](https://github.com/DaviJCB/InfoCloud/assets/102532061/72555e25-1c75-4aa3-b4bc-baac5dc60269)

---
[Código Fonte](https://github.com/Studart7/InfoCloudApp) | [Trello do Projeto](https://trello.com/b/PrIZWpYP/front-end)
