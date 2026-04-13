
# Principais opções de simuladores e emuladores

---

## 1. **Packet Tracer**
- **Tipo:** Simulador de rede.  
- **Destaque:** Ferramenta oficial da Cisco para ensino básico.  
- **Recursos:** Criação de topologias simples, configuração de IPs, roteamento estático, ACLs e servidores (DNS, Web, DHCP).  
- **Perfil:** Iniciantes e estudantes em disciplinas introdutórias de redes.  

---

## 2. **GNS3 (Graphical Network Simulator-3)**
- **Tipo:** Emulador de rede (executa imagens reais de sistemas).  
- **Destaque:** Muito usado em certificações avançadas (CCNP, CCIE).  
- **Recursos:** Integração com máquinas virtuais, suporte a IOS, Juniper, Mikrotik, etc.  
- **Perfil:** Estudantes avançados e profissionais.
- **Usuários** Não faz separação do ambiente de trabalho dos usuários
- **Arquitetura Cliente-Servidor:** O GNS3 pode ser instalado tanto em uma máquina local quanto em um servidor remoto. No entanto, mesmo quando a instalação é feita no servidor, é necessário que o cliente também esteja instalado na máquina do usuário para que o sistema funcione corretamente.
---

## 3. **EVE-NG (Emulated Virtual Environment Next Generation)**
- **Tipo:** Emulador completo.  
- **Destaque:** Interface web, suporta múltiplos fabricantes (Cisco, Palo Alto, Fortinet, etc.).  
- **Recursos:** Laboratórios colaborativos, integração com VMware e VirtualBox.  
- **Perfil:** Treinamento corporativo e certificações.
- **Pago:** A maior parte dos recursos é liberada apenas na versão paga.

---

## 4. **PNETLab**
- **Tipo:** Emulador baseado em EVE-NG (derivado).  
- **Destaque:** Gratuito, interface simplificada e suporte a imagens reais.  
- **Recursos:** Permite criar laboratórios complexos com roteadores, switches e firewalls.  
- **Perfil:** Alternativa acessível para quem busca realismo sem custo.  
- **Arquitetura Cliente-Servidor:** O PNETLab é disponibilizado como uma máquina virtual, podendo ser utilizado localmente ou em um servidor dedicado. Os recursos, cenários e laboratórios são acessados diretamente por meio de uma interface web, sem necessidade de instalação adicional no cliente.
---

## 5. **Boson NetSim**
- **Tipo:** Simulador pago.  
- **Destaque:** Focado em certificações Cisco (CCNA, CCNP).  
- **Recursos:** Exercícios guiados, roteiros de estudo e feedback automático.  
- **Perfil:** Estudantes que querem prática estruturada.  

---

## 6. **NS-3 (Network Simulator 3)**
- **Tipo:** Simulador acadêmico.  
- **Destaque:** Usado em pesquisa científica e simulação de protocolos.  
- **Recursos:** Modelagem de redes sem fio, LTE, 5G, TCP/IP.  
- **Perfil:** Pesquisadores e universidades.  

---

## Comparação rápida

| Ferramenta       | Tipo        | Complexidade   | Público-alvo                  |
|------------------|-------------|----------------|--------------------------------|
| **Packet Tracer**| Simulador   | Básica         | Iniciantes, ensino             |
| **GNS3**         | Emulador    | Avançada       | Profissionais, certificações   |
| **EVE-NG**       | Emulador    | Avançada       | Treinamento corporativo        |
| **PNETLab**      | Emulador    | Avançada       | Usuários avançados (gratuito)  |
| **Boson NetSim** | Simulador   | Intermediária  | Estudantes Cisco               |
| **NS-3**         | Simulador   | Acadêmica      | Pesquisadores                  |

[<< voltar](simuadores_emuladores.md)&nbsp;&nbsp;&nbsp;[próximo >> ](simuladores_emuladores_p3.md)
