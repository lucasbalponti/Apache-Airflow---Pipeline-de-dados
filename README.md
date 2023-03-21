# Apache Airflow - Pipeline de dados

Neste projeto foram desenvolvidos códigos a extração e transformação de dados via uma API usando python, além de realizar a automatização desse processo pelo Apache Airflow

| Nome | Descrição |
| -- | --|
| [Script python extração](https://github.com/lucasbalponti/Apache-Airflow---Pipeline-de-dados/blob/main/datapipeline/extrai_infos_clima.py) | Script python para a extração de dados climáticos via API |
| [Script dag dummy](https://github.com/lucasbalponti/Apache-Airflow---Pipeline-de-dados/blob/ubuntu/dags/first_dag.py) | Script para exemplificar o funcionamento e sintaxe do airflow |
| [Script dag extração](https://github.com/lucasbalponti/Apache-Airflow---Pipeline-de-dados/blob/ubuntu/dags/dados_climaticos.py) | Script dag onde foi configurado semanalmente a extração de dados climáticos via API |