# 🎤 Detecção de Risadas com Machine Learning

Este projeto utiliza técnicas de machine learning para detectar automaticamente **risadas da plateia** em arquivos de áudio. A ideia é transformar reações humanas em dados, ajudando a entender melhor o impacto de conteúdos como vídeos, podcasts e apresentações.

---

## 🧠 Objetivo

- Identificar automaticamente os trechos de áudio com risadas
- Contar o número de **risadas únicas por minuto**
- Explorar modelos de machine learning para comparar desempenho
- Criar visualizações para análise temporal do humor da plateia

---

## 🔍 Exemplo de resultado

- 🎧 Entrada: Áudio com gravação de plateia
- 🤖 Saída: Timestamps com risadas detectadas, gráfico de risadas/minuto, e possibilidade de reconstrução de trechos com risadas

---

## ⚙️ Pipeline do Projeto

1. **Pré-processamento**
   - Split do áudio em pequenos frames
   - Conversão mono, normalização, etc.

2. **Extração de Features**
   - MFCCs
   - Energia
   - Spectral centroid, zero crossing rate, etc.

3. **Modelagem**
   - Classificadores treinados: XGBoost, SVM, Random Forest
   - Avaliação com precision, recall e F1-score

4. **Pós-processamento**
   - Agrupamento de frames para identificar **risadas únicas**
   - Contagem por minuto de execução

5. **Visualização**
   - Gráficos com picos de risadas ao longo do tempo
   - Exportação de frames e reconstrução de áudio filtrado

---

## 🧪 Resultados

| Modelo        | Precision | Recall | F1-score |
|---------------|-----------|--------|----------|
| XGBoost       | 0.87      | 0.82   | 0.84     |
| SVM           | 0.85      | 0.78   | 0.81     |
| Random Forest | 0.82      | 0.76   | 0.79     |

---

## 📊 Visualização

> ![Gráfico de risadas únicas por minuto](./img/risadas_por_minuto.png)

---

## 📁 Estrutura do Projeto

# 🎤 Detecção de Risadas com Machine Learning

Este projeto utiliza técnicas de machine learning para detectar automaticamente **risadas da plateia** em arquivos de áudio. A ideia é transformar reações humanas em dados, ajudando a entender melhor o impacto de conteúdos como vídeos, podcasts e apresentações.

---

## 🧠 Objetivo

- Identificar automaticamente os trechos de áudio com risadas
- Contar o número de **risadas únicas por minuto**
- Explorar modelos de machine learning para comparar desempenho
- Criar visualizações para análise temporal do humor da plateia

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
   - Classificadores treinados: XGBoost, Random Forest
   - Avaliação com precision, recall e F1-score

4. **Visualização**
   - Gráficos com picos de risadas ao longo do tempo

---

## 🧪 Resultados

| Modelo        | Precision | Recall | F1-score |
|---------------|-----------|--------|----------|
| XGBoost       | 0.89      | 0.88   | 0.89     |

---
