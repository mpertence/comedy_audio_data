
## 📁 Estrutura do Projeto

# 🎤 Detecção de Risadas com Machine Learning

Este projeto utiliza técnicas de machine learning para detectar automaticamente **risadas da plateia** em arquivos de áudio.
---

## 🧠 Objetivo

- Identificar automaticamente os trechos de áudio com risadas
- Contar o número de **risadas únicas por minuto**

---

## 🔍 Exemplo de resultado

- 🎧 Entrada: Áudio com gravação de plateia
- 🤖 Saída: Timestamps com risadas detectadas, gráfico de risadas/minuto, e possibilidade de reconstrução de trechos com risadas

---

## ⚙️ Pipeline do Projeto

1. **Pré-processamento**
   - Split do áudio em pequenos frames

2. **Extração de Features**
   - MFCCs
   - Energia
   - Spectral centroid, zero crossing rate, etc.

3. **Modelagem**
   - Classificadores treinados: XGBoost
   - Avaliação com precision, recall e F1-score

4. **Visualização**
   - Gráficos com picos de risadas ao longo do tempo

---

## 🧪 Resultados

| Modelo        | Precision | Recall | F1-score |
|---------------|-----------|--------|----------|
| XGBoost       | 0.89      | 0.88   | 0.89     |

---
