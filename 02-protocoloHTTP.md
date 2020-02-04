# Protocólo HTTP
### Hyper
### Text
### Transfer
### Protocol

São documentos escritos em HTML que podem ser **linkados**, como *CSS*, *JavaScript*, *Imagens*, entre outros

### Caracterísitcas
- Faz parte da camada de **Aplicação**
- É um protocolo **Stateless** - Conversação pela primeira vez, sempre irá fazer requisição em toda **conexão**
- Cliente-Servidor - Requisição e Resposta
  - Manda-se uma requisição através de parâmetros e obtem-se respostas de varias formas de tipos
  - Cliente manda requisição e servidor atende ela e manda resposta baseada
- Opera em cima de TCPIP
- Retorna conteúdos HTML, CSS, JS, Mídias

<Br>

### Fluxo
1- Usuário informa a requisição (www.google.com)
2- Browser gera a requisição (GET / HTTP / 1.1 HOST: www.google.com.br)
3- Servidor WEB gera a resposta
  - Envia um conjunto de cabeçalho e a página HTML
4- Browser exibe a página

<Br>

### Métodos
- GET 
- POST
- PUT
- DELETE
- TRACE
- OPTIONS
- CONECT

<br>

### Requisição e Resposta
- CLiente envia uma requisição ao servidor
- Servidor retorna o dado requisitado
- Diminuir a quantidade de request faz com que seja mais performatico para renderização do site
- Redes desempenho para espalhar arquivos estáticos (menor letência é provido)
- Minimizar o arquivo, porém se for muito grande deve se quebrar
- HandShake

<Br>

### GET
- URL
- Parâmetros da requisição
- google.com.br/search?q=web+moderno&h!=pt-Br
  - Após a ? são os parâmetros
  - q = query
  - h = língua da máquina
  - & é a passagem de uma outra variável

### POST
- Parâmetros para ser enviado
- Se rodar no http numa situação de senha, pode ser descoberto por alguns programas
- Usar https
- E encriptografar

### Grupos de status HTTP
- 1xx - Informação
- 2xx - Sucesso
- 3xx - Redirecionamento
- 4xx - Erro no Cliente
- 5xx - Erro no servidor