---
title: Roadmap para iniciantes
authors:
	- Mayfly
	- Tsuyoshi
	- Uxie
	- Vilela
---

# Áreas

## Linux

Linux é o sistema operacional mais utilizado por hackers (mas não o único, você usa o que quiser).

Ele pode ser rodado diretamente no pc (bare metal) ou pode também ser rodado em diferentes ambientes.

O mais importante do Linux é saber se virar no terminal; a principal interface usada no sistema operacional.

### Essenciais

- Kit básico de sobrevivência para terminal
	- cd
	- ls
	- cat/less
	- mv/cd
	- mkdir/touch
- find
- file
- grep
- sudo/su
- head/tail

### Ambientes

- Sistemas operacionais: Kali, Parrot, Black Arch
- Como/onde rodar: WSL2, VM, Containers, Dual boot, Live USB

### Ferramentas Úteis

- multiplexadores: Terminator, Tmux, Screens
- editores de texto: Vim, Nano, Emacs
- terminais (opcionais): Alacritty, Kitty, Terminator

### CTFs

#### OverTheWire

- [Bandit (0 -> 10)](https://overthewire.org/wargames/bandit/)

#### PicoCTF

- [flag\_shop](https://play.picoctf.org/practice?page=1&search=flag_shop)
- [extensions](https://play.picoctf.org/practice?page=1&search=extentions)
- [First Grep](https://play.picoctf.org/practice?page=1&search=First%20Grep)

#### TryHackMe

##### Recomendados

- [Linux Fundamentals](https://www.tryhackme.com/module/linux-fundamentals)
- [The find command](https://tryhackme.com/room/thefindcommand)

##### Opcionais

- [Tmux](https://tryhackme.com/room/rptmux)
- [Linux Strength Training](https://tryhackme.com/room/linuxstrengthtraining)

## Criptografia/Hashes

A importância da criptografia está em proteger nossos dados de pessoas indesejadas.

Mesmo que um sistema criptográfico seja seguro não é certeza que a pessoa que esteja usando esse sistema use ele de forma correta, isso cria aberturas para que a gente consiga quebrar eles.

Por isso saber como as funções criptográficas funcionam e os suas fraquezas faz com que a gente não caia nos erros comuns ao usar elas.

- Diferença
- ASCII
- HEX/BIN
- Cifras históricas (operam em letras):
	- Cifra monoalfabética (Caesar)
	- Cifra polialfabética (Vigènere e Affine)
- Cifras modernas (operam em bits):
	- Cifra de fluxo
	- Cifra em blocos
	- TLS/SSL
	- 3DES
	- AES
- Princípio de Kerckhoff
	- "Um sistema criptográfico deve ser seguro mesmo que tudo sobre o sistema, exceto a chave, seja de conhecimento público"
- Ataques de criptoanálise clássicas:
	- Força-Bruta (Analisar inputs e outputs)
	- Analítico (Analisar a função)
- Tópicos matemáticos:
	- Teoria dos números
	- Álgebra Modular
- Como funcionam senhas (exemplo de hash)
- Como funciona TLS/SSL (exemplo de criptografia)

### CTFs

#### PicoCTF

- [2Warm](https://play.picoctf.org/practice?page=1&search=2Warm)
- [Warmed Up](https://play.picoctf.org/practice?page=1&search=Warmed%20Up)
- [Lets Warm Up](https://play.picoctf.org/practice?page=1&search=Lets%20Warm%20Up)
- [Bases](https://play.picoctf.org/practice?page=1&search=Bases)
- [caesar](https://play.picoctf.org/practice?page=1&search=caesar)
- [Easy1](https://play.picoctf.org/practice?page=1&search=Easy1)
- [13](https://play.picoctf.org/practice?page=1&search=13)
- [la cifra de](https://play.picoctf.org/practice?page=1&search=la%20cifra%20de)

#### SDS Labs - Backdoor

- [TEST](https://backdoor.sdslabs.co/challenges/TEST)

#### TryHackMe

- [Crack the hash](https://tryhackme.com/room/crackthehash)

## Redes

Redes é a base da comunicação entre computadores. Ela é o que te permite acessar um computador que não o seu (sendo esse acesso esperado ou não).

Sabendo redes você tem uma noção básica de como funciona todo o tipo de comunicação entre computadores e consegue entender mais facilmente limitações e protocolos que agem sobre ela.

### Teoria

- LAN/WAN
- Portas
- TCP/UDP
- Modelos OSI e TCP/IP
- Protocolos:
	- DNS
	- HTTP/HTTPS
	- SSH
	- FTP/SMB

### Ferramentas

- netcat
- openssl
- nmap

### CTFs

#### PicoCTF

- [shark on wire 1](https://play.picoctf.org/practice?page=1&search=shark%20on%20wire%201)
- [shark on wire 2](https://play.picoctf.org/practice?page=1&search=shark%20on%20wire%202)

#### TryHackMe

- [Intro to Networking](https://tryhackme.com/room/introtonetworking)

## Web

Hoje em dia, quem não está no ambiente web? Seja grandes empresas (como Facebook) e até a padaria da esquina. 

Apesar da diferença entre elas, é preciso ter um cuidado para preservar informações da empresa e de seus clientes. 

É importante saber o básico de como a web funciona e os ataques mais comuns para, assim, aprender a atacar e defender.

### Conceitos importantes

Aqui veremos alguns conceitos essenciais para a sobrevivência web.

- Métodos 
	- GET
	- POST
	- PUT
	- PATCH
	- DELETE
- Códigos de status
	- 100 >= 199
	- 200 >= 299
	- 300 >= 399
	- 400 >= 499
	- 500 >= 599
- HTTP Request / Response
- Cookies
- Load Balancer (LB)

### OWASP Top 10

OWASP é um projeto open source que reúne documentações, metodologias, ferramentas e outros conhecimentos relacionados à segurança de aplicações web. 

O Top 10 representa as 10 falhas de segurança web mais aplicadas no dia a dia. 

1. Injeção
2. Quebra de Autenticação
3. Exposição de Dados Sensíveis
4. Entidades Externas de XML (XXE) 
5. Quebra de Controlo de Acessos
6. Configurações de Segurança Incorretas
7. Cross-Site Scripting (XSS)
8. Desserialização Insegura
9. Utilização de Componentes Vulneráveis
10. Registo e Monitorização Insuficiente

### CVEs

Common Vulnerabilities and Exposures (CVE) são registros públicos de vulnerabilidades e exposições conhecidas.

Quando esse termo é usado, pressupõe-se que se trata de uma vulnerabilidade já catalogada e, assim, é possível já encontrar uma forma descoberta de como explorá-la.

- Mitre
- ExploitDB

### Ferramenta de desenvolvedor

- Inspecionar 
- Console
- Debugger
- Network
- Memory
- Storage

### Como funcionam servidores &lt; REQ: Redes

- Apache
- NodeJs

### CTFs

#### OverTheWire

- [Natas (0 -> 10)](https://overthewire.org/wargames/natas/)

#### PicoCTF

- [insp3ct0r](https://play.picoctf.org/practice?page=1&search=insp3ct0r)
- [where are the robots](https://play.picoctf.org/practice?page=1&search=where%20are%20the%20robots)
- [logon](https://play.picoctf.org/practice?page=1&search=logon)
- [picobrowser](https://play.picoctf.org/practice?page=1&search=picobrowser)
- [dont-use-client-side](https://play.picoctf.org/practice?page=1&search=dont-use-client-side)
- [Client-side-again](https://play.picoctf.org/practice?page=1&search=Client-side-again)

#### Backdoor

- [2013-web-50](https://backdoor.sdslabs.co/challenges/2013-WEB-50)
- [authorized persons only](https://backdoor.sdslabs.co/challenges/CK)
- [browser](https://backdoor.sdslabs.co/challenges/BRWSR)
- [robot](https://backdoor.sdslabs.co/challenges/ROBOT)
- [batman](https://backdoor.sdslabs.co/challenges/BATMAN)

#### TryHackMe

- [Web Fundamentals](https://tryhackme.com/room/webfundamentals)
- [Owasp Top 10](https://tryhackme.com/room/owasptop10)

## OSINT
O recohecimento é uma das partes mais importantes na busca por vulnerabilidades em segurança da informação. OSINT trata disso: técnicas para se coletar informações sobre pessoas e empresas (por exemplo), usando fontes abertas e disponíveis na web.

- Google Dorking
- Metadata Analysis

### CTFs

#### TryHackMe

- [OhsInt](https://tryhackme.com/room/ohsint)
- [Intro to Research](https://tryhackme.com/room/introtoresearch)
- [Google Dorking](https://tryhackme.com/room/googledorking)
- [Advent of Cyber 2 (Task 19)](https://tryhackme.com/room/adventofcyber2)

## Scripting

- Python (2 e 3)
- Bash
- Qualquer outra linguagem que vocês queiram

### CTFs

#### PicoCTF

- [like1000](https://play.picoctf.org/practice?page=1&search=like1000)

#### TryHackMe

- [Ninja Skills](https://tryhackme.com/room/ninjaskills)

#### inTheShell_

- [EiTS Resources page](http://intheshell2.duckdns.org:1337/exercicios_script.pdf)

## Computação Forense


- Esteganografia
- Números mágicos

### CTFs

#### TryHackMe

- [CC: Steganograohy](https://tryhackme.com/room/ccstego)

#### PicoCTF

- [Glory of the Garden](https://play.picoctf.org/practice?page=1&search=Glory%20of%20The%20Garden)
- [So Meta](https://play.picoctf.org/practice?page=1&search=So%20Meta)
- [strings it](https://play.picoctf.org/practice?page=1&search=strings%20it)
- [What Lies Within](https://play.picoctf.org/practice?page=1&search=What%20Lies%20Within)

#### backdoor:

- [nosignal](https://backdoor.sdslabs.co/challenges/NO-SIGNAL)
- [sound](https://backdoor.sdslabs.co/challenges/SOUND)

