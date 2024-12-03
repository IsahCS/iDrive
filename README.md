## Configuração

## Clone
  git clone --recurse-submodules https://github.com/IsahCS/iDrive.git

## Ativar google API's 
  Crie um projeto no Google Cloud Console.
  Gere uma chave de API para usá-la no projeto.
  Ative as seguintes APIs:
  
    Maps JavaScript API
    Maps Static API
    Places API
    Routes API

## Configure as variáveis de ambiente
  Renomeie os arquivos .env-exemplo para .env. Você pode fazer isso manualmente ou executar os comandos abaixo:
  
    cp .env-exemplo .env
    cd iDriveServerProject
    cp .env-exemplo .env
    cd ..
    cd iDriveWeb
    cp .env-exemplo .env
    cd ..

## Inicie os serviços
  Na raiz do projeto (\iDrive) execute o seguinte comando para construir e iniciar os containers:
  
    docker compose up --build

## Acesse a aplicação
  http://localhost:80


