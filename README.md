# cibersecurity-desafio-phishing
Projeto do desafio de phishing com SEToolkit – curso de cibersegurança, usando Kali Linux

# Desafio de Clonagem de Site com SEToolkit no Kali Linux

Este repositório contém o registro completo do desafio prático de clonagem de site utilizando o **SEToolkit (Social-Engineer Toolkit)** no Kali Linux, como parte do curso/laboratório.

---

## ✅ Comandos Utilizados no Kali Linux com SEToolkit

### Acesso ao modo root:
```bash
sudo su

setoolkit
```
Execução do SEToolkit:
```bash
setoolkit
```
Passos dentro do SEToolkit:
1. Selecionar a opção 1: Social-Engineering Attacks
```bash
1
```
2. Selecionar a opção 2: Website Attack Vectors
```bash
2
```
3. Selecionar a opção 3: Credential Harvester Attack Method
```bash
3
```
4. Selecionar a opção 2: Site Cloner
```bash
2
```

Definir o site a ser clonado:
• O SEToolkit exibirá o IP da máquina automaticamente.
• Em seguida, solicitará a URL do site a ser clonado:

⚠️ Utilize o protocolo HTTP (sem 'S') para evitar erros:
```bash
http://www.facebook.com
```

Acessar a página clonada no navegador:
Sempre acessar com o protocolo HTTP:
```bash
http://192.168.100.129
```


## ✅ Observações Importantes

- Este projeto tem finalidade exclusivamente educacional, realizado em ambiente controlado e autorizado.

- Após o usuário inserir login e senha na página clonada, o SEToolkit realiza um redirecionamento automático (redirect) para o site original.

- Esse comportamento gera um efeito visual chamado "flicker" (ou "piscada de página") entre programadores — um leve flash ou troca rápida de página, que geralmente passa despercebido pelos usuários leigos.

- A clonagem funciona apenas na rede local com IPs privados como 192.168.x.x.

- Para acessos externos, seriam necessárias configurações adicionais, como redirecionamento de portas no roteador ou VPN.


## ✅ Prints
As capturas de tela dos principais passos foram incluídas na pasta /images.


## ✅ Conclusão
- Este repositório documenta todo o processo de utilização do SEToolkit no Kali Linux, conforme orientado no desafio, e pode servir como referência para estudos futuros.

⛔ Importante: Nunca utilize essas técnicas em ambientes ou sistemas sem autorização explícita. Uso não autorizado é crime.

