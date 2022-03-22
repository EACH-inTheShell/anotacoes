# Instalando Linux

Grande parte das ferrmentas que vamos usar para as atividades do grupo serão ferrmentas feitas para linux, portanto para que todos os novos integrantes acompanhar nossos encontros, ter linux instalado em alguma máquina disponível vai ser necessário para o decorrer das atividades.

## Opções

Primeiro vamos começar com as opções, não existe apenas essas opções para usar linux mas recomendamos essas opções para user durante as atividades em grupo! Um *WSL* pode dificultar durante as atividades do grupo, já que alguns protocolos usados vão precisar de *GUI* por exemplo o protocolo `rdp` (não queremos focar muito na parte de fazer um *WSL* funcionar com `rdp` por exemplo, pois vai atrasar as atividades da semana).

Lembrando que, se as ferramentas de segurança não forem usadas no dia-a-dia, não é uma boa prática usar um *SO* (Sistema Operacional) focado em `pentesting` ou `segurança da informação` como *SO* principal.

- `Bare Metal`: Instalar um único *SO* no seu computador (Windows, Linux, MACOS, etc...)
- `Dual Boot`: Instalar dois *SO* no seu computador

## Distribuições

Algumas distribuições que recomendamos para usar nas atividades, pois elas já vem com ferramentas de `segurança da informação`:

- `Kali` (Recomendado)
- `Parrot` (Recomendado)
- `Black Arch`

O `Black Arch` em específico tem uma curva maior de aprendizado para quem não está acostumado com *Linux*, então recomendamos o `Black Arch` para pessoas que já tem alguma familiaridade com distribuições baseadas em `Arch`. O `Black Arch` pode ser instalado e configurado do zero, ou caso já tenha uma distribuição baseada em `Arch` ela pode ser transformada em `Black Arch` ativando os repositórios do `Black Arch`.

Algumas diferenças entre as distribuições `Parrot` e `Kali` são destacadas nesse [fórum](https://plus.diolinux.com.br/t/kali-linux-vs-parrot-os/5100)

## Como instalar

Caso a opção seja fazer um dualboot existe [esse tutorial](https://www.youtube.com/watch?v=6D6L9Wml1oY) não oficial.

Outras opções de `Bare Metal`, `Dual Boot` e `Virtual machine` podem ser encontradas abaixo:

- [Kali](#Kali)
- [Parrot](#Parrot)
- [Black Arch](#Black-Arch)


# [Kali](https://www.kali.org/)

O `Kali` é uma distribuição `GNU/Linux` baseada no Debian que vem com [várias ferramentas](https://www.kali.org/tools/) de segurança da informação.

## Bare Metal

#### Oficial

Para instalar o `Kali` no computador como sistema operacional principal, existe o tutorial do [site oficial](https://www.kali.org/docs/installation/hard-disk-install/).

#### Não-Oficial (Português)
- [Video no youtube](https://www.youtube.com/watch?v=EQqjFIZZQt4)

## Dual Boot

#### Oficial

Para instalar o `Kali` com outro linux no sistemaa, existe o tutorial do [site oficial](https://www.kali.org/docs/installation/dual-boot-kali-with-linux/).

## Virtual Machine

#### Oficial

Para instalar o `Kali` em uma máquina virtual, existem tutoriais no [site oficial](https://www.kali.org/docs/virtualization/).

# [Parrot](https://www.parrotsec.org/)

O `Parrot` é uma distribuição `GNU/Linux` baseada no Debian construída por desenvolvedores e especialistas em segurança para construir um `framework` de ferramentas de segurança da informação.

## Bare Metal

#### Oficial

Para instalar o `Parrot` no computador como sistema operacional principal, existe o tutorial do [site oficial](https://www.parrotsec.org/docs/installation.html).

#### Não-Oficial

- [youtube passo-a-passo](https://www.youtube.com/watch?v=xTuRuIFNrBQ)

## Virtal Machine

#### Oficial

Para instalar o `Parrot` em uma máquina virtual, existe o tutorial do [site oficial](https://www.parrotsec.org/docs/installation.html).

# [Black-Arch](https://www.blackarch.org/)

O `Black Arch` é uma distribuição baseada em `Arch` com [2804 ferramentas](https://www.blackarch.org/tools.html) podendo ser instaladas individualmente ou em grupos, além disso `Black Arch` é compatível com as instalações baseadas em `Arch` existentes.

## Existing Arch installation

Em uma distribuição `Arch` existente, é preciso adicionar os repositórios de ferramentas `Black Arch` e para isso existe o [tutorial oficial](https://www.blackarch.org/downloads.html#install-repo).

## Bare Metal

#### Oficial

Para instalar o `Black Arch` no computador como sistema operacional principal, existe o tutorial do [site oficial](https://www.blackarch.org/blackarch-install.html).
