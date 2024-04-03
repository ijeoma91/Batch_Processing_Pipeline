# Batch_Processing_Pipeline

This project case study main goal is to design a batch processing pipline which will processing data with the use of Docker, spark and cassandra

The pipline will read data  from a csv file which was generated from kaggle, analyzie and later save into cassandra in a docker.

# Steps to Run Batch Processing.

Since I used the google calab as my python porogramming interface for this project, there are serveral steps to be able to run this code in your server or in your local system
There will be a detailed archtectural/ Prerequsite which has a full and lay down details on how to set up your pc before running this code

The following are the basic steps to able to run this code:
- python 2.7 or higher installed in your local system
- Java 8 from Orcle installed in your system
- Docker Desktop which contain Docker compose to be installed in your system (Create an acctount if you don't have one)
- Ngrok to be also install in your system (This is the main tunnel/ intermediary between the docker-compose.yml- and Google Colab)
  
 ### Running Code>...

 - Open a Google Colab
 - install pyspark and Spark
 - In install and import all the necessary for this project and they can be seen  before the main line of Code
   
   ### For Docker-Compose>>>
    - Install any Text Editors, for this case study, Notepad ++ were used
    -  Copy and store the code in your project directory of your choice using *docker-compose.yml*
    - Open your project directory where the code is instored using CMD
    -  Type this (docker-compose u  and docker-compose up -d) in the cmd project directory to connect your docker-compose to your docker-desktop where your cassandra is pull out for data in storation.
  
    -  Note: For much more detailed explaination look at the project Archtectural/Prerequisite`
  
    -  Finally .... to use the docker-compose.yml and the dataset, you need to unzip the folder named My_Batch_Processing_Data_Project
  
Author: Ijeoma Esther Anizoba
   
  
 
