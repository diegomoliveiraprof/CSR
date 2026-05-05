# 172.18.1.40


### Comandos IP VPC



Configuração de endereçamento IP em pcs virtuais VPCs.

## 10.1.1.0/24

10.1.1.0 -> endereço da rede - NÃO posso usar me máquinas

10.1.1.1

...

10.1.1.254

10.1.1.255 -> Broadcast -  - NÃO posso usar me máquinas

| **Ação**                                 | **Comando**                          |
| ---------------------------------------- | ------------------------------------ |
| **Configurar IP/GW**                     | `ip 10.0.0.5 255.255.255.0 10.0.0.1` |
| **Configurar DNS**                       | `ip dns 1.1.1.1`                     |
| **Ver Configuração**                     | `show ip`                            |
| **Salvar tudo**                          | `save`                               |
| **Limpar IP**                            | `clear ip`                           |
| **DHCP** (se houver servidor)            | `ip dhcp`                            |
| **PING** (teste entre pcs)               | ping 10.1.1.1                        |
| **TRACE** (Verificar rota até o ponto B) | trace 8.8.8.8                        |
