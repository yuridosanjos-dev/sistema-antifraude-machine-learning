# 🛡️ Sistema de Inteligência Artificial Antifraude (PIX/Cartão)

Este projeto apresenta uma solução de Machine Learning voltada para CyberSecurity e Prevenção a Fraudes em transações bancárias eletrônicas. O foco principal é a detecção e o bloqueio de atividades ilícitas em tempo real (milissegundos), minimizando o prejuízo da instituição financeira.

## 💰 Impacto no Negócio (ROI)
* **Prejuízo Evitado:** R$ 3.378.786,18 (Valor exato recuperado ao bloquear 222 ataques em tempo real).
* **Assertividade Geral:** 97.75% de acurácia sistêmica.
* **Eficiência Comercial:** 92% de precisão nas fraudes confirmadas, reduzindo drasticamente o índice de falsos positivos e o bloqueio indevido de cartões de clientes legítimos.

## 🔍 Critérios de Decisão da IA (Feature Importance)
O modelo foi treinado para entender o comportamento do fraudador de forma autônoma, mapeando os seguintes pesos críticos de risco:
* **Hora da Transação:** 52.58% de importância (picos críticos identificados entre 00h e 05h da manhã).
* **Valor da Transação:** 34.58% de importância (operações com valores muito acima do histórico padrão).
* **Limite Diário:** 9.49% de importância.
* **Idade do Cliente:** 3.35% de importância.

## 🛠️ Tecnologias Utilizadas
* **Python**
* **Pandas & NumPy**
* **Matplotlib & Seaborn**
* **Scikit-Learn** (*Random Forest Classifier*)
