# R024 - Web Service
O que é? 
- Serviço de negócio com simples tecnologias com formatos tipo texto para interoperabilidade. Formatos binários são complexos na questão de tipagem e para integração de aplicação. 
- O tráfego são textuais: XML, JSON,
- Url associadas
- Padrão de resultado

<br>

- SOAP e REST (dois modos de trabalhar com web service)
- SOAP  
  - Descreve as assinaturas de cada classe
  - WSDL (XML chato que descreve as funcionalidade do serviço disponibiliza)
  - RPC - Invocação remota atraves desse protocolo(SOAP) - Chama as classes disponibilizadas
  - XML
  - Burocrático
<Br>
- REST
  - Requisição ao end-point e reconhece o verbo REST
  - Se seguir o REST a aplicação irá ser um RESTful
  - Simples de comunicação  
<Br>

### Convenão do RESTful
- CRUD

|URL         |Método|Descrição          |
|---         |---   |---                |
|/clientes   |POST  |Novo CLiente       |
|/clientes   |GET   |Obtém todos        |
|/clientes/36|GET   |Obtém cliente 36   |
|/clientes/12| POST |Atualiza Cliente 12|
|/clientes/41|DELETE|Excluir Cliente 41 |

<br>

### Escolha Arquiteturais
- SOA
  - Mais antiga
  - Baseada em serviços instalado em ESD(Barramentos de serviços)
    - Esses serviços são orquestrados por linguagens
  - Serviços pequenos para ser usados em várias partes
  - Escala de forma mais independente 
    - Se torna dificil para gerar comunicação entre os serviços
-Microserviços
  - Quebra de serviços para atender específicas partes
  - Ex. Spotify - Playlist(Microserviço)
  - Deixa de ter uma aplicação grande monolítica para essa quebra
  - Podem ter banco de dados diferentes, linguagem diferentes...
  - Mais flexibilidade de escalar a aplicação
  
