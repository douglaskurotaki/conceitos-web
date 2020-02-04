
- 1950 - Computador Eletrônico
- 1960 - ARPANET - Departamento de Defesa Americano
- 1970 - TCP/IP - Robert E. Kahn & Vint Cerf
- 1980 - WWW - Tim Berners-Lee
- 1990 - Internet no Brasil
- 2000 - Provedores discados

### Grande rede de computadores!

- **Topologias** é a forma de como se organiza a rede (**Centralizada**, **Distribuida**)
- A internet em si é distribuida, pois são ligadas em varios pontos
- A web é uma **teia**, na qual é uma vasta quantidade de provedores que se conectam e a partir deles nós conseguimos nos conectar (**ISP**)

### TCPIP

- É **orientado a conexão**
- UDP - **Não orientado a conexão**, porém é mais leve
- TCP possui uma **validação** antes do dado ser enviado
- É um protocólo com **padrão Layer**
  - Rede/Física - Internet - Transporte - Aplicação
  - A camada de cima usa a camada de baixo. Aplicação usa camada de Transporte
  - A camada de baixo devolve determinada informação para de cima
  - Física - Ethernet, Wi-Fi, Mac address, Física(Hardware) e Enlace(Software)
  - Internet - IP, Conexão entre redes, Transferência de Pacotes
    - Podem ter IP repetidos desde que esteja na mesma rede
  - Transporte - TCP(Confiável), UDP(Melhor esforço)
  - Aplicação - HTTP, FTP, SMPT, Comunicação Processo-A-Processo, Número de Porta

### IP

- É responsável pela **comunicação** entre redes
- Classe A (192.168.100.230), cada parte é de 0 a 255
  - Parte desse IP é destinada a rede e a outra do computador
  - Primeira parte é a rede e as 3 últimas o HOST
  - Máscara de Sub-rede
- Classe B
  - As 2 primeiras partes é a rede e o resto HOST
  - Máscara 255.255.0.0
  - 255 é a rede e o 0 é HOST
- Classe C
  - 255.255.255.0
  - 3 partes é a rede e o resto é o HOST
- O IP sozinho não mostra muito coisa, pois o que define o que é rede e host é a **máscara**

### Porta
- Processo é mapeado pela porta
- Porta serve para conectar a requisição de uma outra máquina