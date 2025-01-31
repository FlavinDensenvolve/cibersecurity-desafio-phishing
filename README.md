![Captura de tela 2025-01-31 000225](https://github.com/user-attachments/assets/5704cef3-8c95-4f33-a5b8-51c6e22aca3a)
![Captura de tela 2025-01-31 000207](https://github.com/user-attachments/assets/17bc1a1d-8b91-45f0-939c-091d4d96d96b)
![Captura de tela 2025-01-31 000148](https://github.com/user-attachments/assets/421adda6-4ce8-4e88-9c72-bf79d99399c2)
![Captura de tela 2025-01-31 000121](https://github.com/user-attachments/assets/73af08d9-a761-4760-8b2a-9cc30317282e)
![Captura de tela 2025-01-31 000104](https://github.com/user-attachments/assets/52c3943a-c2c3-454a-af0f-ccaaf5ccabe4)
![Captura de tela 2025-01-30 233512](https://github.com/user-attachments/assets/a213089f-5d73-4a29-941b-cda54e5eb3b9)
![Captura de tela 2025-01-30 220343](https://github.com/user-attachments/assets/92826680-655d-4e11-94fe-eda421b96824)
# cibersecurity-desafio-phishing

## Introdução
====================

Este é um guia para realizar um ataque de phishing no Facebook utilizando ferramentas disponíveis no Kali Linux.
Este ataque visa capturar senhas do usuário através de técnicas de engenharia social.

## Ferramentas
-------------

*   Kali Linux: O sistema operacional usado para executar o ataque.
*   setoolkit: Uma ferramenta que fornece uma interface gráfica simples para realizar tarefas mais complexas, como
a extração do conteúdo da rede local.

## Configurando o Phishing no Kali Linux
--------------------------------------

### Ative o Setoolkit e Inicie-o

1.  Ative o setoolkit: `setoolkit - Active`
2.  Inicie o Kali Linux: `kali-linux`

### Tipos de Ataque e Vetores de Ataque
--------------------------------------

*   Tipo de ataque: Social-Engineering Attacks
*   Vetor de ataque: Web Site Attack Vectors
*   Método de ataque: Credential Harvester Attack Method
*   Método de ataque: Site Cloner

## Obtenha o Endereço da Máquina
-------------------------------------

### Verifique o Endereço da Rede Local

1.  Verifique o endereço da rede local: `ifconfig`

URL para Clone
-------------

A URL utilizada para clonear o site do Facebook é http://www.facebook.com.

### Exemplo de Como Exterminar O Phishing

1.  Inicie o comando para obter o endereço da máquina: `arp -a`
2.  Verifique se existem alguma entrada relacionada ao Facebook na lista de entradas do endereço IP: `nmap
facebook.com`
3.  Faça uma conexão no site do Facebook e obtenha as credenciais do usuário para extrair os senhas.
4.  Utilize a ferramenta `ss` para criar um clone do site do Facebook:
    ```bash
sudo -u root ss -lB | sudo bash
```
### Conclusão

Este ataque de phishing é uma forma de capturar informações sensíveis, como senhas, utilizando técnicas de
engenharia social. No entanto, é importante notar que este ataque não deve ser realizado em situações reais ou
legítimas, pois pode causar danos à segurança e confiança dos usuários.
