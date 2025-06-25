# 🖥️ Projeto Observability Zabbix

Nesse projeto, estou documentando todo o processo para atingir o funcionamento eficaz do ambiente. Será um ambiente Linux, baseado no Ubunto, para ferramenta Zabbix. O inutuito desse projeto, é demonstrar pleno conhecimento N1 sobre servidores Linux, Zabbix, CMD, criação de grupos de usuários, importação de templates, monitoramento de sistemas operacionais (CPU, memória, disco, rede), monitoramento de redes (tráfego, latência, perda de pacotes e desempenho) e monitoramento de recursos: (CPU, Memória, Disco, Rede). Todo conhecimento deste projeto foi adquirido no curso 052 - Observability and Monitoring Fundamentals pela plataforma 4Linux. Objetivo: Demonstrar conhecimento, concretizar meu aprendizado e alcançar olhares de recrutadores. 😎

---

Para o pleno funcionamento do nosso ambiente, vamos instalar e configurar o Virtual Box, Vagrant e Git. 

**`1. VirtualBox`**
<br/>
<br/>
• Instalação
<br/>
<br/>
No site da [VirtualBox](https://www.virtualbox.org/wiki/Downloads) podemos instalar a versão mais recente do Oracle VM VirtualBox. A instalação é simples, como estou baixando em um Windows basta clicar no "Windows Hosts", executar o arquivo que foi baixado, e seguir normalmente até que a instalação seja efetuada com sucesso.
<p align="center">
  <img src="https://github.com/user-attachments/assets/561b2e9c-ec5b-4131-ba22-4484a0350d0c" alt="VBoxManage versão">
</p>
<br/>
E para verficar que foi instalado corretamente, utilizo o seguinte comando no CMD:
</p>
<br/>
<p align="center">
  <img src="https://github.com/user-attachments/assets/a597c17c-a527-4843-a89f-dfedeb028861" alt="VBoxManage versão">
</p>
<br/>
Se ele retornar a versão corretamente como mostrado, ele está então devidamente instalado. Caso não esteja, recomendo verificar se a aplicação está no path do sistema, que, no meu caso foi necessário até obter sucesso. C:\Program Files\Oracle\VirtualBox\
Copie esse caminho. Vá em: Iniciar → variáveis de ambiente → clique em "Editar variáveis de ambiente do sistema". Clique em "Variáveis de ambiente...". Em "Variáveis do sistema", selecione a variável chamada Path → clique em Editar. Clique em "Novo" e cole o caminho copiado. Clique em OK em todas as janelas para salvar.
</p>
<br/>
• Configuração
</p>
<br/>
A partir de então posso realizar a configuração. Na mesma página do site da VirtualBox, faço o download do Extension Pack. Clico em duas vezes no arquivo Oracle_VM_VirtualBox_Extension_Pack-<versão>.vbox-extpack para iniciar a instalação do pacote. Na janela do VirtualBox clique em "Instalar".
  </p>
  <p align="center">
  <img src="https://github.com/user-attachments/assets/acd8a7c2-bbd1-43e4-8bce-1020c1077c13" alt="VBoxManage versão">
</p>

---
  
**`2. Vagrant`**
<br/>
