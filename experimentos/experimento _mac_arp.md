_______________________

# Experimento MAC e ARP



## OBJETIVO
​
Utilizar um sniffer de rede como o Wireshark, para evidenciar o funcionamento das LAN's com
end. MAC e protocolo ARP.
Executar o experimento e responder às questões em um relatório, utilizar print das telas sempre
que possível para justificar suas respostas.

## Experimento

## 1. Inicie a captura no Wireshark
- Abra o **Wireshark**.  
- Selecione a **interface de rede ativa** (aquela conectada à internet ou rede local).  
- Clique em **Start Capture** para começar a coleta de pacotes.

## 2. Visualize e manipule a tabela ARP
- Abra o **Prompt de Comando (CMD)** no Windows ou o **Terminal (CLI)** no Linux.  
- Execute o comando para visualizar a tabela ARP:  
  - **Windows:** `arp -a`  
  - **Linux:** `arp -n`  
- Observe os endereços IP e MAC já presentes na tabela.  
- Escolha **dois endereços IP da rede local** que **não estejam listados** na tabela ARP.  
- Efetue um **ping** para cada um desses endereços.

## 3. Finalize a captura
- Retorne ao **Wireshark**.  
- Clique em **Stop Capture** para encerrar a coleta de 

