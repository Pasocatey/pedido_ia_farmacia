# 💊 Sistema de Consulta de Medicamentos (Bubble + N8N + Supabase)

## 📌 Descrição
Este projeto é um protótipo de aplicativo para **farmacêuticos clínicos**:

- O usuário insere o **nome do medicamento** e informações do paciente no **formulário Bubble**.  
- O formulário dispara uma **chamada API para um workflow no N8N**, que utiliza o **ChatGPT** para analisar possíveis **interações, efeitos colaterais e complicações**.  
- Os resultados são armazenados e consultáveis no **Supabase**.  

Objetivo: **melhorar a segurança e eficiência da farmácia clínica**, ajudando farmacêuticos a tomar decisões mais informadas e rápidas.

---

## 🎯 Objetivo
- Facilitar a análise de medicamentos para pacientes específicos.  
- Identificar riscos, interações e efeitos adversos rapidamente.  
- Demonstrar integração prática entre Bubble, N8N, ChatGPT e Supabase.

---

## ⚙️ Tecnologias Utilizadas
- **Bubble** → Criação do formulário e interface do usuário  
- **N8N** → Processamento da consulta e integração com ChatGPT  
- **ChatGPT** → Análise de interações, efeitos colaterais e complicações  
- **Supabase** → Armazenamento seguro dos registros de consulta  

---

## 🗂 Estrutura do Projeto
- **Bubble App** → Formulário de entrada e visualização do resultado  
- **N8N Workflows** → Processamento da consulta via API + ChatGPT  
- **Supabase Tables** → Pacientes, medicamentos, resultados de consultas  
- **Docs** → Prints e explicações detalhadas do fluxo  

---

## 📖 Como Testar
1. Acesse o Bubble App: `[https://pedidos-ia-farmcia-55733.bubbleapps.io/version-test?debug_mode=true]`  
2. Preencha o formulário com o nome do medicamento e dados do paciente.  
3. O N8N processa a consulta utilizando o ChatGPT.  
4. Confira no Supabase os resultados da análise.  
5. (Opcional) Receba alertas sobre possíveis complicações ou interações, se configurado.  

---

## ✅ Resultados Esperados
- Consultas de medicamentos recebidas e processadas automaticamente  
- Informações sobre interações, efeitos colaterais e complicações armazenadas  
- Apoio direto à **farmácia clínica**, auxiliando na tomada de decisão do farmacêutico 
