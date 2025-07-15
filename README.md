```markdown
# Painel Interativo de Análise Estratégica - Moendo Construções

## 1. Visão Geral do Projeto

Este projeto consiste em uma **Single-Page Application (SPA)** desenvolvida para visualizar de forma interativa os resultados de uma análise de negócios detalhada sobre a empresa **Moendo Construções**. A aplicação transforma um relatório estratégico estático em um painel de controle dinâmico e explorável, permitindo que os usuários consumam dados complexos, insights e recomendações de maneira intuitiva e eficiente.

O objetivo principal é facilitar a compreensão da posição estratégica da empresa, seu modelo de negócio dual, o cenário de mercado em que atua e suas oportunidades de crescimento.

## 2. Estrutura e Design da Aplicação

A SPA foi concebida como um painel de controle moderno, com uma arquitetura de informação que prioriza a usabilidade e a exploração não linear dos dados.

- **Navegação Fixa**: Uma barra lateral de navegação permite ao usuário alternar instantaneamente entre as principais seções da análise:
  - **Visão Geral**: Um dashboard com os KPIs e insights mais críticos.
  - **Modelo de Negócio**: Detalhes sobre a estrutura de dupla entidade (CNPJs).
  - **Análise de Mercado**: Gráficos sobre os vetores de crescimento do setor.
  - **Desempenho**: Análise da performance em licitações e lacunas operacionais.
  - **Estratégia**: Matriz SWOT interativa e recomendações estratégicas.

- **Design Responsivo**: A interface foi construída com **Tailwind CSS**, garantindo uma experiência de usuário consistente e funcional em desktops, tablets e dispositivos móveis.

- **Paleta de Cores**: Utiliza uma paleta de cores profissional e limpa, com tons neutros (**Slate**) e um destaque em verde-azulado (**Teal**) para elementos interativos e dados importantes, garantindo legibilidade e apelo visual.

## 3. Funcionalidades Interativas

A aplicação foi enriquecida com diversos elementos interativos para engajar o usuário e facilitar a absorção das informações:

- **Gráficos Dinâmicos**: Utiliza **Chart.js** para renderizar gráficos de barras que visualizam os principais vetores de crescimento do mercado, com *tooltips* informativos.
- **Alternância de Conteúdo**: Na seção "Modelo de Negócio", botões permitem ao usuário alternar a visualização das informações entre os dois CNPJs da empresa, facilitando a comparação direta.
- **Acordeão de Recomendações**: As recomendações estratégicas são apresentadas em um formato de acordeão (*accordion*), permitindo que o usuário expanda cada item para ler os detalhes, evitando sobrecarga de informação.
- **Navegação por Hash**: O roteamento da SPA é gerenciado via `window.location.hash`, permitindo a navegação entre seções sem recarregar a página e possibilitando o compartilhamento de links diretos para seções específicas.

## 4. Tecnologias Utilizadas

Este projeto foi construído com um conjunto de tecnologias web *front-end* padrão, sem a necessidade de um ambiente de compilação ou *build*.

- **HTML5**: Para a estrutura semântica do conteúdo.
- **Tailwind CSS (via CDN)**: Para a estilização responsiva e utilitária.
- **Chart.js (via CDN)**: Para a criação de gráficos interativos.
- **JavaScript (Vanilla JS)**: Para toda a lógica de interatividade, manipulação do DOM, gerenciamento de estado simples e roteamento.

## 5. Como Executar o Projeto

Como a aplicação é um arquivo HTML único e autocontido, não há necessidade de instalação de dependências ou de um servidor web.

- Basta abrir o arquivo `index.html` em qualquer navegador de internet moderno (como Google Chrome, Firefox, Safari ou Edge).

## 6. Fonte dos Dados

Todas as informações, dados, análises e conclusões apresentadas nesta aplicação são baseadas no relatório de análise estratégica fornecido sobre a **Moendo Construções**. A SPA serve como uma ferramenta de visualização para esse relatório.
```
