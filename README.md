# jornada-ciber-2026
- 0. encapsulamento é o processo de colocar um "envelope" em torno dos dados quando eles vão descer pelas camadas do modelo OSI/TCP-IP para serem enviados pela rede

- 1. Protocolo de Acesso à Rede (Network Access)

Corresponde às camadas 1 e 2 do modelo OSI (Física + Enlace).
Responsável pela transmissão física e entrega local na rede (mesmo switch ou mesma rede).
Exemplos:
Ethernet
Wi-Fi (802.11)
PPP


Função principal: Endereços MAC, quadros, switches.

2. Protocolo de Internet (Internet Layer)

Corresponde à camada 3 do OSI (Rede).
Responsável pelo roteamento entre redes diferentes.
Exemplos principais:
IP (Internet Protocol) — o mais importante
ICMP (usado no Ping)
OSPF, BGP (protocolos de roteamento)


Função principal: Endereços IP, roteamento lógico.

3. Protocolo de Transporte (Transport Layer)

Corresponde à camada 4 do OSI.
Responsável pela entrega confiável (ou não) dos dados entre origem e destino.
Exemplos:
TCP (confiável, com conexão)
UDP (rápido, sem conexão)


Função principal: Portas (ex: porta 80, 443), controle de fluxo, confiabilidade.

4. Protocolo de Aplicação (Application Layer)

Corresponde às camadas 5, 6 e 7 do OSI.
São os protocolos que o usuário interage diretamente.
Exemplos:
HTTP / HTTPS
DNS
SMTP (e-mail)
FTP, SSH, DHCP


Função principal: Comunicação entre programas/aplicativos.

  
