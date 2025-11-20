# GS2_Solucoes-_Em_Energias_Renovaveis_E_Sustentaveis

feito por: Leticia Giordani villegas - RM564028, Sarah Sayako Trolezi - RM563841 1CCR e Giovanna Aparecida Gonçalves Pavesi Botero - RM562018 1CCPQ

# Sistema de Dimensionamento de Energia Solar Residencial 
Descrição do Projeto
Este projeto utiliza Machine Learning para dimensionar sistemas de energia solar fotovoltaica de forma inteligente e precisa. O sistema analisa o consumo energético, área disponível e irradiação solar local para recomendar o tamanho ideal de um sistema solar, além de calcular economia financeira e impacto ambiental.
Ele tem o objetivo de incentivar pessoas a adiquirirrem uma placa solar, seja pela diminuição na conta de energia ou pelo impacto ambiantal

# Funcionalidades

Dimensionamento Inteligente: Usa algoritmos de Machine Learning (Random Forest e Regressão Linear) para prever o tamanho ideal do sistema solar
Análise Financeira Completa: Calcula investimento inicial, economia mensal/anual e tempo de retorno (payback)
Impacto Ambiental: Estima a redução de emissões de CO₂ e equivalência em árvores plantadas
Visualização de Dados: Gráficos de predição vs realidade e distribuição de erros
Validação Cruzada: Garante a confiabilidade das predições através de cross-validation

# Como Usar
**Defina seus parâmetros no Main()**
```
consumo_mensal = 500  # kWh/mês
area_disponivel = 50  # m²
irradiacao_solar = 5.5  # kWh/m²/dia
```

# Impacto Ambiental
O sistema calcula automaticamente:

Redução de emissões de CO₂
Equivalência em árvores plantadas
Contribuição para sustentabilidade

# Metodologia

Geração de Dados: Simulação realística baseada em distribuições estatísticas
Pré-processamento: Normalização com StandardScaler
Treinamento: Random Forest ou Regressão Linear
Validação: Cross-validation com 5 folds
Predição: Dimensionamento considerando restrições físicas

**Dados:**

https://www.portalsolar.com.br/mercado-de-energia-solar-no-brasil.html
https://www-cleanenergyreviews-info.translate.goog/blog/most-efficient-solar-panels?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc