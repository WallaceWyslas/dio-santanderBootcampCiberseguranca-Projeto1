# Objetivo
Utilizar uma ferramenta de Phishing para captura de login e senhas

# Resultado
Utilizei o sistema Kali Linux, instalado em uma VM, e o framework [setoolkit](https://github.com/trustedsec/social-engineer-toolkit) para esse processo. Para isso, segui as seguintes etapas:
- No CLI utilizei o comando ```setoolkit```;
- Entrei nas seguintes opções:
  - ```1) Social-Enginnering Attacks```;
  - ```2) Website Attack Vectors```;
  - ```3) Credential Harvester Attack Method```;
  - ```1) Web Templates```;
  - ```2) Google```.

Com isso, é possível criar uma interface parecida com a do Google, que assim que o usuário inserir o **Login** e a **Senha**, o sistema captura essas informações da seguinte forma:

![image](https://github.com/user-attachments/assets/514c31eb-445d-4717-8048-44f7ccde3492)

![image](https://github.com/user-attachments/assets/ee756dcd-ddaf-4d59-bf68-ed80c4ea71b7)


Para um melhor resultado, seria interessante criar uma rede Wi-Fi própria, que assim que o usuário entrasse na rede, era direcionado para a  página de credenciais do Google.
