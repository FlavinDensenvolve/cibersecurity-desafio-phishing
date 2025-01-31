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
