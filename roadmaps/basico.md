# Roadmap para iniciantes

## Pentest

### CTFs

- TryHackMe
	- [Pentesting Fundamentals](https://tryhackme.com/room/pentestingfundamentals)
	- [Principles of Security](https://tryhackme.com/room/principlesofsecurity)

## Linux

Linux é o sistema operacional que roda na maioria dos servidores encontrados na internet, e também muito utilizado por hackers por facilitar o desenvolvimento e distribuição de ferramentas.

Ele pode ser rodado diretamente no computador sendo instalado sozinho (bare metal), em conjunto com outro sistema operacional (dual boot) ou rodado diretamente de um *pendrive* (live boot), ou pode também ser rodado em ambientes virtualizados como em uma maquina virtual ou através do WSL2 no windows.

O mais importante do Linux é saber se virar no terminal, pois vai ser o principal método de interação do usuário (você) com os computadores pessoais e servidores.

### Ferramentas essenciais

- Kit básico de sobrevivência no terminal
	- cd
	- ls
	- cat
	- mv/cp
	- mkdir/touch
- find
- file
- grep
- sudo/su/doas
- head/tail
- less

### Ambientes

- Distribuições Linux: Kali, Parrot, Black Arch
- Como/onde rodar: WSL2, VM, Containers, Dual boot, Live USB

### Algumas ferramentas uteis

Essas servem para melhorar sua experiencia com o Linux e aumentar sua produtividade.

- shells: bash, zsh, fish, dash
- editores de texto: Vim, Nano, Emacs
- multiplexadores: Terminator, Tmux, Screens
- simuladores de terminal: Alacritty, Kitty, Terminator

### CTFs

- OverTheWire
	- [Bandit (0 -> 10)](https://overthewire.org/wargames/bandit/)
- TryHackMe
	- [Linux Fundamentals 1](https://tryhackme.com/room/linuxfundamentalspart1)
	- [Linux Fundamentals 2](https://tryhackme.com/room/linuxfundamentalspart2)
	- [Linux Fundamentals 3](https://tryhackme.com/room/linuxfundamentalspart3)
- PicoCTF
	- [flag\_shop](https://play.picoctf.org/practice?page=1&search=flag_shop)
	- [extensions](https://play.picoctf.org/practice?page=1&search=extentions)
	- [First Grep](https://play.picoctf.org/practice?page=1&search=First%20Grep)

## Redes

Redes é a base da comunicação entre computadores. Ela é o que te permite se comunicar com um outro computador.

Sabendo redes você tem uma noção básica de como funciona todo o tipo de comunicação entre computadores e consegue entender mais facilmente limitações e protocolos que agem sobre ela.

### Teoria

- Redes/subredes (LAN, MAN e WAN)
- Portas
- TCP/UDP
- Modelos OSI e TCP/IP
- Protocolos (DNS, HTTP, ICMP...)

### Ferramentas

- netcat/ncat
- nmap
- wireshark

### CTFs

- TryHackMe
	- [What is Networking?](https://tryhackme.com/room/whatisnetworking)
	- [Networking](https://tryhackme.com/room/bpnetworking)
	- [Intro to LAN](https://tryhackme.com/room/introtolan)
	- [Introductory Networking](https://tryhackme.com/room/introtonetworking)
- PicoCTF
	- [shark on wire 1](https://play.picoctf.org/practice?page=1&search=shark%20on%20wire%201)
	- [shark on wire 2](https://play.picoctf.org/practice?page=1&search=shark%20on%20wire%202)

## Web

Hoje em dia, quem não está no ambiente web? Seja grandes empresas (como Facebook) e até a padaria da esquina.

Apesar da diferença entre elas, é preciso ter um cuidado para preservar informações da empresa e de seus clientes.

É importante saber o básico de como a web funciona e os ataques mais comuns para, assim, aprender a atacar e se defender.

### Conceitos importantes

Aqui veremos alguns conceitos essenciais para a sobrevivência web.

- HTTP Request / Response
- Métodos
- Códigos de status
- Parâmetros
- Cookies

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

### Como funcionam servidores < REQ: Redes

- Apache
- NginX
- NodeJs

### CTFs

- OverTheWire
	- [Natas (0 -> 10)](https://overthewire.org/wargames/natas/)
- TryHackMe
	- [Web Fundamentals](https://tryhackme.com/room/webfundamentals)
	- [DNS in detail](https://tryhackme.com/room/dnsindetail)
	- [HTTP in detail](https://tryhackme.com/room/httpindetail)
	- [How websites work](https://www.tryhackme.com/room/howwebsiteswork)
	- [Owasp Top 10](https://tryhackme.com/room/owasptop10)
- PicoCTF
	- [insp3ct0r](https://play.picoctf.org/practice?page=1&search=insp3ct0r)
	- [where are the robots](https://play.picoctf.org/practice?page=1&search=where%20are%20the%20robots)
	- [logon](https://play.picoctf.org/practice?page=1&search=logon)
	- [picobrowser](https://play.picoctf.org/practice?page=1&search=picobrowser)
	- [dont-use-client-side](https://play.picoctf.org/practice?page=1&search=dont-use-client-side)
	- [Client-side-again](https://play.picoctf.org/practice?page=1&search=Client-side-again)
- Backdoor
	- [2013-web-50](https://backdoor.sdslabs.co/challenges/2013-WEB-50)
	- [authorized persons only](https://backdoor.sdslabs.co/challenges/CK)
	- [browser](https://backdoor.sdslabs.co/challenges/BRWSR)
	- [robot](https://backdoor.sdslabs.co/challenges/ROBOT)
	- [batman](https://backdoor.sdslabs.co/challenges/BATMAN)

### Materiais auxiliares no desenvolvimento de CTFs

Nestes materiais, há descrição, exemplos e usos dos conceitos e ferramentas utilizados em diferentes CTFs para facilitar o aprendizado. 

- [Natas 0 ao 8](./web/Onboarding-web.pdf)