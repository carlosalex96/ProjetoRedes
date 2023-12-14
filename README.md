# ProjetoRedes

## Bem vindo(a) ao meu projeto de conclusão do módulo de redes da minha formação em DevOps pela Ada Tech!

Realizei a criação de 2 redes diferentes e a comunicação entre uma e outra.

### Rede A
IP da rede: 192.168.0.0/24   
Gateway: 192.168.10.254   
DHCP: 192.168.10.253

Criação de Outras 4 máquinas dentro da Rede Interna A utilizando DHCP para desktops, e IP fixo para Servidores.

### Rede B
IP da rede: 172.15.0.254/24   
Gateway: 172.15.0.254   
DHCP: 172.15.0.253    
Servidor Web: 172.15.0.252 

Criação de Outras 5 máquinas dentro da Rede Interna B utilizando DHCP para desktops, e IP fixo para Servidores.

### Equipamentos:
1 Roteador 1841, 2 Switches 2960 24TT, 2 computadores (clientes) e 3 servidores (2 DHCP e 1 Web/DNS)

### Objetivo:
O objetivo final, é que um dos Desktops da Rede A, consiga colocar em seu navegador interno, o endereço do Site do Servidor WEB que está na REDE B, e a página possa ser carregada corretamente, validando deste modo o Roteamento entre as Redes, DNS e a camada da Aplicação funcionando corretamente.
Foi possível alcançar o objetivo fazendo a criação das 2 redes conectadas a um roteador com portas configuradas para ambas as redes. A comunicação das máquinas da Rede A com o servidor WEB que está na Rede B foi possível por configurar o endereço IP do servidor WEB como DNS na Rede A.

### Visão Final:
![image](https://github.com/carlosalex96/ProjetoRedes/assets/83734836/4d177040-fff9-479c-8cb4-bf5f136444d2)
