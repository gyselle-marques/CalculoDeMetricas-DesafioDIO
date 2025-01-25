<h1 align="center"> Desafio DIO: Cálculo de Métricas de Avaliação de Aprendizado</h1>
<p>Neste projeto, é calculado as principais métricas para avaliação de modelos de classificação de dados, como acurácia, sensibilidade (recall), especificidade, precisão e F-Score.</p>
Para calcular as métricas, é utilizado uma matriz de confusão que fornece os seguintes valores:

- VP: Verdadeiros Positivos
- VN: Verdadeiros Negativos
- FP: Falsos Positivos
- FN: Falsos Negativos

<p>Para implementar as funções de cálculos, é utilizado as fórmulas a seguir:</p>

```python
# Fórmula: Acurácia = (VP + VN) / (VP + VN + FP + FN)
acuracia = (VP + VN) / (VP + VN + FP + FN)
print(f"Acurácia: {acuracia:.2f}")

# Fórmula: Precisão = VP / (VP + FP)
precisao = VP / (VP + FP)
print(f"Precisão: {precisao:.3f}")

# Fórmula: Sensibilidade = VP / (VP + FN)
sensibilidade = VP / (VP + FN)
print(f"Sensibilidade: {sensibilidade:.3f}")

# Fórmula: Especificidade = VN / (VN + FP)
especificidade = VN / (VN + FP)
print(f"Especificidade: {especificidade:.3f}")

# Fórmula: F-Score = 2 * (Precisão * Sensibilidade) / (Precisão + Sensibilidade)
f_score = 2 * (precisao * sensibilidade) / (precisao + sensibilidade)
print(f"F-Score: {f_score:.3f}")
```

##
<h3>💻Tecnologias</h2>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white) 
