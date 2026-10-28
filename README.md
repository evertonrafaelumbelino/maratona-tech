# 📊 Dashboard de Pesquisa: Gamificação no Aprendizado

Projeto desenvolvido para a 2ª Fase da Maratona Tech, Nível 3.
> Aluno autor/desenvolvedor: **Everton Rafael Umbelino dos Santos**

## 📌 Sobre o Projeto

Este repositório contém o Dashboard Interativo de Análise de Dados referente à pesquisa sobre  Gamificação no Aprendizado, criada para avaliar o impacto do uso de elementos e métodos gamificados (como pontuações, medalhas, níveis e rankings) na absorção de conteúdo e no engajamento dos estudantes.
O objetivo do Dashboard é transformar os dados brutos de 61 respondentes em visualizações dinâmicas e de fácil interpretação, permitindo filtrar por perfis demográficos, analisar métricas de foco e avaliar o suporte ao estudo tradicional.

## 🏆 Maratona Tech

A Maratona Tech é uma competição educacional focada em tecnologia e inovação, criada para incentivar estudantes a resolverem problemas reais por meio do uso de tecnologia, análise de dados e pensamento crítico.

- Fase: 2ª Fase
- Categoria/Nível: Nível 3

A competição abrange coleta de dados, estruturação de hipótese, análise qualitativa/quantitativa, criação de Dashboard visual para apresentação dos resultados e um vídeo sobre o projeto.

## 🎯 Pergunta Central e Hipótese

Pergunta Central da Pesquisa:

> "A gamificação no aprendizado é mais eficaz do que o método tradicional?"

Hipótese Inicial:

> "Estudantes que usam gamificação aprendem e focam mais do que os que utilizam métodos tradicionais."

Resultado & Veredito:

> Status: **Hipótese Parcialmente Comprovada**

A maioria dos respondentes demonstra forte preferência pelo formato gamificado e relata ganho direto em foco e motivação. No entanto, uma parcela significativa de alunos ainda rende melhor com métodos convencionais ou considera ambos equivalentes. A gamificação se provou um excelente complemento motivacional, e não uma substituição total dos métodos pedagógicos tradicionais.

## 🚀 Funcionalidades do Dashboard

- *Visualização Qualitativa:* Gráfico de rosca (Doughnut) comparando a preferência entre Aprendizagem Gamificada e Aprendizagem Tradicional.

- *Escala de Percepção:* Gráfico de barras indicando a nota atribuída pelos alunos quanto ao nível de ajuda que a gamificação proporciona no estudo (Escala 1 a 5).

- *Indicadores de Foco:* Cards numéricos indicando se o aluno sente ganho de foco (Sim, Talvez, Não).

- *Filtros Dinâmicos em Tempo Real:*
    - *Faixa Etária:* Jovem (0 a 19 anos) vs. Adulto (20 a 59 anos).
    - *Situação Estudantil:* Somente estuda vs. Trabalha e estuda.
    - *Nível de Experiência:* Iniciante, Intermediário e Avançado.

- *Análise e Parecer Técnico:* Seção dedicada à interpretação dos resultados com auxílio de análise preditiva/IA.

## 💻 Tecnologias Utilizadas

- HTML5 & CSS3: Estruturação semântica e estilização do painel.
- Tailwind CSS (via CDN): Framework de CSS utility-first para layout responsivo, moderno e limpo.
- JavaScript (ES6+): Lógica de manipulação de dados, atualização de DOM e gerenciamento dos filtros.
- Chart.js: Biblioteca interativa para geração dos gráficos de rosca e barras.
- FontAwesome: Ícones para aprimoramento da interface do usuário.

## 📂 Estrutura de Arquivos

```
.
├── dados.js         # Base de dados bruta com as 61 respostas da pesquisa
├── index.html       # Arquivo principal vinculada ao dados.js
└── README.md        # Documentação do repositório
```