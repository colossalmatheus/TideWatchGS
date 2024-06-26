# TideWatch

## Equipe
- Fabio de Oliveira Targa - RM551328 - 2TDSPN
- Joao Vitor Souza Nunes - RM550381 - 2TDSPF
- Enzo Oliveira - RM551356 - 2TDSPF
- Matheus Colossal Araujo - RM99572 - 2TDSPF
- Vinicius Durce Carlini - RM550427 - 2TDSPM

## Como Rodar a Aplicação

### Configuração do Ambiente de Desenvolvimento:
- Certifique-se de ter o Java Development Kit (JDK) instalado na sua máquina.

### Configuração do Projeto:
- Clone o repositório do projeto ou crie um novo projeto Spring Boot usando uma ferramenta de desenvolvimento integrado (IDE) como IntelliJ IDEA, Eclipse ou Spring Tool Suite.
- Configure as dependências e propriedades do projeto, incluindo a configuração do banco de dados no arquivo `application-homologacao.yml`.

### Configuração do Banco de Dados:
- Certifique-se de ter um banco de dados configurado e em execução.
- Configure as credenciais e a URL do banco de dados no arquivo de configuração `application-homologacao.yml`.

### Execução da Aplicação:
- Execute a aplicação Spring Boot localmente, usando a IDE ou a linha de comando.

### Teste:
- Acesse a aplicação em um navegador da web ou faça solicitações HTTP usando ferramentas como Postman para verificar se está funcionando conforme o esperado.

## DER
<img width="596" alt="image" src="https://github.com/colossalmatheus/TideWatchGS/assets/125572827/438044dd-9555-4aac-bd2f-1a6b1f4ed4a6">


## Diagrama de Classes
![image](https://github.com/colossalmatheus/TideWatchGS/assets/125572827/736a84fb-f506-48af-9f9e-07f69cef50bf)


## Endpoints

### Drone
- **GET** `/drone`
- **GET** `/drone/{id}`
- **POST** `/drone`

### Localizacao
- **GET** `/localizacao`
- **GET** `/localizacao/{id}`
- **POST** `/localizacao`

### Sistema
- **GET** `/sistema`
- **GET** `/sistema/{id}`
- **POST** `/sistema`

### Usuario
- **GET** `/usuario`
- **GET** `/usuario/{id}`
- **POST** `/usuario`

### Embarcacao
- **GET** `/embarcacao`
- **GET** `/embarcacao/{id}`
- **POST** `/embarcacao`

### Monitoramento
- **GET** `/monitoramento`
- **GET** `/monitoramento/{id}`
- **POST** `/monitoramento`

### Residuo
- **GET** `/residuo`
- **GET** `/residuo/{id}`
- **POST** `/residuo`

- Link do pitch: https://youtu.be/Yh6JtN-8Zfg
