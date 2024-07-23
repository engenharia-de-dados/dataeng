# Como começar em Engenharia de Dados
Este projeto tem o objetivo de organizar conteúdos sobre engenharia de dados,  principalmente em português, para facilitar o aprendizado de quem está entrando na área.

Dividimos os recursos em 4 níveis 

## Roadmap

 
### Nível 1 : Fundamentos <<<< Comece aqui!

```mermaid
    graph LR
        A[Fundamentos]
        B[Programação]
        B1[Python]
        B2[SQL]
        C[Banco de Dados Básico]
        C1[Bancos SQL]
        C1_1[Mysql]
        C1_2[Postgres]
        C1_3[SQL Server]
        C2[Bancos NoSQL]
        C2_1[MongoDB]
        C2_2[ElasticSearch]
        C2_3[Redis]
        D[Linux]
        D1[Terminal]
        D2[Shell Scripting]
        D3[SSH]
        D4[Services]
        D5[Resource/ Process Management]
        A-->B
        A-->C
        A-->D
        B-->B1
        B-->B2
        C-->C1
        C-->C2
        D-->D1
        D-->D2
        D-->D3
        D-->D4
        D-->D5
        C1-->C1_1
        C1-->C1_2
        C1-->C1_3
        C2-->C2_1
        C2-->C2_2
        C2-->C2_3

        click B "#programa%C3%A7%C3%A3o" "Programação"
        click B1 "#python" "Python"
        click B2 "#sql" "SQL"
        click C "#banco-de-dados-básico"
       
      
```

##  Programação 

- ### Python
 
    | Site | Título | Nível |

    |:--------|:-------:|--------:|
    |[Python](https://www.python.org//){:target="_blank"}|Python|Básico|
    |[devAnalytics/Youtube](https://www.youtube.com/watch?v=zC0X4CBui-I&list=PLQDFv3ddAPFSwwybX1t5XO7MIyJOTm_Pu){:target="_blank"}|Introdução à Linguagem Python|Básico|
    |[Pandas](https://pandas.pydata.org/){:target="_blank"}|Pandas|Básico|
- ### SQL

    | Site | Título | Nível |

    |:--------|:-------:|--------:|
    |[TeoMeWhy](https://github.com/TeoCalvo/sql_gc){:target="_blank"}|Treinamento SQL|Básico ao avançado|
   
    |[sql-for-data-analysis](https://www.udacity.com/course/sql-for-data-analysis--ud198){:target="_blank"}|Treinamento SQL|Básico|
    
    
    
   
## Banco de dados (Básico)


### Bancos SQL

- #### Mysql
    - [Curso de SQL Completo Gratuito (Softblue)](https://www.softblue.com.br/site/curso/id/3/CURSO+SQL+COMPLETO+BASICO+AO+AVANCADO+ON+LINE+BD03)

- #### Postgres
    - [Treinamento PostgreSQL para DBAs (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/banco-de-dados/postgresql.html)
- #### SQL Server

### Bancos NoSQL

- #### MongoDB
   - [Treinamento MongoDB (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/banco-de-dados/mongodb.html)

- #### ElasticSearch
   - [Treinamento ElasticSearch (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/big-data/elasticsearch.html)

- #### Redis
   - [Treinamento Redis (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/big-data/redis.html)

## Linux


- ### Terminal 

- ### Shell Scripting

- ### SSH

- ### Services

- ### Resource/ Process Management


**[⬆ Voltar ao início](#roadmap)**



### Nível 2 : Indo para as nuvens!
 
```mermaid
    graph LR
        P[Plataforma]
        A[Cloud]
        A1[AWS]
            A1_1[Amazon S3]
            A1_2[AWS VPC]
            A1_3[AWS EC2]
        A2[Azure]
            A2_1[Azure Storage]
            A2_2[Azure Virtual Machines]
            A2_3[Azure Virtual Networks]
        A3[GCP]
            A3_1[Google Cloud Storage]
            A3_2[Google Compute Engine]
            A3_3[Google VPC]
    B[Open Source]
        B1[Docker]
        B2[Apache Mesos]
        B3[OpenStack]
        P-->A
        P-->B
        A-->A1
        A-->A2
        A-->A3
        A1-->A1_1
        A1-->A1_2
        A1-->A1_3
        
        A2-->A2_1
        A2-->A2_2
        A2-->A2_3
        
        A3-->A3_1
        A3-->A3_2
        A3-->A3_3
         
        B-->B1
        B-->B2
        B-->B3 

        click B "#open-source"
        click A1 "#aws"
     
```
 

## Plataforma
### Cloud
#### AWS
- ####  Amazon S3
    - [Um Inventor Qualquer](https://www.youtube.com/watch?v=ayu9xlQXCYs&list=PLOF5f9_x-OYUaqJar6EKRAonJNSHDFZUm&index=17)
- #### AWS VPC
    - [Um Inventor Qualquer](https://www.youtube.com/watch?v=WMsADIgy4ms&list=PLOF5f9_x-OYUaqJar6EKRAonJNSHDFZUm&index=6)
- #### AWS EC2
    - [Um Inventor Qualquer](https://www.youtube.com/watch?v=a6nU5NTHJDM&list=PLOF5f9_x-OYUaqJar6EKRAonJNSHDFZUm&index=8)

#### Azure
- #### Azure Storage
- #### Azure Virtual Machines
- #### Azure Virtual Networks
- #### [Azure Certification DP-2032](https://github.com/JoseRFJuniorBigData/DP-2003)

#### GCP
- #### Google Cloud Storage
- #### Google Compute Engine
- #### Google VPC

### Open Source
- #### Docker
    - [Treinamento Docker (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/infraestrutura/docker.html)
- #### Apache Mesos
    - [Treinamento Apache Mesos (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/hadoop/apache-mesos.html)
- #### OpenStack

 


### Nível 3 : Escolha seu caminho

## Data Pipelines Engineer

```mermaid
    graph LR
        P[Data Pipelines Engineer]
        A[Arquitetura Serveless]
          A1[AWS Lambda] 
          A1[Google Functions] 
          A1[Azure Functions] 
        
        B[Job Orquestration]
            B1[AWS Step Function]
            B2[Apache Airflow]
            B3[Luigi]
            B3[Prefect]
            B3[Dagster]
        C[Processing Frameworks]
            C1[Apache Spark]
            C2[Apache Arrow]
            C3[dbt]
        
        
        P-->A
        P-->B
        P-->C
        
        A-->A1
        A-->A2
        A-->A3 
        
        B-->B1
        B-->B2
        B-->B3 

        C-->C1
        C-->C2
        C-->C3
        
        click B "#open-source"
        click A1 "#aws"
     
```

### Arquitetura Serveless
- #### AWS Lambda
    - [Um Inventor Qualquer](https://www.youtube.com/watch?v=N5dtRX2PWHY&list=PLOF5f9_x-OYUaqJar6EKRAonJNSHDFZUm&index=19)
- #### Google Functions
- #### Azure Functions

### Job Orquestration
- #### AWS Step Function
- #### Apache Airflow
  - [Supletivo Airflow](https://www.youtube.com/watch?v=f_lnDBR3rFU)
  - https://www.udemy.com/course/the-ultimate-hands-on-course-to-master-apache-airflow
  - https://www.udemy.com/course/the-complete-hands-on-course-to-master-apache-airflow
  - https://www.udemy.com/course/apache-airflow-on-aws-eks-the-hands-on-guide	
  - [Treinamento Apache Airflow (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/data-science/airflow.html)
- #### Luigi
- #### Prefect
- #### Dagster

### Processing Frameworks
- #### Apache Spark
  - [Supletivo Spark](https://www.youtube.com/watch?v=mrHnb8U4fX4)
- #### Apache Arrow
- #### dbt
  - [Supletivo dbt](https://www.youtube.com/watch?v=96gpDt-MGMM) 
  - [ETL101 - Curso de ETL utilizando o Modern Analytics Stack (Big Query + Stitch + dbt)](https://www.youtube.com/watch?list=PLrJaJt2i__IxReStfKCl88VT4pQxVKRzF&v=1q1P1mP9III)
  - [Treinamento dbt - Analytics Engineering Workflow (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/data-science/dbt.html)



## Data Infraestructure Engineer
 
```mermaid
    graph LR
        P[Data Infraestructure Engineer]
        A[Kubernets]
          A1[Helm]  
        
        B[Clustering]
            B1[Apache Spark - infra] 
        C[Infra as Code]
            C1[Terraform]
            C2[Ansible]
            C3[AWS CDK]
            C4[Pulumi]
        D[Auto-Scaling]
        
        P-->A
        P-->B
        P-->C
        P-->D
        
        A-->A1 
        
        B-->B1 

        C-->C1
        C-->C2
        C-->C3
        C-->C4
         
     
```
### Kubernets
- Helm
### Clustering
- Apache Spark - infra
### Infra as Code
- Terraform
- Ansible
- AWS CDK
- Pulumi
### Auto-Scaling


### Nível 4: Torne-se um Jedi

```
Aprofundamento Geral
    Recursos Computacionais
    Linguagens de Programação
    Data Warehousing
        * Arquiteturas de Schema de DWs;
    Monitoramento
    Segurança
    Data Lakes
        * Arquiteturas de DL;
        * Data Lakehouses;

Arcabouço Teórico
    Algebra linear
    Cálculo numérico
    Recuperação de Informação
    Computação distribuída

Data Governance
    Controle de Acesso SGBDs
    Catálogo de dados
        * Amundsen;
        * Datahub;
        * OpenMetadata;
        * Apache Atlas
    Testes de dados;
        * Great Expectations;
    Auditoria
        LGPD/GPDR

Data Streaming
    Apache Kafka
      -  [Treinamento Kafka Fundamental (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/big-data/kafka.html)
    AWS Kinesis
    CDC
    Apache Nifi
      - [Treinamento Apache NiFi (Ambiente Livre)](https://www.ambientelivre.com.br/treinamento/hadoop/apache-nifi.html)
    Apache Beam
	    https://www.udemy.com/course/apache-beam-python

Machine Learning Engineering
    Machine Learning
        Aprendizado Supervisionado
        Aprendizado Não-Supervisionado
    Estatística e Probabilidade
    Teste A/B
 
``` 
 ===========================

## Trilhas Pagas:
* Engenheiro de dados do Datacamp; 
* Curso de engenheiro de dados do Google (para Certificação); 
* Engenharia de dados da Udacity;  https://www.udacity.com/course/data-engineer-nanodegree--nd027

  

## Datasets para estudar e criar projetos:
	* Google Bigquery public datasets - https://cloud.google.com/bigquery/public-data;
	* Kaggle Datasets - https://www.kaggle.com/;
	* Portais do Governo;
	* APIs;
	    * Tools:
		* Postman;
		* Imnsonia;
	    * CEP, CNPJs, DDD, FIPE, etc - https://brasilapi.com.br/docs
 
