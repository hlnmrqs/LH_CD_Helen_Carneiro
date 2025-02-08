# Desafio de Ciência de Dados Lighthouse

## Requisitos

Antes de executar o projeto, instale os seguintes pacotes Python:

```sh
pip install -r requirements.txt
```

## Como Executar o Projeto

1. Clone este repositório:

```sh
git clone https://github.com/hlnmrqs/LH_CD_Helen_Carneiro.git
cd LH_CD_Helen_Carneiro
```

2. Execute o arquivo:

```sh
python projeto.ipynb
```

4. O modelo treinado será salvo no diretório `/models/modelo_rf.pkl` no formato compactado.

5) Para carregar o modelo e fazer previsões:

```python
modelo_rf = joblib.load("models/modelo_rf.joblib")
```

## Avaliação do Modelo

O modelo foi avaliado usando as seguintes métricas:

- **MAE (Erro Absoluto Médio)**
- **MSE (Erro Quadrático Médio)**
- **RMSE (Raiz do Erro Quadrático Médio)**
- **R² (Coeficiente de Determinação)**

---
