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

Passo 2: Inicie o Setoolkit
Digite o comando: setoolkit. Ao abrir pela primeira vez, aceite os termos de uso da ferramenta digitando YES.

![401181540-4caa7c67-207d-4e9a-b8c1-4b0b490841c4](https://github.com/user-attachments/assets/6f3881e4-cc3d-4582-bb6f-28a9ba480113)

Passo 3: Escolha o tipo de ataque
Selecione a opção 01) Social-Engineering Attacks no menu principal.

![401182725-382ca0bb-b191-4661-9f62-1b4cc21e1367](https://github.com/user-attachments/assets/e2a24b42-0c90-4b69-b6f0-af6d98ef4d1a)

Passo 4: Configure o vetor de ataque
Escolha a opção 02) Web Site Attack Vectors. 

![401183645-6894a2e5-94c9-41c5-99a3-f894f51a3827](https://github.com/user-attachments/assets/579a3bb1-d34e-404b-9169-a0e343a0b2ef)

Passo 5: Escolha o método de ataque
Selecione 03) Credential Harvester Attack Method. 

![401184822-b2cfab7f-9671-4ab0-a752-18da8e9e843e](https://github.com/user-attachments/assets/9f349a16-c926-42c3-b48d-c417340c1e1b)

Passo 6: Configure o método de clonagem
Selecione a opção 02) Site Cloner.

![401185511-49fd500e-c21f-431b-bc30-69a8ca044a16](https://github.com/user-attachments/assets/d052b209-1340-465b-9de5-b116cf8b6988)

Passo 7: Identifique o endereço IP
A ferramenta exibirá o IP da máquina que será utilizado como servidor para capturar as credenciais. Mantenha as configurações padrão e pressione Enter. O IP da máquina será exibido na tela.

![401188127-0fe7af53-6ee9-4f50-bb81-08d9988c3894](https://github.com/user-attachments/assets/718c864d-107a-4ecf-8363-0667747703d6)

Passo 8: Insira a URL a ser clonada
Digite o endereço do site que deseja clonar. Para este exemplo, insira: http://www.facebook.com.

![401189293-ae36dc56-d1b5-449b-b386-312bc1042054](https://github.com/user-attachments/assets/244c8a5c-0df4-47df-9891-69376cf12634)

Passo 9: Finalize a configuração
Pressione Enter para concluir. A ferramenta estará pronta, aguardando que um usuário acesse o link clonado e insira as credenciais.

![401190051-bde4993f-7fe6-4333-bc1d-fb0ee8e40af0](https://github.com/user-attachments/assets/fc4b44a8-16ff-4f27-98d7-2c85da505301)

Passo 10: Envie o IP para um alvo
Compartilhe o IP exibido no Passo 7 com a pessoa que deseja que acesse o site clonado.

![402288236-eb9ea83b-5a06-4103-8ddc-50138b0e6978](https://github.com/user-attachments/assets/e2642123-ff7a-476a-b404-bd5ab8013127)










