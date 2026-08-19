# ⚽ Corinthians — Análise de Desempenho com e sem Memphis Depay

## 📊 Sobre o projeto

Este projeto tem como objetivo analisar o desempenho do Sport Club Corinthians Paulista antes, durante e após a chegada de Memphis Depay, buscando identificar, através de dados, possíveis diferenças no desempenho da equipe quando o jogador esteve em campo e quando esteve ausente.

O período analisado começa na estreia de Memphis pelo Corinthians, em setembro de 2024, e se estende até agosto de 2026.

A análise utiliza dados das partidas do Corinthians e estatísticas individuais de Memphis Depay, permitindo comparar diferentes indicadores de desempenho da equipe.

> **Pergunta principal:** O Corinthians apresenta desempenho diferente quando Memphis Depay está em campo?

---

## 🎯 Objetivos

- Analisar o desempenho do Corinthians com e sem Memphis Depay;
- Comparar resultados em partidas com e sem a participação do jogador;
- Analisar indicadores ofensivos e defensivos;
- Avaliar a influência de Memphis nos resultados da equipe;
- Identificar possíveis padrões de desempenho;
- Criar indicadores e visualizações para facilitar a interpretação dos dados;
- Desenvolver um projeto completo de análise de dados para portfólio.

---

## 📅 Período analisado

**Início:** Setembro de 2024  
**Fim:** Agosto de 2026

O período começa a partir da estreia de Memphis Depay pelo Corinthians.

---

## 📚 Dados utilizados

### 🏟️ Dados das partidas

Para cada partida do Corinthians são coletadas informações como:

- ID da partida
- Data
- Temporada
- Competição
- Fase/Rodada
- Mandante
- Visitante
- Gols do mandante
- Gols do visitante
- Resultado do Corinthians
- Casa/Fora
- Tipo de jogo

### 📈 Estatísticas das partidas

Também são coletadas estatísticas de desempenho das equipes:

- Posse de bola
- Gols esperados (xG)
- Grandes chances
- Finalizações
- Defesas do goleiro
- Sprints
- Escanteios
- Faltas
- Passes
- Desarmes
- Tiros livres
- Cartões

### 👤 Estatísticas de Memphis Depay

Para as partidas em que houver dados disponíveis, serão analisadas:

- Minutos jogados
- Gols
- Assistências
- xG
- Finalizações
- Finalizações no alvo
- Chutes para fora
- Chutes bloqueados
- Dribles
- Dribles certos
- Passes certos
- Percentual de passes certos
- Passes decisivos
- Cruzamentos
- Bolas longas
- Perdas de posse
- Faltas sofridas
- Impedimentos
- Duelos ganhos
- Duelos no chão
- Duelos aéreos
- Desarmes
- Interceptações
- Cortes
- Nota SofaScore

---

## 🗂️ Estrutura dos dados

O projeto será dividido inicialmente em três conjuntos principais:

```text
📁 Corinthians-Memphis-Analysis
│
├── 📊 Partidas
│   └── Informações gerais de cada partida
│
├── 📈 Estatisticas_Partidas
│   └── Estatísticas do Corinthians e adversários
│
├── 👤 Estatisticas_Memphis
│   └── Estatísticas individuais de Memphis Depay
│
├── 🐍 Python
│   └── Tratamento e análise dos dados
│
├── 🗄️ SQL
│   └── Consultas e análises
│
├── 📊 PowerBI
│   └── Dashboard
│
└── README.md
