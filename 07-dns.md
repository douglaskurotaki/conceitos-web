# R022 - DNS

### Servidor DNS Traduz nomes de domínio em endereços IP
www.cod3r.com.br -> 54.69.61.89 

DSN Funciona sobre o protocolo UDP na porta 53

<Br>

- O usuário informa o endereço no browser
- Computador envia uma consulta DNS para o sevidor local
- O servidor responde com o endereço IP
- Computador acessa o servdor a partir do IP obtido

### Buscar Recursiva
- DNS Cliente
- DNS Server 1 (11.11.12.1)
Nessa duas questões, o DNS cliente faz uma requisição ao www.cod3r.com e se o DNS não reconhecer ele vai tentar fazer uma busca em outras DNS com server diferentes. O server que tiver referenciado a esse site irá responder e irá retornar para o DNS Cliente

### Busca Iterativa
Quando DNS Cliente requer o site e o DNS Server 1 e ele retorna um DNS, assim, a partir desse novo DNS o Cliente irá tentar fazer a requisição a partir desse outro até encontrar o verdadeiro

### DNS Records
- A - IPV4
- AAAA - IPV6
- MX - Servidor de Email
- NS - Servidor de DNS
- CNAME - Canonical Name (Apelido)