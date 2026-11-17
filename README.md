# Calculadora EcoTrip: Simulador de Impacto Ambiental

A Calculadora EcoTrip é uma aplicação web que simula o impacto ambiental em viagens terrestres. A ferramenta compara diferentes modais de transporte (Carro, Ônibus, Caminhão e Bicicleta), oferecendo uma análise visual clara sobre qual opção é mais ecológica, além de estimar o custo para compensação dessas emissões através de Créditos de Carbono.


## Desenvolvimento
Este projeto foi assistido por IA (GitHub Copilot) demonstrando as capacidades da ferramenta em um caso de uso prático.

Etapas: 
  - Criação rápida da estrutura HTML semântica e do CSS inicial;
  - Auxílio na implementação dos algoritmos de cálculo de emissão e conversão para créditos de carbono no arquivo calculator.js;
  - Sugestões para transformar código legado em ES6+ Moderno;
  - Geração de comentários JSDoc padronizados para todas as funções e objetos;
  - Sugestão de paletas de cores harmônicas e implementação de layouts responsivos com CSS Grid e Flexbox;
  - Criação do workflow de deploy automatizado para o GitHub Pages via GitHub Actions.

## Objetivos

O EcoTrip tem como objetivo conscientizar viajantes sobre o impacto invisível de seus deslocamentos. 

A aplicação permite:
  - Estimar a emissão exata de CO₂ baseada na distância e no veículo;
  - Visualizar a diferença de impacto entre Carro, Ônibus, Caminhão e Bicicleta.;
  - Traduzir a poluição gerada em métricas financeiras (Créditos de Carbono) para neutralização.

## Cálculo

A lógica matemática reside em 'js/calculator.js' e utiliza os seguintes fatores médios de emissão:

  - Modal de Transporte X Fator de Emissão (kg CO₂/km)
  - Bicicleta X 0.00 (Zero Emissão)
  - Ônibus X 0.089 (Por passageiro)
  - Carro X 0.120 (Médio a gasolina)
  - Caminhão X 0.960 (Diesel leve)

### Fórmula: Emissão Total = Distância (km) × Fator de Emissão





