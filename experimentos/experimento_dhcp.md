# Experimento MAC e ARP
## OBJETIVO
​Compreender o processo de atribuição dinâmica de endereços IP através da análise real de pacotes, identificando as etapas do acrônimo DORA.

## Experimento
1. Inicie a captura no Wireshark
2. No terminal (Linux/Mac) ou CMD/PowerShell (Windows), execute os comandos para liberar o IP atual e solicitar um novo:

Linux: sudo dhclient -r (libera)
sudo dhclient -v (renova).

Windows: ipconfig /release e ipconfig /renew.
