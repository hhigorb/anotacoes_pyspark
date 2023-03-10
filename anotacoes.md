# Spark

Spark é uma ferramenta para processamento de dados massivo.

Ele trabalha com clusters, ou seja, o processamento pode ser dividido em várias máquinas. Graças a isso, ele é extremamente rápido e eficiente.

![Spark Tolerância a Falhas](images/Screenshot_1.png "Spark Tolerância a Falhas")

## Particionamento

É possível particionar o processamento em diferentes clusters. Isso ajuda quando há muitos registros para processar. É basicamente dividir os dados em partições (mês a mês, por exemplo).

![Partições](images/Screenshot_2.png "Partições")

## Lazy Evaluation

O spark utiliza Lazy Evaluation. Isso significa que uma transformação de dados só executada quando uma ação é invocada.

![Lazy Evaluation](images/Screenshot_3.png "Lazy Evaluation")

## Transformações: Narrow e Wide

Transformação Narrow ocorre quando os dados necessários estão em uma mesma partição.

Já Wide quando os dados estão em mais de uma partição.

## Componentes

![Componentes](images/Screenshot_4.png "Componentes")

---

![Componentes](images/Screenshot_5.png "Componentes")

## SparkContext e SparkSession

SparkContext fornece conexão transparente com o Cluster. Já o SparkSession dá acesso ao SparkContext

## Formato de dados para Big Data

![Formato de dados para Big Data](images/Screenshot_6.png "Formato de dados para Big Data")

---

![ORC ou Parquet](images/Screenshot_7.png "ORC ou Parquet")

## RDD - Reilient Distributed Datasets

![RDD](images/Screenshot_8.png "RDD")

---

![RDD pt2](images/Screenshot_9.png "RDD pt2")

## Dataset e DataFrame

![Datasets e DF](images/Screenshot_10.png "Datasets e DF")

---

![DataFrames](images/Screenshot_11.png "DataFrames")

---

![DataFrames Tipos de Dados](images/Screenshot_12.png "DataFrames Tipos de Dados")

---

![Schema](images/Screenshot_13.png "Schemaa")