# Desafio_Cibersecurity_Setoolkit_Phishing
Phishing para capturar senha e login de uma pagina da internet

Exemplo Prático: Configuração de Phishing com o Site do Facebook

Ferramentas Utilizadas:

Kali Linux (https://www.kali.org/)
Setoolkit (ferramenta pré-instalada no Kali Linux)

Pontos Importantes:

Se estiver utilizando uma máquina virtual (VM), configure a rede no modo Bridged Adapter (Inglês) ou Placa de Modo Bridge (Português).
Este método funciona apenas para dispositivos conectados à mesma rede.
É necessário clonar a página específica onde o usuário insere o login e senha.

Resumo do Procedimento: Configuração do Setoolkit para Phishing no Kali Linux
Obtenha acesso root: sudo su
Inicie o Setoolkit: setoolkit
Selecione o tipo de ataque: Social-Engineering Attacks
Escolha o vetor de ataque: Web Site Attack Vectors
Configure o método de ataque: Credential Harvester Attack Method
Escolha o método de clonagem: Site Cloner
Verifique o endereço IP da máquina: ifconfig
Insira a URL do site a ser clonado: http://www.facebook.com
Envie o IP da máquina para um alvo.

Detalhamento do Procedimento

Passo 1: Obtenha acesso root
No terminal, insira o comando: sudo su. O sistema solicitará a senha do administrador.
![401180923-eabaade4-3d43-425a-bea8-6172b8bc7688](https://github.com/user-attachments/assets/6ccfae83-a260-4f5c-bcd2-8ec0d99c9048)

