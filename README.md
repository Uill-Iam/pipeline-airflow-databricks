# Desenvolvendo Pipeline com Airflow e Databricks 🚀

<div align="center">
  <img src="https://github.com/user-attachments/assets/e581af4b-599e-4ed5-a84e-17ef94720c30" alt="Imagem do pipeline com Airflow e Databricks"/>
</div>


## Badges
![Status](https://img.shields.io/badge/Status-Finalized-brightgreen)  
![Python](https://img.shields.io/badge/Python-3.8-blue)  
![Apache Airflow](https://img.shields.io/badge/Apache-Airflow-orange)  
![Azure Databricks](https://img.shields.io/badge/Azure-Databricks-blue)  
![API](https://img.shields.io/badge/API-APILayer-blue)  
![Slack](https://img.shields.io/badge/Slack-Bot-green)  
![GitHub last commit](https://img.shields.io/github/last-commit/Uill-Iam/pipeline-airflow-databricks)  

---

## Índice
1. [Descrição do Projeto](#descrição-do-projeto)
2. [Status do Projeto](#status-do-projeto)
3. [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
4. [Acesso ao Projeto](#acesso-ao-projeto)
5. [Tecnologias utilizadas](#tecnologias-utilizadas)
6. [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras-do-projeto)

---

## Descrição do Projeto
Este projeto tem como objetivo demonstrar a criação de um pipeline de dados utilizando **Apache Airflow** para orquestrar o processo de ELT, junto com **Azure Databricks** para a execução de transformações de dados. O projeto foi dividido em três partes, utilizando o modelo de **Medalhão** para organizar as diferentes camadas de processamento.

O fluxo do pipeline inclui:
1. **Coleta de Dados**: Através de uma API de câmbio de moedas, foram coletados dados de cotação do Real em relação a três moedas distintas (Dólar, Euro e Libra).
2. **Limpeza de Dados**: Realizada no **Databricks**, onde os dados foram higienizados e preparados para análise.
3. **Geração de Tabelas e Gráficos**: Criação de tabelas de resumo e gráficos de evolução do dólar utilizando os dados tratados.
4. **Integração com Slack**: Utilizando um bot do **Slack API**, as informações geradas (gráficos e tabelas) foram enviadas diretamente para um canal do Slack.
5. **Orquestração com Airflow**: Todo o processo foi orquestrado no **Apache Airflow**, incluindo a automação de etapas e agendamento de tarefas.

---

## Status do Projeto
✅ **Finalizado**  

O pipeline foi desenvolvido, testado e colocado em produção com sucesso.

---

## Funcionalidades e Demonstração da Aplicação
- **Coleta de Dados (API de Cotação de Moeda):** Dados de cotação de moedas são adquiridos automaticamente a partir da API **APILayer**.
- **Limpeza e Processamento de Dados (Databricks):** Utilizando o **Databricks**, os dados brutos são limpos e transformados.
- **Geração de Tabelas e Gráficos:** Tabelas de resumo e gráficos de evolução do dólar são gerados para análise.
- **Integração com Slack:** O bot no **Slack** recebe os dados processados e envia mensagens diretamente no canal.
- **Orquestração no Airflow:** O processo completo é orquestrado no **Apache Airflow**, garantindo a execução automática e em tempo programado.

**Demonstração:**  
- O fluxo de dados é monitorado e orquestrado pelo **Airflow**, com a execução automática das tarefas.
- Ao final de cada execução, as informações são enviadas diretamente para o Slack, proporcionando uma notificação em tempo real.
**Slack:**
  
![image](https://github.com/user-attachments/assets/6931d9d7-2b21-4af9-b2be-01e79b973f91)

---

## Acesso ao Projeto
Você pode acessar o repositório do projeto no GitHub [aqui](https://github.com/Uill-Iam/pipeline-airflow-databricks).

---

## Tecnologias utilizadas
- **Apache Airflow** - Orquestração de workflow
- **Azure Databricks** - Processamento e transformação de dados
- **API APILayer** - Coleta de dados de cotação de moedas
- **Slack API** - Envio de mensagens para Slack
- **Python** - Linguagem de programação utilizada para desenvolvimento

---

## Pessoas Desenvolvedoras do Projeto
- [Uiliiam Santos](https://github.com/Uill-Iam) - Desenvolvedor
