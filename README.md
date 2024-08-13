# Análise de Séries Temporais

Este repositório oferece uma variedade de scripts e notebooks voltados para a análise de séries temporais. O propósito é disponibilizar uma coleção de métodos para:

Análise de Dados Temporais: Técnicas para explorar e interpretar séries temporais.
Ajuste de Modelos: Métodos para ajustar modelos estatísticos ou de aprendizado de máquina aos dados.
Previsão de Dados: Ferramentas para prever valores futuros com base em dados passados.


## Estrutura do Repositório

- **`01_analise_tendencia_linear/`**: Análise básica de uma série temporal com ajuste de tendência linear.
  - **Descrição**: Verifica a existência de uma tendência linear em uma série temporal simples, ajusta um modelo linear, calcula os parâmetros do modelo e faz uma previsão para valores futuros.
  - **Código**: 
    - Ajusta uma reta aos dados utilizando `optimize.curve_fit`.
    - Calcula os parâmetros \(b0\) (intercepto) e \(b1\) (inclinação).
    - Avalia a qualidade do ajuste através do erro médio quadrático (MSE).
    - Realiza uma previsão para o próximo valor da série.
  - **Visualizações**: Plota a série temporal original e a reta ajustada.
  
- **`02_analise_parabola/`**: Análise e ajuste de uma parábola (arquivo adicional).
  - **Descrição**: (Adicione uma breve descrição aqui após análise do código).
  - **Código**: (Inclua uma breve descrição das funções e cálculos realizados).
  - **Visualizações**: (Descreva os gráficos ou visualizações produzidos).

## Dependências

Este projeto requer as seguintes bibliotecas Python:

- `numpy`
- `matplotlib`
- `scipy`

