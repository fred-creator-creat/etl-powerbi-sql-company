# 📊 Desafio de Projeto: Processamento de Dados e Dashboard Gerencial (MySQL + Power BI)

Este repositório contém o projeto de integração entre Banco de Dados relacional e Business Intelligence. O objetivo foi realizar o processamento de uma base de dados (cenário 'Company') utilizando Python no Google Colab, com a posterior criação de um dashboard interativo no Power BI.

---

## 🏛️ Contexto e Parcerias

* **Plataforma de Ensino**: [DIO (Digital Innovation One)](https://www.dio.me/)
* **Empresa Patrocinadora**: [Klabin](https://www.klabin.com.br/)
* **Formação**: Power BI Analyst
* **Desenvolvedor**: [Fred Cavalheiro]

---

## 🛠️ Tecnologias Utilizadas

* **[Google Colab](https://colab.research.google.com/)**: Ambiente de nuvem utilizado para execução do script Python e conexão com o banco de dados.
* **[Python / Pandas](https://pandas.pydata.org/)**: Processamento e limpeza de dados (ETL).
* **[MySQL](https://www.mysql.com/)**: Sistema de gerenciamento de banco de dados relacional para armazenamento dos dados do cenário 'Company'.
* **[Microsoft Power BI Desktop](https://powerbi.microsoft.com/)**: Criação do modelo relacional, tratamento no Power Query e visualização de dados.

---

## ⚠️ Justificativa Técnica e Adaptações de Ambiente

Como parte do meu processo de transição de carreira, este projeto exigiu resiliência e adaptações técnicas devido a limitações de infraestrutura:

* **Substituição da Azure**: Por não possuir conta corporativa e visando evitar custos de licenciamento/cartão de crédito na nuvem Azure, optei por uma arquitetura **100% Cloud e Gratuita** utilizando Google Colab e scripts Python para simular a integração com o banco de dados.
* **Hardware e Resiliência**: O desenvolvimento foi realizado em máquina emprestada com limitações de hardware, o que impossibilitou o uso de ferramentas locais pesadas (como o MySQL Workbench). Toda a manipulação de dados foi feita via código no Colab, garantindo a integridade do processamento mesmo com restrições físicas.
* **Restrição de Publicação**: Devido à falta de e-mail institucional para o Power BI Service, a entrega é composta pelas evidências visuais (capturas de tela) e pelos arquivos fonte (`.pbix` e `.ipynb`).

---

## 🚀 Estrutura do Projeto

O projeto foi dividido em duas camadas principais:

### 1. Processamento e ETL (Backend)
* **Conexão**: Script Python para interligação dos dados no ambiente MySQL.
* **Transformação**: Limpeza de dados, tratamento de nulos e tipos de dados via Power Query no Power BI, garantindo que o modelo estivesse pronto para análise.

### 2. Dashboard Gerencial (Frontend)
O relatório foi organizado em 3 visuais estratégicos:
* **Gestão de Colaboradores**: KPIs de equipe, departamentos e análise de cargos.
* **Projetos & Operações**: Acompanhamento de horas trabalhadas e status de projetos.
* **Distribuição Geográfica**: Mapa interativo com a localização dos departamentos.

---

## 📂 Galeria de Evidências (Screenshots)

Abaixo, as capturas de tela que comprovam a execução e a qualidade técnica do projeto:

### 🖼️ Dashboards Finais
| Página 1: Gestão | Página 2: Operações | Página 3: Geográfica |
|:---:|:---:|:---:|
| ![Gestão](./assets/dashboard-01-gestao-colaboradores.png) | ![Operações](./assets/dashboard-02-projetos-operacoes.png) | ![Geográfica](./assets/dashboard-03-distribuicao-geografica.png) |

### ⚙️ Modelagem e Processamento (ETL)
* **Modelagem de Dados (Relacionamentos):**
![Relacionamentos](./assets/modelagem-dados-relacionamentos.png)

* **Processamento de Tabelas (Power Query):**
| Tabela Employee | Tabela Departament | Tabela Project |
|:---:|:---:|:---:|
| ![Employee](./assets/tabela-01-employee-transformacao.png) | ![Departament](./assets/tabela-02-departament-limpeza.png) | ![Project](./assets/tabela-04-project-configuracao.png) |

---

## 📞 Contato e Conexão
**Fred Cavalheiro**
* 🔄 **Transição de Carreira:** De Segurança Patrimonial para Tecnologia/Dados.
* 🎓 **Técnico em Desenvolvimento de Sistemas** (Senac).
* 📚 **Estudante de:** Machine Learning e Análise de Dados (Python, Neo4j, Power BI e Excel).
* 🔗 **[Meu Perfil no LinkedIn](https://www.linkedin.com/in/fred-cavalheiro/)**

---
**Projeto desenvolvido para demonstrar competência técnica em ETL, SQL e Visualização de Dados sob restrições de ambiente.**
