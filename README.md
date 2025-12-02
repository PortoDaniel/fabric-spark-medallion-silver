# 🧱 Medallion Pipeline com Spark no Microsoft Fabric

Este repositório contém meu primeiro projeto utilizando **Spark + Microsoft Fabric**, estruturado com a **Arquitetura Medallion (Bronze → Prata → Ouro)**.  
Todo o desenvolvimento foi realizado em **notebooks PySpark**, utilizando a camada PRATA para transformar, padronizar e preparar os dados para consumo analítico.

---

## 🚀 O que foi desenvolvido

### ✔ Camada PRATA (Silver)
Notebook responsável por:
- Leitura dos dados brutos da camada Bronze  
- Padronização e normalização de colunas  
- Conversão de tipos (datas, numéricos, strings)  
- Deduplicação e regras de negócio  
- Escrita dos dados tratados em Delta Lake  
- Organização do pipeline para consumo analítico no Fabric

> O notebook disponibilizado é **100% seguro**, sanitizado e sem qualquer credencial, URI ABFS ou GUID real.

---

## 📂 Conteúdo do repositório

fabric-spark-medallion-pipeline/
│
├── prata/
│ └── prata_cv_sanitized.ipynb ← notebook da camada PRATA (versão segura)
├── README.md
└── .gitignore

yaml
Copy code

---

## 🧠 Tecnologias utilizadas

- **PySpark (Spark 3.x)**
- **Delta Lake**
- **Microsoft Fabric (OneLake + Notebooks)**
- **Arquitetura Medallion**
- **Data Lakehouse Principles**

---

## 🔐 Segurança
Nenhum dado sensível está presente neste repositório.  
Todos os seguintes itens foram removidos ou mascarados:

- URIs ABFS  
- GUIDs do workspace/lakehouse  
- Credenciais de acesso  
- Endpoints internos  
- Keys, tokens e conexões

O notebook mantém apenas a **lógica funcional** do pipeline.

---

## 🎯 Objetivo do projeto
Este repositório faz parte da minha jornada de evolução em:

- Engenharia de Dados  
- Spark no Fabric  
- Arquitetura Medallion  
- Construção de pipelines reprodutíveis e seguros  
- Boas práticas de Data Lakehouse  

Se quiser trocar ideias sobre Spark, Fabric ou Medallion, fique à vontade!

---

## 📎 Contato

LinkedIn: https://www.linkedin.com/in/seu-perfil  
GitHub:   https://github.com/seu-usuario
