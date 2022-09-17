COLAB DIRECT LINK: <https://colab.research.google.com/drive/1sR6PDVHM4KQZG0YD1ly_OrAyEtDG-7h7#scrollTo=zl8N4-d5OzRf>




# **VLabs Data Challenge | 2021** 👨‍💻

    (i)   Desafio: Previsão de LTV do cliente para os próximos 90 dias 
         --> Receita esperada de cada cliente para o período de 25/02/2021 até 26/05/2021 (ou seja, qual o valor total gasto por esse cliente
         durante todo o período indicado);
         --> Leaderboard: ranking com base na acuracidade dos modelos (RMSE);

    (ii)   Database: <https://www.kaggle.com/c/VLabs-DC>

    (iii)   Deliverables:
          --> Arquivo de previsão;
          --> Código-fonte;
          --> Vídeo explicativo (máx. 5 min);
    
    (iv) Formato do Arquivo de Submissão:
          --> Você deve enviar um arquivo CSV com exatamente 126.616 entradas mais uma linha de cabeçalho. Seu envio mostrará um erro se
          você tiver colunas extras
                (além de ID_CLIENTE e VALOR) ou linhas;
          --> O arquivo deve conter exatamente 2 colunas:
                # ID_CLIENTE (em qualquer ordem)
                # VALOR (contendo uma variável contínua de predição representando o valor total gasto pelo cliente no período de 90 dias)

---
---
---
> Data Description
---
---
---

  1. **Descrição dos Arquivos**:
* sales_20_21_train.csv - Nossa base de treino contendo cada venda realizada entre 02/01/2020 e 24/02/2021;
* sample_submission.csv - Exemplo de submissão final. As respostas foram geradas com valores 0 para todos os clientes;


  2. **Descrição dos campos**:
* ID_VENDA - Id único para cada registro;
* DT_VENDA - Data da venda;
* LOJA - Id único da loja em que a venda foi realizada;
* QTD_SKU - Quantidade de produtos vendidos;
* VALOR - Valor total da venda;
* ID_CLIENTE - Id único do cliente;
* CANAL - Canal de venda (FIS - Físico, ECM - E-commerce, 
TELEVENDAS - Telefone, WHATSAPP - WhatsApp, IFOOD - iFood);

---
# Main Libraries
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

<div style="display: inline_block"><br> 
    
</div>

---
