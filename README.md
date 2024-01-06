# Airflow Preparar Ambiente
Preparando Ambiente do Airflow

- Pré-requisitos:
   - Instalação Docker

- IDE
   - Anaconda/VSCode

- Instalar Airflow com Docker

  ### Download docker para Windows

  <img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/Docker_Windows.png">

  Instalar Airflow com Docker

  1. Crie uma pasta "airflow"
  2. Salve os seguintes arquivos na pasta:
      - docker-compose.yaml
      - .env

 ### Instalando o Docker

  <img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/Instalando_Docker.png">

  Aguardar o termino da instalação

 - Após a instalaçao do docker, abrir o prompt de comando e posicionar na pasta airflow.

  <img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/CMD_Airflow.png">

  - Apos localizar o caminho da pasta, digitar dir e verificar se o resultado será corretamente apresentado.

  <img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/CMD_DIR.png">
    
   - Agora vamos digitar os comandos para realizar a instalação.

     docker-compose up -d
 
     <img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/Termino_Execucao.png">    

     Comando verificar se o ambiente está pronto: docker-compose ps

   <img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/Verificando_Se_AmbientePronto.png">   

   #### Após a preparação do ambiente, abrir o navegador e digitar: localhost:8080

![image](https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/assets/66569714/41304b15-b699-4507-81b0-02fd73ff806f)



   
     
