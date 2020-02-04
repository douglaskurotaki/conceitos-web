# Client Side VS Server Side

## Evolução das Arquiteturas
1- Mainframe 
  - Tudo é centralizado
2- Client-Server
  - Delphi
  - Aplicação de 2 ou 3 camadas
    - CLient - Regra de Negócio - Banco de dados (2 camadas)
    - Client com regras - middleware - Banco de dados (3 camadas)
    - Processamento dentro do cliente
    - Dificuldade  de atualizar aplicação
3- Web Server-side
  - Toda lógica e renderização é **processada** no servidor
  - Fácil atualização
  - Servidor centraliza todas as responsabilidades
  - Tudo é feito por requisição, ou seja, situações mesmo simples, vai renderizar novamente a página
4- front-end Client-side + server
  - Código fica no lado cliente para facilidade de obter dados: Microserviços
  - Regra de detalhes visuais
  - Modelos ricos
  - SPA (Single page aplication), é uma única página que gera html para renderizar a página dinamicamente diretamente do JS
  - Dados vindo do JSON
  - Trabalhando com os 2 Server-side e Client-side