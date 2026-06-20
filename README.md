# 📊 Dashboard RAIS - Indicadores de Vínculos Empregatícios

Este repositório contém um dashboard desenvolvido em Power BI para análise de dados governamentais da Relação Anual de Informações Sociais (RAIS). O objetivo do projeto é mapear o cenário de vínculos trabalhistas (ativos e CLT) e explorar as características socioeconômicas e demográficas da região.

## 📸 Prévia do Dashboard
*<img width="1809" height="1017" alt="image" src="https://github.com/user-attachments/assets/0040ef12-7da8-4036-96dd-20a01890ad2f" /><img width="1820" height="1034" alt="image" src="https://github.com/user-attachments/assets/3273de66-2ed3-49fe-9578-551fb6b9e529" />
*

## 💡 Por que este arquivo está no formato `.pbit`?
Devido ao alto volume de dados processados neste projeto (a base original possui cerca de 2GB e milhões de linhas), este repositório utiliza o formato **Power BI Template (.pbit)**. 

O `.pbit` preserva toda a inteligência do projeto:
- Relacionamentos e Modelagem de Dados
- Medidas e Fórmulas DAX
- Estruturas de ETL (Power Query)
- Layout e Visuais

Ele apenas descarta os dados importados em cache, mantendo o repositório leve, performático e alinhado com as boas práticas de versionamento.

## 🚀 Como abrir e utilizar este projeto na sua máquina

Para interagir com o dashboard e visualizar os gráficos preenchidos, siga os passos abaixo:

1. **Faça o clone ou baixe este repositório** para a sua máquina.
2. **Obtenha a base de dados:** Certifique-se de ter os dados brutos da RAIS localmente (ou acesso ao banco de dados onde os dados estão hospedados, como o BigQuery / Base dos Dados).
3. **Abra o arquivo `.pbit`:** Dê um duplo clique no arquivo `Eduardo-Bandeira-Trabalho Power BI.pbit`.
4. O Power BI será aberto e solicitará a **atualização da fonte de dados** (Caminho do arquivo local ou credenciais do banco). 
5. Aponte para o diretório correto na sua máquina e aguarde a carga dos dados.

## 🛠️ Tecnologias e Técnicas Aplicadas
- **Power BI:** Visualização de dados e Data Storytelling.
- **Power Query (M):** Limpeza e transformação de dados.
- **Linguagem DAX:** Criação de medidas calculadas para inteligência de negócio.
- O pré-processamento original dos dados da RAIS foi realizado em **Python (Pandas/Parquet)** para otimização de volumetria e memória.

---
Desenvolvido por **Eduardo Bandeira Oliveira**.
