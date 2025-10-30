# projeto_adatech_ml1
Projeto para conclusão do curso da AdaTech - Machine Learning 1 - Prof Maurício Sobrinho

## Storytelling do projeto

A base escolhida para o projeto é a "Credit Card Transactions Fraud Detection Dataset" do Kaggle, podendo ser acessada através do link https://www.kaggle.com/datasets/kartik2112/fraud-detection/data.

Trata-se de uma base contendo transações simuladas de cartão de crédito com a marcação de legítimas ou fraude.

A base possui 22 colunas, sendo elas:

| Campo | Descrição |
|-------|-----------|
| trans_date_trans_time | Data e hora da transação |
| cc_num | Número da conta corrente do cliente |
| merchant | Comerciante em que a transação foi efetuada |
| category | Categoria do tipo da transação efetuada |
| amt | Valor da transação |
| first | Primeiro nome do cliente |
| last | Último nome do cliente |
| gender | Gênero do cliente |
| street | Rua de residência do cliente |
| city | Cidade de residência do cliente |
| state | Estado de residência do cliente |
| zip | CEP de residência do cliente |
| lat | Latitude da residência do cliente |
| long | Longitude da residência do cliente |
| city_pop | Tamanho populacional da cidade do cliente |
| job | Profissão do cliente |
| dob | Data de nascimento do cliente |
| trans_num | Identificação da transação |
| unix_time | Identificação de horário da transação |
| merch_lat | Latitude do comércio em que foi feita a transação |
| merch_long | Longitude do comércio em que foi feita a transação |
| is_fraud | Marcação se a transação foi fraude ou não |

O objetivo é do projeto desenvolver um modelo para prever transações que sejam fraude.

Foram avaliados os modelos:

KNN
Árvores de Decisão
Random Forest
XBoost
LightGBM
SVM

O restante da metodologia está descrita nos markdowns e comentários do notebook.
