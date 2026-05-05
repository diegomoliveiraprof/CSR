# Linux Comandos Úteis

---

📂 Manipulação de pastas e arquivos

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| ls -l | Lista arquivos com detalhes | ls -l /home/diego |
| cd pasta | Entra na pasta especificada | cd projetos |
| pwd | Mostra caminho atual | pwd |
| mkdir nome | Cria nova pasta | mkdir backup |
| rm arquivo | Remove arquivo | rm notas.txt |
| rm -r pasta | Remove pasta e conteúdo | rm -r temp |
| cp origem destino | Copia arquivo/pasta | cp foto.jpg /imagens/ |
| mv origem destino | Move ou renomeia | mv relatorio.txt relatorio_final.txt |

---

🌐 Gerenciamento de redes

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| ping host | Testa conectividade | ping [google.com](http://google.com/) |
| networkctl | Mostra interfaces diponíveis | networkclt |
| ip addr show | Mostra interfaces e IPs | ip addr show |
| netstat -tulnp | Lista conexões e portas | netstat -tulnp |
| curl url | Acessa conteúdo de uma URL | curl [https://example.com](https://example.com/) |
| wget url | Baixa arquivo da web | wget https://site.com/arquivo.zip |

---

🌐 Visualizar rotas com ip

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| ip route show | Mostra tabela de rotas atual | ip route show |
| ip route add | Adiciona rota manualmente | ip route add 192.168.1.0/24 via 192.168.0.1 |
| ip route del | Remove rota | ip route del 192.168.1.0/24 |

---

📝 Criação e edição de arquivos

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| touch arquivo | Cria arquivo vazio | touch notas.txt |
| nano arquivo | Editor simples | nano notas.txt |
| vim arquivo | Editor avançado | vim notas.txt |
| cat arquivo | Mostra conteúdo | cat notas.txt |
| less arquivo | Visualiza com rolagem | less notas.txt |
| echo "texto" > arquivo | Escreve (sobrescreve) | echo "Olá" > notas.txt |
| echo "texto" >> arquivo | Adiciona ao final | echo "Nova linha" >> notas.txt |

---

⚙️ Manipulação de serviços com Systemd

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| systemctl status serviço | Verifica status | systemctl status nginx |
| systemctl start serviço | Inicia serviço | systemctl start nginx |
| systemctl stop serviço | Para serviço | systemctl stop nginx |
| systemctl restart serviço | Reinicia serviço | systemctl restart nginx |
| systemctl enable serviço | Ativa na inicialização | systemctl enable nginx |
| systemctl disable serviço | Desativa inicialização | systemctl disable nginx |

---

🚶 Movimentação entre pastas

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| cd .. | Volta uma pasta | cd .. |
| cd / | Vai para raiz | cd / |
| cd ~ | Vai para pasta do usuário | cd ~ |

---

🔑 Acesso remoto com SSH

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| ssh usuario@host | Conecta em servidor | ssh [diego@192.168.0.10](mailto:root@192.168.0.10) |
| ssh -p porta usuario@host | Conecta em porta específica | ssh -p 2222 diego@servidor |
| scp arquivo usuario@host:/destino | Copia para servidor | scp backup.zip diego@servidor:/home/diego/ |
| scp usuario@host:/origem arquivo | Copia do servidor | scp diego@servidor:/home/diego/backup.zip . |

---

📥 Download de arquivos via CLI

| Comando | Descrição | Exemplo |
| --- | --- | --- |
| wget url | Baixa arquivo | wget https://site.com/arquivo.zip |
| curl -O url | Baixa mantendo nome | curl -O https://site.com/arquivo.zip |

---

