# 📌 Sprint 3 - DISRUPTIVE ARCHITECTURES: IOT, IOB & GENERATIVE IA

## 🔹 **Visão Geral do Projeto**
Este projeto tem como objetivo desenvolver um modelo de **Machine Learning** para prever e reduzir sinistros odontológicos, utilizando **Random Forest**. Durante a **Sprint 3**, foram aplicadas melhorias na arquitetura do modelo, validação dos dados e integração com outras disciplinas do projeto.

---

## 📍 **Objetivos da Sprint 3**
✅ **Demonstração do Protótipo Funcional** – Apresentação do modelo atualizado e análise de seus resultados.  
✅ **Explicação da Arquitetura de IA** – Justificativa para a escolha do modelo e como ele será aplicado no sistema.  
✅ **Base de Dados Utilizada** – Definição e importância das variáveis para a análise preditiva.  
✅ **Evoluções desde a Sprint 2** – Melhorias implementadas, como normalização de dados e validação cruzada.  
✅ **Integração com Outras Disciplinas** – Explicação de como o modelo será utilizado pelo backend e no app mobile.  
✅ **Organização no GitHub** – Estruturação do repositório com documentação clara.  
✅ **Criatividade na Apresentação** – Desenvolvimento de um vídeo explicativo com storytelling e demonstração prática.  

---

## 🏗 **Arquitetura da Solução**
O modelo de IA foi construído utilizando **Python e Scikit-Learn** para prever consultas desnecessárias, ajudando a reduzir custos e otimizar atendimentos.

### **🔹 Stack Tecnológica:**
- **Linguagem:** Python  
- **Bibliotecas:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib  
- **Modelo de IA:** Random Forest Classifier  
- **Banco de Dados:** Simulado via dataset sintético  
- **Backend:** Integração futura via API REST (Flask)  
- **Mobile:** Consumo dos resultados pelo aplicativo Android  

### **🔹 Fluxo de Funcionamento:**
1️⃣ Coleta de dados históricos de consultas odontológicas.  
2️⃣ Tratamento e normalização dos dados.  
3️⃣ Treinamento do modelo de IA com validação cruzada.  
4️⃣ Predição de padrões que indicam sinistros desnecessários.  
5️⃣ Exposição do modelo via API para integração com backend e mobile.  

---

## 🔬 **Base de Dados**
A base de dados foi gerada artificialmente para simular um histórico de pacientes. As principais features utilizadas são:
- **Idade** 📊
- **Frequência de Consultas** 📅
- **Procedimento Preventivo Realizado** ✅
- **Histórico de Doenças** 🏥
- **Tempo desde a Última Consulta** ⏳
- **Consulta Desnecessária (Target)** 🚨

---

## ⚙ **Melhorias da Sprint 2 para Sprint 3**
🚀 **Sprint 2:** O modelo inicial não possuía normalização e não utilizava validação cruzada.  
🔥 **Sprint 3:** Implementamos:
- **Validação cruzada (K-Fold CV)** para evitar overfitting.  
- **Normalização dos dados** com `StandardScaler`.  
- **Visualização de importância das features** para entender os fatores de risco.  

---

## 🌎 **Integração com Outras Disciplinas**
📡 **Backend (.NET/Java):** O modelo será exposto via **API REST**, permitindo consultas em tempo real.  
📱 **Aplicativo Mobile:** O app poderá consumir a API para exibir alertas e recomendações personalizadas aos usuários.  
📊 **Banco de Dados:** Os dados serão integrados ao **banco relacional Oracle** para armazenamento e análises futuras.  

---

## 🚀 **Como Rodar o Projeto**
1️⃣ Clone o repositório:  
2️⃣ Instale as dependências e bibliotecas
3️⃣ Execute o notebook  
4️⃣ O modelo será treinado e salvo no arquivo modelo_rf.pkl

---
