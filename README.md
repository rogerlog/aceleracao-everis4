# Aceleração Global Dev Everis #4 :rocket:

Anotações das aulas. :pencil2::books:

- [Abertura - Como trabalhar em um ambiente ágil e global](#abertura---como-trabalhar-em-um-ambiente-ágil-e-global)
- [Linux: A introdução ao sistema operacional](#linux---a-introdução-ao-sistema-operacional)
- [Shell script - Manipulando Arquivos](#shell-script---manipulando-arquivos)
- [Monitoramento de clusters Hadoop de alto nível com HDFS e Yarn](#monitoramento-de-clusters-hadoop-de-alto-nível-com-hdfs-e-yarn)
- [Orquestrando ambientes de big data distribuídos com Zookeeper, Yarn e Sqoop](#orquestrando-ambientes-de-big-data-distribuídos-com-zookeeper-yarn-e-sqoop)
- [Como realizar consultas de maneira simples no ambiente complexo de Big Data com HIVE e Impala](#como-realizar-consultas-de-maneira-simples-no-ambiente-complexo-de-bigdata-com-hive-e-impala)
- [Explorando o poder do NoSQL com Cassandra e Hbase](#explorando-o-poder-do-nosql-com-cassandra-e-hbase)
- [Intensivo de Python - O mínimo que você precisa saber](#intensivo-de-python---o-mínimo-que-você-precisa-saber)
- [Trabalhando com serviços de mensageria real time com Python e Kafka na prática](#trabalhando-com-serviços-de-mensageria-real-time-com-python-e-kafka-na-prática)
- [Processando grandes conjuntos de dados de forma paralela e distribuída com Spark](#processando-grandes-conjuntos-de-dados-de-forma-paralela-e-distribuída-com-spark)
- [Criando pipelines de dados eficientes - Parte 1](#criando-pipelines-de-dados-eficientes---parte-1)
- [Criando pipelines de dados eficientes - Parte 2](#criando-pipelines-de-dados-eficientes---parte-2)
- [Orquestrando Big Data em Ambiente de Nuvem](#orquestrando-bigdata-em-ambiente-de-nuvem)
- [Scala: o poder de uma linguagem multiparadigma](#scala-o-poder-de-uma-linguagem-multiparadigma)
- [O que você precisa saber para construir APIs verdadeiramente restfull](#O-que-você-precisa-saber-para-construir-APIs-verdadeiramente-restfull)
- [Graduação - habilidades que diferenciam um sênior na everis](#graduação---habilidades-que-diferenciam-um-sênior-na-everis)





<br><br><br>

------

## Abertura - Como trabalhar em um ambiente ágil e global

*Experts com grande experiência em projetos de missão crítica compartilham os princípios e competências essenciais para o dev desenvolver habilidades globais.*

:calendar: 18/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

*Notas da live*

#### Qualidades de um bom desenvolvedor (Soft Skills)

https://imasters.com.br/desenvolvimento/as-5-qualidades-de-um-bom-desenvolvedor



#### Metodologia Ágil

https://neilpatel.com/br/blog/metodologia-agil/

https://robsoncamargo.com.br/blog/o-que-e-metodologia-agil



<br><br><br>

------

## Linux - A introdução ao sistema operacional

​	:hourglass: 10 horas

<br>

#### Introdução ao Linux e configuração inicial

- **História do Linux**

Criado 1991 por Linus Torvalds. O Linux é o Kernel ou Núcleo do Sistema Operacional. Ele é um sistema Multitarefa e Multiusuário.

O Linux pode ser *distribuído* por empresas, organizações ou mesmo pessoas, que podem colocar características no SO.

O Ubuntu é um SO de código aberto que é desenvolvido pela Canonical com base no kernel Linux.

- **Instalação e configuração**

VMWare 15

Ubuntu 20.04

- **Apresentação do Sistema Operacional**
  - Ambiente
  - LibreOffice/Navegadores
  - Software Updater
- **Configuração do Sistema Operacional - Parte 1**

Em Settings... Notifications... Search...  Privacy

Diagnostics - Enviar relatório de erros.

Atalhos do Ubuntu - Settings/Keyboard Shortcuts

- **Configuração do Sistema Operacional - Parte 2**

Configurando para portugues em Settings

Acesso Universal

Aplicativos Padrão

- **Certifique seu Conhecimento**

  Marque a alternativa com 3 principais distribuições Linux: 	*Ubuntu, Debian e Suse.*

  O que é o Linux?	*O Linux é o Kernel do Sistema Operacional.*	

  O que é o Ubuntu Linux?	*É uma distribuição baseada no Kernel Linux, tendo sua base no Debian e amplamente aceita em todas as comunidades de usuários.*

  Quem criou o Linux? 	*Linus Torvalds.*

  O que é uma "distro"? 	*Uma distro é uma distribuição baseada no Kernel Linux.*

  O que é um software de virtualização de Sistemas Operacionais? 	*É um software que permite criar máquinas virtuais com um ou mais sistemas dentro de um único ambiente.*

  Qual a empresa criadora e mantenedora do Ubuntu? 	*Canonical.*

  Marque abaixo a alternativa correta contendo 3 programas pré instalados no Ubuntu 20.04: 	*Mozilla Firefox, Rhythmbox e Thunderbird.*	

  O que é a Doca? *A Doca e a barra de tarefas do Ubuntu Linux.*	

  Em qual sistema o criador do Linux se baseou para sua criação?	*Unix.*

#### Conhecendo o terminal Linux e seus atalhos

- **Conhecendo o terminal e primeiros comandos**

Terminal, Shell ou konsole é uma linha de comando onde podemos executar programas específicos do Linux. CTRL + ALT +T no Ubuntu

man sudo_root

pwd *Diretório local*

- **Atalhos**

Ctrl+C Cancela o comando atual

Ctrl+U Apaga a linha inteira

- **Revisão do Conteúdo**

cd~ *Muda para diretório pessoal*

history *Histórico de comandos*

ls -l *Opção lista longa com detalhes*

<u>*Exercícios Práticos*</u>

1) Abra o Terminal
2) Crie uma Pasta de nome Ubuntu dentro da Pasta Documentos
3) Mova esta Pasta para o diretório Pessoal
4) Crie um arquivo vazio de nome teste.txt dentro da Pasta Ubuntu
5) Renomeie este Arquivo como linux.txt
6) Crie uma cópia deste arquivo na Pasta Downloads
7) Exiba todos os comandos digitados no Terminal
8) Execute a ajuda do comando ls
9) Execute o manual do comando mv
10) Pare a execução do manual
11) Saia do Terminal utilizando sequência de teclas
12) Exclua a pasta Ubuntu
13) Exclua o arquivo linux.txt 
14) Limpe o terminal
15) Utilize o comando para sair do terminal

- **Certifique seu conhecimento**

  Qual o comando lista arquivos e diretórios no Linux? 	*ls*

  O que é o terminal no Linux?	*O terminal, Shell ou Konsole, é uma ferramenta de linha de comando do Linux.*

  Qual comando cria diretórios no Linux?	*mkdir*

  Qual das alternativa abaixo move um diretório de nome Ubuntu para a pasta pessoal?	*mv Ubuntu ~*

  Qual comando remove um arquivo do Linux?	*rm*

  Qual comando abaixo repete o ultimo comando digitado no terminal?	*!!*

  Qual comando utilizado para copiar um arquivo?	*cp*

  Qual a sequência de teclas correta para acessar o terminal no Linux?	*CTRL + ALT + T*

  Qual o comando usado para mover ou renomear arquivos ou diretórios?	*mv*

  Qual combinação de teclas de atalho finaliza o terminal?	*CTRL + D*

#### Comandos para manipulação de arquivos e textos e redirecionamento

- **Lidando com arquivos .txt**

nano teste.txt

​		ctrl + g *Exibe as informações e comandos do nano*

​		ctrl + j *Justifica o texto*

​		alt + u *desfazer última ação*

​		ctrl + o *salva o arquivo*

​		ctrl + x *fechar arquivo*

<u>cat</u> exibe conteúdo do arquivo e <u>tac</u> exibe o conteúdo inverso de um arquivo

- **Propriedades do arquivo .txt e comandos de datas**

head teste.txt *Exibe as primeiras 10 linhas*

tail teste.txt *Exibe as 10 ultimas linhas*

tail teste.txt > distros.txt *Cria um arquivo com a saída do comando tail, ou head*

cal *Calendário do mês corrente*

cal > calendario.txt *Cria um arquivo com a saída do comando cal*

date *Exibe a data e hora que executou comando*

date >> calendario.txt *Adiciona a saída do comando date no final do arquivo calendario.txt*

cal 2020 *Exibe o calendario do ano 2020*

tail distros.txt | grep Linux *O grep vai fazer uma busca dentro do arquivo distros.txt*

- **Comando de paginação de textos e criação de pastas**

cat teste.txt | more *Exibe o arquivo teste.txt com paginação --Mais--*

cat teste.txt | less *Exibe o arquivo teste.txt com paginação :*

ctrl + z *Sai do arquivo*

& *e* && *Operadores de redirecionamento*

cat maio.txt & cat julho.txt *Exibe os arquivos separados por comando no terminal com pausa*

cat maio.txt && cat julho.txt *Exibe os arquivos consecutivos*

file maio.txt *Exibe informações do arquivo ou diretório* 

file linux_ubuntu

whatis *Exibe o que faz determinado arquivo*

- **Revisão do conteúdo**

  (|) Envia a saída de um comando para entrada de outro comando permitindo a execução de dois comandos.

  (>) Redireciona a saída de um comando para outro comando ou arquivo

  (>>) Redireciona a saída e adiciona a mesma para um comando ou arquivo

  (<) Direciona a entrada de um arquivo para a saída de um comando

  (&) Este operador permite usar dois comando e separa suas saídas no terminal

  (&&) Usado para que dois comandos só sejam executados se o primeiro for executado com sucesso

rm -r * *Remover todos os arquivos de uma pasta*

Apostilas e informações do Linux https://guiafoca.org

- **Exercícios de Revisão**

Exercícios de Revisão
1) Crie uma pasta de nome Exercícios e Acesse a mesma
2) Crie um arquivo vazio de nome lista_nomes.txt
3) Abra este arquivo com o Editor Nano
4) Digite 20 Nomes de Pessoas Conhecidas incluindo o seu, pulando de linha para cada nome inserido.
5) Salve o arquivo
6) Exiba os 10 primeiros Nomes da Lista
7) Exiba os 10 ultimos Nomes da Lista
8) Procure no texto o seu nome
9) Crie um Arquivo chamado setembro.txt com a saida do comando cal.
10) Adicione o conteúdo do arquivo setembro.txt ao arquivo lista_nomes.txt
11) Exiba o arquivo lista_nomes.txt com paginação
12) Exiba o caminho do arquivos setembro.txt
13) Exiba o tipo do arquivo lista_nomes.txt
14) Exiba a explicação do comando ls
15) Renomeie o Arquivo lista_nomes.txt para arquivo.txt
16) Limpe o Terminal
17) Saia do Terminal

- **Certifique seu Conhecimento**

  Hugo deseja criar uma pasta com seu nome e logo em seguida, se houver sucesso na criação da pasta, abrir esta pasta no terminal. Qual sequência de comandos Hugo deve usar?	*mkdir Hugo && cd Hugo*

  José quer exibir o calendário do mês de junho de 2019 na saída do terminal, qual sequência de comandos ele deve digitar?		*cal junho 2019*

  Qual das opções abaixo utilizamos quando queremos redirecionar a saída de um comando para outro comando ou arquivo?		*Nenhuma das alternativas.*

  Qual comando utilizamos para criar um arquivo vazio de nome teste.txt?	*touch teste.txt*

  José quer saber a explicação do comando ls, qual sequência de comandos ele deve usar?	*whatis ls*

  Qual comando para editarmos o arquivo teste.txt no editor nano?	*nano teste.txt*

  João deseja procurar seu nome em um arquivo chamado lista_nomes.txt, qual sequência de comandos ele deve usar?	*grep Joao lista_nomes.txt*

  Qual comando utilizado para exibir o conteúdo de um arquivo no terminal?	*cat*

  Qual comando utilizado para exibir a data atual do sistema?	*date*

  Qual comando utilizado para inverter a saída do conteúdo de um arquivo no terminal?	*tac*

#### Diretórios do Linux e Comandos de Sistema

- **Apresentação dos comandos de diretórios do Linux**

/bin/ *Binários principais dos usuarios. Executáveis*

/boot/ *Arquivos do sistema de Boot*

/dev/ *Arquivos de dispositivos*

/etc/ *Arquivos de configuração do sistema*

/home/ *Diretório dos usuários comuns do sistema*

/lib/ *Bibliotecas essenciais do sistema e os modulos do kernel*

/media/ *Diretório de montagem e dispositivos*

/mnt/ *Diretório de montagem de dispositivos - mesmo que media*

/opt/ *Instalação de programa não oficiais da distribuição ou por conta do usuário*

/sbin/ *Armazena arquivos executáveis que representam comandos administrativos. Exemplo: shutdown*

/srv/ *Diretórios para dados de serviços fornecidos pelo sistema*

/tmp/ *Diretório para arquivos temporários*

/usr/ *Segunda hierarquia do sistema, onde ficam os usuarios comuns do sistema e programas*

/var/ *Diretório com aquivos variaveis gerados pelos programas do sistema. Exemplo: email, cache, impressoras*

/root/ *Diretório do usuario root - O usuário root tem o total poder sobre o sistema.* 

/proc/ *Diretório virtual controlado pelo Kernel*

- **Praticando no terminal os comandos de diretórios e sistema - Parte 1**

cat /proc *Informações de cpu*

cat /proc/cpuinfo | more *Informações de cpu*

cat /proc/meminfo

lspci *Todos os hardwares conectados via pci*

lsusb | more *Informações usb*

arch *Arquitetura do sistema*

uname *Nome do kernel*

uname -r *Versão do kernel*

uname -m *Arquitetura do kernel*

free *Saída de memória fisica e memoria swap*

du -h ~ | more *Relação de arquivos e diretórios e alocação de espaço no hd*

-h *human readble - leitura facilitada com espaços*

- **Praticando no terminal os comandos de diretórios e sistema - Parte 2**

cat /etc/passwd | more *Todos os usuários do sistema*

reboot *Reinicia o sistema*

shutdown -h now *Desliga o sistema*

shutdown --help *Informações do comando shutdown*

​		-r *Reinicia o sistema*

​		-h *Desliga o sistema*

​		-c *Cancela*

lscpu | more *Informações sobre processamento*

lshw | more *Lista de todos os hardwares*

lshw -short *Exibe de forma simplificada os hardwares*

- **Revisão do conteúdo**

echo "texto para o terminal"

echo -e "\n" *quebra de linha. Preciso colocar -e*

- **Certifique seu conhecimento**

  Quais comandos exibem a arquitetura do kernel Linux?		*uname -m, arch*

  Qual comando exibe a versão do kernel Linux?		*uname -r*

  Um técnico deseja exibir todos os dispositivos do tipo USB conectados ao Linux, qual comando ele deve utilizar?			*lsusb*

  Qual a saída do comando cat /proc/cpuinfo?		*Informações de Processamentos.*

  João deseja visualizar o espaço ocupado por cada arquivo e pasta dentro de /home no hd. Qual sequência de comandos ele deve usar?		*du -h /home*

  Qual o comando exibe todas as placas PCI listadas pelo Linux?		*lspci*

  Qual comando exibe o nome do kernel?		*uname*

  Qual o comando exibe informações de memória física e swap?		*free*

  Qual comando exibe todos os hardwares listados pelo Linux?		*lshw*

  Qual a saída do comando cat /proc/meminfo?		*Informações de Memória.*

#### Fundamentos de Rede e Comandos de Rede

- **O que são Redes, Protocolos e Interfaces de rede**

Rede: É um conjunto de equipamentos interligados de maneira a trocarem informações.

Rede Wan: Wide Area Network ou World Area Network é uma rede geograficamente distribuída.

Rede Man: Metropolitan Area Network é uma rede metropolitana que interligam várias redes locais.

Rede Lan: Local Area Network é uma rede local de uma forma geral em um único prédio ou campus.

Protocolos: É a linguagem usada pelos dispositivos de uma rede de modo que eles consigam se entender. Existem vários protocolos.

​		IP - Protocolo de Internet - Endereço Ip - números que identificam seu computador em uma rede.

​		ICMP - (Internet Control Message Protocol) tem por objetivo prover mensagens de controle na comunicação entre nós.

​		DNS - Domain Name Server - esse protocolo de aplicação tem por função identificar endereços Ips e manter uma tabela com os endereços dos caminhso de algumas redes.

Interface de Rede: é um software e/ou hardware que faz a comunicação em uma rede de computadores. (No Ubuntu está na pasta /dev). Ex: eth0 - Placa de rede Ethernet - cabeada

A interface loopback é um tipo especial de interface que permite fazer conexões com você mesmo, com ela, você pode testar vários programas de rede sem interferis em sua rede. Por padrão, o endereço IP 127.0.0.1 foi escolhido para loopback.

- **Comando ifconfig**

sudo apt install net-tools

ifconfig *Exibe Interfaces de rede*

ipv4 inet 192.168.110.128

netmask *Mascara de rede - separa rede publica da rede privada*

broadcast *Endereço público da minha máquina*

ipv6 inet6 *Sequência hexadecimal*

ether *Enderço físico, da placa de rede. Conhecido como endereço maq. Ele é único da placa de rede*

- **Comandos hostname e ping**

hostname *Exibe informações sobre o host, nosso computador na rede*

hostname -I *Endereço IP*

hostname -i *Com i minuscula, info de loopback*

who *Exibe como estamos logados na rede*

whoami *Usuario logado na rede*

ping *Faz parte do protocolo icmp, faz controle de host, verifica se está ativo ou inativo*

ping www.google.com.br -w  4 *Envia 4 pacotes de ping*

dig www.google.com.br *Informações sobre os caminhos de rede de um ip ou host*

- **Comandos traceroute e finger**

sudo apt install traceroute

traceroute to  www.google.com *Exibe os nós até chegar no google.com*

dig www.google.com +short *Exibe apenas o endereço dns, ip*

whois www.google.com *informações sobre determinado host, dono do dominio, país, servidor dns*

finger *Informações de usuario logado no nosso host*

- **Revisão do conteúdo e exercícios - Parte 1**

- **Revisão do conteúdo e exercícios - Parte 2**

- **Exercícios Práticos**

Exercícios Práticos
1) Crie um arquivo de aularedes.txt
2) Exiba o número de IP da rede no terminal
3) Adicione a saída do comando anterior ao arquivo aula redes.txt
4) Exiba o número de IP Loopback no terminal
5) Adicione a saída do comando anterior ao arquivo aula redes.txt
6) Exiba Informações DNS sobre o host www.pudim.com.br
7) Adicione a saída do comando anterior ao arquivo aula redes.txt
8) Exiba Informações do Usuário logado na rede
9) Adicione a saída do comando anterior ao arquivo aula redes.txt
10) Execute um teste no host www.pudim.com.br com 6 pacotes
11) Adicione a saída do comando anterior ao arquivo aula redes.txt
12) Trace a Rota do seu computador até o host www.pudim.com.br
13) Adicione a saída do comando anterior ao arquivo aula redes.txt
14) Exiba Informações sobre Interfaces de Rede e Endereços IP no terminal
15) Adicione a saída do comando anterior ao arquivo aula redes.txt
16) Limpe o terminal
17) Imprima o arquivo aularedes.txt com paginação no terminal

- **Certifique seu conhecimento**

  Qual comando testa se um host está ativo ou inativo enviando pacotes de requisição do protocolo ICMP?	*ping*

  Qual comando testa se um host está ativo ou inativo enviando pacotes de requisição do protocolo ICMP?		*Interface de rede é um software e/ou hardware que faz a comunicação em uma rede de computadores.*

  Qual comando exibe o nome do computador na rede (nome do host)?		*hostname*

  O que é Protocolo em Redes de Computadores?		*A “linguagem” usada pelos dispositivos de uma rede de modo que eles consigam se entender.*

  Qual das alternativas abaixo representa 3 protocolos de Rede?	*IP, ICMP e DNS*

  Qual sequência de comandos exibe a rota do seu computador (sua rede) até o host www.google.com?	*traceroute www.google.com*

  Qual das alternativas abaixo representa as 3 estruturas de rede conhecidas?	*WAN, MAN e LAN*

  Qual comando exibe Interfaces de Rede e Endereços IP no terminal?	*ifconfig*

  Qual sequência de comandos exibe o número de IP do site www.pudim.com.br?	*dig www.pudim.com.br +short*

  O que é Rede?	*É um conjunto de equipamentos interligados de maneira a trocarem informações e compartilharem recursos.*

#### Fuçando no Linux com comandos diversos

- **Comandos history, alias e outras interações com arquivos .txt**

history *Exibe histórico de comandos. Coloque a flag -c para apagar*

alias hh='history' *Cria um atalho para comandos. Nesse caso, só digita hh para exibir o histórico*

nl arquivo.txt *Número de linhas do arquivo*

wc -l arquivo.txt *Exibe todas as linhas, inclusive em branco. A flag -w exibe o total de palavras. -c para total de bytes. -m total de caracteres. --help para todas as informações*

ls -a *Exibe arquivos ocultos*

ls -F *Coloca uma barra em cada diretório*

cmp arquivo1.txt arquivo2.txt *Faz comparação entre arquivos*

diff *Exibe outra diferença de arquivos*

sort -n arquivo.txt *Organiza a saída do arquivo em ordem numérica*

- **Comandos last reboot, route, time, cowsay e cmatrix**

last reboot *Todas as Informações de reinicialização do sistema*

route -n *Tabelas de roteamento ip do nosso kernel*

time *Mostra o tempo de um processo*

uptime *Tempo que o sistema está rodando*

Comandos que precisam de instalação

​	cowsay *Mostra um desenho. Com a flag -d ; -g*

​	cowsay -f (vader)(tux)(dragon) *Exibe vários animais*

​	xcowsay

​	cmatrix

- **Comandos para desligar o sistema operacional**

init 0 *Desliga a máquina*

telinit 0 *Desliga a máquina*

halt *Pede uma autenticação para desligar a máquina*

seq 1 10 > arquivo.txt *Imprime uma sequência de números e coloca dentro de um arquivo.*

whereis *Exibe o caminho do programa e seu manual*

which *Exibe o caminho de um programa*

cmp *Compara dois aquivos*

- **Revisão do conteúdo com JSLinux**

Funciona parte de console e gráfica no browser. https://bellard.org/jslinux

- **Certifique seu conhecimento**

  José deseja exibir a comparação entre dois arquivos de texto, um arquivo de nome vazio.txt  e outro arquivo.txt qual sequência ele deve digitar no terminal?	cmp vazio.txt arquivo.txt

  José deseja exibir a contagem do número de palavras de um arquivo de nome vazio.txt qual sequência ele deve digitar no terminal?	wc -w vazio.txt

  Qual comando organiza um arquivo de texto em ordem alfabética ou numérica?	sort

  Qual dos comandos abaixo coloca números de linhas em um arquivo de texto?	nl

  José deseja exibir a contagem do número de linhas de um arquivo de nome vazio.txt qual sequência ele deve digitar no terminal?	wc -l vazio.txt

  Quais opções de comandos temos para desligar a máquina rapidamente?	shutdown -h now, init 0, telinit 0, e halt

  José deseja exibir a contagem do número de bytes de um arquivo de nome vazio.txt qual sequência ele deve digitar no terminal?	wc -c vazio.txt

  Qual sequência de comandos exibe o tempo de processamento do comando traceroute no host www.pudim.com.br?	time traceroute www.pudim.com.br

  Qual das opções do comando history apaga o histórico de comandos?	history -c

  João deseja instalar o programa cowsay para sua filha, qual sequência de comandos ele deve digitar no terminal?	sudo apt install cowsay

#### Controle de usuários, grupos e permissões

- **Como adicionar usuários**

adduser nomedousuario

- **Como trocar de usuário e alterar sua senha**

su nomedousuario *Trocar de usuario*

passwd nomedousuario *Alterar senha*

Método Zenit Polar

- **Como exibir informações de login e remover um usuário**

laslog *Exibir informações de Login dos Usuarios*

last *Exibir uma listagem do usuario de entrada e saída do sistema*

logname *Exibe o nome do usuario atual logado no sistema*

id *Exibe todos os identificadores do usuário*

*Exibir todos os usuarios* cat /etc/passwd

userdel -r nomedousuario *Remove o usuario, com a flag -r vai remover a pasta pessoal*

- **Como criar um grupo e gerenciar os usuários**

cat /etc/group *Exibe todos os grupos do sistema*

groups *Exibe todos os grupos de um usuário*

addgroup *Criar um grupo*

adduser usuario grupo *Adiciona um usuario a um grupo*

gpasswd -a usuario grupo *Adiciona um usuario a um grupo*

gpasswd -d *Remove um usuario de um grupo*

groupdel grupo *Remover um grupo*

- **Como gerenciar permissões em diretórios e o que é o modo octal**

Permissões

​		r - read

​		w - write

​		x - eXecution

ls -lh *Verifica permissões em um diretório*

**d** *é pra diretório e* **-** *é pra arquivos*

drwx**r-x**r-x 		dono**grupo**outros

chmod *Mudar a permissão de um arquivo ou diretório*

| User (owner) |    Group    |    Other    |
| :----------: | :---------: | :---------: |
| r \| w \| x  | r \| w \| x | r \| w \| x |
| 4 \| 2 \| 1  | 4 \| 2 \| 1 | 4 \| 2 \| 1 |

Composto por números sob a base 8, ou seja, de 0 a 7

O primeiro dígito representa o dono do ficheiro/diretório (u)

O segundo dígito representa o grupo (g)

O terceiro dígito representa os outros (o)

As permissões são específicas para cada grupo.

​		Exemplo: 0 quando não tem nenhuma atribuição 1 0 0

chmod 100 arquivo.txt

ls -lh *Exibe informações*

- **Comando chmod**

4+2+1 = 7

Para usuario: chmod 700 arquivo.txt

todas as condições 7

somente leitura e execução 5

Mais alto nível de privilégio 777

- **Revisão e prática do conteúdo**

- **Certifique seu conhecimento**

  Qual sequência de comandos abaixo adiciona um usuário de nome teste a um grupo de nome grpteste?	 adduser teste grpteste

  Qual comando deleta usuários e suas respectivas pastas pessoais?	userdel -r

  Andrea deseja exibir todos os usuários de um sistema, qual sequência de comandos ela deve utilizar?	cat /etc/passwd

  Qual comando exibe o nome do usuário logado no sistema?	logname

  Qual comando adiciona um grupo?	addgroup

  Qual sequência de comandos abaixo remove um usuário de nome teste do grupo de nome grpteste?	gpasswd –d teste grpteste

  Qual comando exibe os identificadores de um usuário?	id

  Qual comando é usado para alterar a senha de um usuário?	passwd

  Augusto tem um dois usuários em seu sistema: um de nome augusto e outro guto. Sendo que no terminal de Augusto está logado no usuário augusto, que sequência de comandos ele deve utilizar para trocara para o usuário guto?	su guto

  Qual comando é usado para adicionar usuários?	adduser

#### Compactação, descompactação e arquivamento

- **Comandos gzip, zip e bzip2**

Compactadores são programas que diminuem o tamanho de um arquivo ou diretório

gzip *Compactador muito usado, possui uma taxa excelente de compactação*

gzip arquivo.txt

Descompactar gunzip arquivo.txt.gz

gzip -9 arquivo.txt *Compactação máxima*

Compactador zip

​		zip arquivo.zip arquivo.txt

​		unzip arquivo.zip

Compactador bzip2

​		bzip2 arquivo.txt

​		bzip2 -d arquivo.bz2

- **Comandos rar e tar**

Compactador rar

​		rar a arquivo.rar arquivo.txt

​		rar x arquivo.rar

Arquivador: junta vários arquivos em um só.

Arquivador tar

​		tar -cf aularedes.txt.tar aularedes.txt		*Vai criar um arquivo tar.gz*

​		tar -xvf aularedes.txt.tar.gz

​		tar -xvf aularedes.txt.tar.gz -C ~/Documentos *Vai extrair dentro do diretório*

​		gunzip arquivos.tar.gz 	*Vai retirar a compactação*

- **Revisão e prática do conteudo**

- **Certifique seu Conhecimento**

  Qual opção do arquivador tar descompacta um arquivo compactado e arquivado com tar?	*-xvf*

  Qual comando abaixo compacta arquivos e adiciona a extensão zip?	*zip*

  Qual comando abaixo compacta arquivos e adiciona a extensão bz2?	*bzip2*

  Qual a extensão gerada pelo comando de compactação de arquivos bzip2?	*bz2*

  Qual opção do compactador bzip2 descompacta um arquivo bz2?	*-d*

  Qual comando abaixo compacta arquivos e adiciona a extensão gz?	*gzip*

  Qual comando abaixo representa um arquivador?	*tar*

  Qual comando abaixo não compacta arquivos?	*bz2*

  Qual comando abaixo compacta arquivos e adiciona a extensão rar?	*rar*

  Qual opção do compactador rar descompacta um arquivo rar?	*-x*

#### Gerenciamento de pacotes

- **Instalação, atualização e remoção de pacotes**

Existem pacotes com a extensão .deb, .rpm e outros.

gerenciadores de pacotes são sistemas que possuem resolução automática de dependencias entre pacotes. Ex: dpgk, apt e yum

apt

​		sudo apt install pacote *Instala pacote*

​		sudo apt upgrade pacote *Atualiza pacote*

​		sudo apt remove pactote *Remove um pacote*

- **Atualização de sistema e o comando dpkg**

sudo apt update && apt upgrade

sudo su *Usuario root*

Sites: https://pkgs.org e https://rpm.pbone.net

Gerenciador dpkg

​		sudo dpkg -i pacote.deb

​		copia arquivo Binary Package do site

​		sudo dpkg -I pacote.deb *Descrição do pacote*

​		sudo dpkg -r nomedopacote *O nome do pacote é dado na descrição do pacote. Em Package*

- **Introdução ao Fedora**

https://gtfedora.org/pt_BR

- **Comandos rpm e yum**

Gerenciador rpm

​		rpm -ivh pacote.rpm

​		rpm -ivh --nodeps pacote.rpm

​		rpm -U pacote.rpm *Atualização do pacote*

​		rpm -e pacote.rpm *Remoção do pacote*

Gerenciador yum

​		yum install pacote		*Instalação do pacote*

​		yum update pacote 	*Atualização do pacote*

​		yum remove pacote	*Remoção do pacote*

- **Revisão e prática do conteúdo**

- **Certifique seu Conhecimento**

  O que é um pacote?	*Pacotes são programas colocados dentro de um arquivo identificados por sua extensão.*

  Qual distribuição utilizamos neste curso para trabalhar com pacotes rpm?	*Fedora*.

  Qual gerenciador instala, e remove pacotes .deb?	*dpkg*

  Qual opção do comando rpm instala um pacote rpm?	*-ivh*

  Qual sequencia de comandos remove um programa instalado pelo apt?	*sudo apt remove*

  Qual opção do comando yum remove um pacote rpm?	*remove*

  Qual gerenciador que além de instalar pacotes também atualiza o sistema?	*apt*

  Qual distribuição utilizamos neste curso para trabalhar com pacotes deb?	*Ubuntu*.

  Quais gerenciadores instalam e removem pacotes rpm?	*rpm e yum*

  José deseja instalar o pacote wireshark no ubuntu utilizando o apt. Qual sequência de comandos José deve usar?	*sudo apt install wireshark*

<br><br><br>

------

## Shell script - Manipulando Arquivos

​	:hourglass: 2 horas

<br>

#### Introdução ao curso e alguns comandos com Shell Script

- **Apresentação Inicial**

Daviny - github.com/davinyvidal

- **Objetivos do curso e o que é Shell Script**

O que é Shell Script? é uma interface de usuário para acessar os serviços de um SO. 

Script é uma linguagem de programação que executa no sistema em tempo de execução, muito utilizado para automação. Bash, SH

- **cd - Mudar Diretório**

cd = change directory

cd / Abre o diretório raiz do sistema

cd ~ Abre o diretório do usuário corrente.

cd .. Voltar diretório

- **ls - Listando arquivos**

ls -l *Lista o conteúdo em coluna detalhada*

ls -a *Lista o conteúdo até arquivos ocultos*

ls -s *Lista o conteúdo com tamanho alocado de cada arquivo, em bloco*

man ls *ou* info ls *apresenta todas as opções e informações do comando ls*

- **touch - Criar e atualizar o conteúdo**

Touch - Usado para criar arquivos vazios ou alterar data e hora.

​	*Criar Múltiplos Arquivos* touch file_name1.txt file_name2.txt

​	*Alterar Hora de Acesso* touch -a file_name.txt

​	*Alterar Hora de Acesso sem Criar um novo arquivo* touch -c file_name.txt

​	*Definir Hora Específica de Acesso e Modificação* touch -t 2020012081047.30 file.txt

​	CCYYMMDDhhmm.ss

​	*Para alterar hora da modificação* touch -m file.txt

- **cat - Visualizar conteúdo do arquivo**

concatenate (concatenar)

*Criar, Unir e Exibir arquivos*

*Colocar o resultado em um outro arquivo* cat arq1.txt > arq_final.txt

Para para a rolagem da tela e permitir a navegação use o pipe |

cat novo_arquivo.txt

#### Comandos com Shell Script - Parte 2

- **mv - Mover Arquivos**

mv *Move arquivos e diretório e renomeia arquivos e diretórios.*

-i *Confirme antes de substituir*

-n *Sem substituição*

-b *Substituindo pelo backup*

-u *Substitua se o arquivo de destino for antigo ou não existir.*

- **cp - Copiar Arquivos**

cp *Permite copiar arquivos ou diretórios para outro local.*

-i *Confirmação de existência*

-v *Exibe saída*

-l *criar hard links em vez de copiar os arquivos*

-s *criar links simbólicos em vez de copiar arquivos*

-u *copiar apenas quando o arquivo de origem for mais novo do que o arquivo de destino ou quando o arquivo de destino não existir.*

- **mkdir - Criando diretórios**

- **find - Produrar por arquivos e rm - Removendo arquivos**

rm *Remover arquivos*

-f *Não confirma*

find Procurar arquivos

find ./ -type f -name "o" Procura arquivos no diretório atual com o nome de "o"

find ./ -type f -name "A*" Procura arquivos no diretório atual iniciando com "A"

man find *Exibe informações do comando*

- **diff - Comparar diferença entre arquivos**

diff *Faz comparações entre arquivos*

- **rmdir - Remover diretório**

rmdir *Remover diretório vazio*

rm -rf *Para diretório não vazio*

- **env - Trabalhando com variáveis**

env *Variáveis de ambiente*

PS1 *Prompt da linha de comandos*

HOME *Diretório "/home" de um usuário*

PATH *Lista de diretórios vasculhados quando um comando é executado*

*Exemplo*

​		limao=limao

​		echo $limao

​		export limao

​		env

- **Considerações finais**

https://github.com/davinyvidal/dio-shell-script

<br>

<br>

<br>

------

## Monitoramento de clusters Hadoop de alto nível com HDFS e Yarn

*Aprenda mais sobre  a gerenciar dados armazenados em disco no cluster com o HDFS e como a gerenciar os recursos de um cluster utlizando o Yarn para alocar recursos computacionais da melhor maneira.*

:calendar: 19/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

[Slides](/.pdfs/Aula-19-01-2021.pdf)

<br>

#### :pencil:*Anotações pré live* 

- **Ecossistema Hadoop**

Para Inserir os dados temos **Flume** (Não estruturado) e o **Sqoop** (Dados Relacionais)

Sistema de arquivos distribuídos - **HDFS**

Gerenciamento de recursos - **YARN**

**Hadoop** (Batch) é uma aplicação para processar grandes volumes de dados em batch. Sistema distribuído. O Hadoop é uma linguagem de baixo nível, precisa de programação em Java.

**Apache Spark** (Real Time) é uma aplicação de processamento de dados em tempo real, ou próximo do tempo real em memória.

**Apache Pig** é uma aplicação de script. Pode criar aplicações .

**Mahout**, é uma biblioteca de Machine Learning para o sistema Hadoop.

**Hive** é uma solução Data Warehouse para Big Data. Dados estruturados, com linguagem semelhante ao SQL.

**Apache Kafka** (Streaming), aplicações de streamings, processamento contínuo de dados.

**Spark Streaming**, é uma parte do Spark que trata streaming.

Algumas Soluções com objetivo de tratamento de dados: Drill, Zookeeper, Ambari, Hbase, Solr, Lucene, Storm.

**Map Reduce**, tem por objetivo dividir tarefas de processamento de dados em vários nós (vários servidores virtualizados ou não ). *<u>Dividir para conquistar</u>*. Vários nós estarão trabalhando simultaneamente.

Fundamento para Map Reduce e Hadoop: *Simplified Data Processing on Large Clusters*.

Google: https://ai.google/research/pubs/pub62

<u>Particularidades</u>

- Escalável
- Tolerante a falhas
- Disponibilidade
- Confiável
- Utiliza conceito chave/valor
- Não cria gargalos na rede, pos dados não trafegam (*processamento no nó*)

<u>Importante</u>

- Processamento em Batch
- Grande volumes de dados
- Processamento distribuído
- Linguagem Imperativa (**JAVA**) - Necessidade de um programa para rodar uma aplicação hadoop*

<u>Observações</u>

- Uma vez no HDFS pode ser acessado por diversos sistemas (Hadoop, Hive, Spark, etc.)
- Mapeamento é executado em paralelo nos nós
- Apenas quando Mapeamento é encerrado, a redução inicia, tambem em paralelo
- Fase intermediária: Suffle
- Existem tarefas que requerem apenas a etapa de Mapeamento.

<u>Hadoop</u>

- Processamento em Batch
- Baseado no conceito de MapReduce
- Desenvolvido em Java
- Open source
- Distribuído: *Opera em clusters*
- Hardware comodity: *Em qualquer tipo de hardware*
- Capaz de distribuir o processamento em dezenas ou milhares de nós em um cluster
- Suporte a dados estruturados ou não estruturados
- Terabytes até Petabytes de dados
- Conceito Master/Slave
  - Master: mantém metadados, logs, adiciona, encontra, exclui e copia arquivos, distribui as tarefas de mapeamento e redução entre os nós, agendamento, balanceamento, etc.
    - NameNode: gestão do HDFS em um nó. pode ser replicado (Hadoop 2)
      - Datanodes: modo ativo e stanby
      - Heartbeat: enviado do DataNode ao NameNode, como sinal de *saúde*
    - JobTracker: distribui as tarefas de mapeamento e redução entre os nós.
    - TaskTracker: recebe as tarefas de mapeamento e redução do JobTracker: agendamentos, balanceamento de carga, gestão de falhas, etc.
  - Slave: Mantém dados, replica blocos.

<u>Yarn</u>

- Alocação de Recursos de forma global e unificada no cluster
- Agendamentos
- Priorização
- Tolerância a Falhas
- Componentes
  - ResourceManager: um por cluster
    - AplicationManager; gerencia atividades, otimização, distribuição de recursos, etc.
    - Scheduler
  - NodeManager: um por nó
    - Responsável pela execução dos Jobs
  - Aplication Master
    - Distribui tarefas aos containers
  - Container: mantem as tarefas

<br>

*Links Úteis*

- https://datascientist.com.br

- http://pig.apache.org/
- https://hadoop.apache.org/
- https://www.youtube.com/watch?v=iANBytZ26MI
- https://www.youtube.com/watch?v=1vbXmCrkT3Y&ab_channel=edureka%21

- https://www.ipsense.com.br/blog/tudo-o-que-voce-precisa-saber-sobre-o-ecossistema-hadoop/

- https://cloud.google.com/solutions/migration/hadoop/hadoop-migration-security-guide?hl=pt-br

- https://www.sas.com/pt_br/insights/big-data/hadoop.html

- https://www.youtube.com/watch?v=1SNoNTaWFIo&ab_channel=CursodeBigData-RicardoPaiva

- https://www.youtube.com/watch?v=CjRkEywm1go&ab_channel=CursodeBigData-RicardoPaiva

- https://www.youtube.com/watch?v=GQAT4OiZE2U

<br>

#### Live com Rodrigo Garcia (*Everis*) :signal_strength:

*Anotações*

**Parte 1: Big Data**

> <u>Big Data</u> é um processo de análise e interpretação de um grande volume de dados armazenados remotamente. O Big Data pode integrar qualquer dado coletado sobre um assunto ou uma empresa, como os registros de compra e venda e mesmo os canais de interação não digital (telemarketing e call center). Onde há um registro feito, a tecnologia alcança.

<br>

*Escalabilidade Horizontal*

Processamento **tradicional**: escalabilidade vertical

Processamento **distribuído**: escalabilidade horizontal

**O que é um cluster?** É um grupo de computadores que trabalham juntos. Provê armazenamento, processamento e gerenciamento de recursos.

**O que é um nó?** Computador individual no cluster. O nó master (driver) gerencia a distribuição de trabalho para os nós workers.

**O que é um daemon?** É um programa (serviço) rodando em um nó. Cada um tem sua função no cluster.

<br>

**Parte 2: HDFS**

**O que é o Hadoop?**

- Projeto de software open source escrito em Java;
- Escalável, confiável, processamento distribuído;
- S.O de Big Data;
- Pode utilizar hardware comum (commodity cluster computing);
- Framework para computadção distribuída, com filesystem distribuído (HDFS);
- Infraestrutura confiável capaz de lidar com falhas (hardware, software, rede).

**Distros**

- <u>Open Source</u>
  - Apache Hadoop
- <u>Commercial Open Source</u>
  - Cloudera (+Hortonworks)
  - MapR
  - AWS ElasticMapReduce
  - Microsoft HDInsight

***Core Hadoop***

- Processing
  - Spark
  - MapReduce
- Storage
  - HDFS
- Resource Management
  - YARN

<br>

**HDFS** - *Hadoop Distributed File System*

*HDFS -> Native OS Filesystem -> Disk Storage*

- Baseado no Google FS;
- Escalável e tolerante a falhas;
- Arquivos Texto, sequence file, Parquet, AVRO, ORC...
- Tamanho mínimo de um bloco **(default: 128 MB)**;
- Fator de replicação **(default: 3)**.

*Componentes do HDFS*

- NameNode: *Gerencia o namespace(responsável por metadados); Se o Namenode para o cluster, fica inacessível;*

- DataNode: *Armazena os blocos de arquivos;*

- Secondary NameNode: *Oferece tarefas de ponto de verificação e manutenção do Namenode. Não é um bkp*

*Como funciona?*

Daddos separados em blocos; Replicado em 3; O Namenode armazena os metadados.

*Exemplo*

![](/.img/exemplo1hdfs.png)

![](/.img/exemplo2hdfs.png)

<br>

*PUT /GET*

- Copiar arquivo HDFS para local

  $ hdfs dfs -get /tmp/file_teste.txt

- Ingestão manual

  $ hdfs dfs -put file_teste.txt /user/everis-bigdata/

*Live Demo*

$ sudo -u hdfs hdfs dfs -chmod -R 777 /tmp
$ hdfs dfs -ls -h /
$ hdfs dfs -cat /tmp/file_teste.txt |head -10
$ hdfs dfs -rm /tmp/file_teste.txt
$ hdfs dfs -mkdir /tmp/delete
$ hdfs dfs –cp /tmp/file_teste.txt /tmp/delete/
$ hdfs dfs –touchz /tmp/delete/empty_file
$ hdfs dfs -rm -R /tmp/delete
$ hdfs dfs -du -h /user
$ hdfs fsck /tmp/ -files -blocks

<br>

*Start da Máquina Virtual*

​	usuario: everis

​	password: everis2021

ifconfig; endereço começando com 192.168.

*Caso não instalado: sudo yum install net-tools -y*

Utilizando o MobaXterm. Este Ip *(192.168.15.27)* foi encontrado utilizando o ifconfig

```bash
ssh 192.168.15.27 -l everis
```

Start NameNode

```bash
$ sudo service hadoop-hdfs-namenode start
```

```bash
$ sudo service hadoop-hdfs-secondarynamenode start
```

Verificar script_apoio

tmp

```bash
ll script_apoio/
```

```bash
sh script_apoio/start_all_service.sh
```

```bash
$ sudo service hadoop-hdfs-namenode start
$ sudo service hadoop-hdfs-secondarynamenode start
$ sudo service hadoop-hdfs-datanode start
$ sudo service hadoop-mapreduce-historyserver start
$ sudo service hadoop-yarn-resourcemanager start
$ sudo service hadoop-yarn-nodemanager start
```

```bash
$ hdfs dfs -get /tmp/file_teste.txt
```

```bash
$ hdfs dfs -put file_teste.txt /user/everis-bigdata/
```

Colocar a permissão antes

```bash
$ sudo -u hdfs hdfs dfs -chmod -R 777 /tmp
$ hdfs dfs -ls -h /
$ hdfs dfs -cat /tmp/file_teste.txt |head -10
$ hdfs dfs -rm /tmp/file_teste.txt
$ hdfs dfs -mkdir /tmp/delete
$ hdfs dfs –cp /tmp/file_teste.txt /tmp/delete/
$ hdfs dfs –touchz /tmp/delete/empty_file
$ hdfs dfs -rm -R /tmp/delete
$ hdfs dfs -du -h /user
$ hdfs fsck /tmp/ -files -blocks
```

Informações do arquivo

```bash
ll -h
```

*São dois sistemas de arquivos diferentes. hdfs e local*

No hdfs demora mais um pouco para ler por fazer todo o caminho, descrito no exemplo anterior.

Conectando o namenode

```bash
sudo -u hdfs hdfs fsck /tmp/ -files -blocks
```

Ele mostra os blocos. No exemplo, apnas 1 bloco pois é menor que 128MB. E só tem uma réplica. Under replicated.

/tmp/file_teste.text 4784 bytes

Mostra as informações do hdfs fsck

```bash
hdfs fsck
```

<br>

**Parte 3: YARN**

*Yet Another Resource Negotiator*

- Gerenciamento de recursos;
- Gerenciamento e monitoramento de Jobs;
- Recursos dos nós são alocados somente quando requisitado (via container).

*Componentes*

- **Application**: um job submetido ao Hadoop;
- **Application Master**: gerencia a execução e o escalonamento das tarefas (1 por aplicação);
- **Container**: unidade de alocação de recursos (ex. c1 = 1 GB RAM, 2 CPU);
- **Resource Manager**: gerenciador global de recursos;
- **Node Manager**: gerencia o ciclo de vida e monitora os recursos do Container.

*Execução de aplicação*

![](/.img/exemplo1Yarn.png)



Log

```bash
sudo sed -i 's|hdfs://|hdfs://bigdata-srv:8020/|g'
/etc/hadoop/conf/yarn-site.xml
```

Jobs: O Hadoop Vai rodar alguns exemplos de MapReduce

```bash
sudo –u hdfs yarn jar /usr/lib/hadoop-mapreduce/hadoopmapreduce-examples.jar wordcount /tmp/file_teste.txt
/tmp/wc_output
```

*Pesquisar sobre exemplos na biblioteca exemplo de MapReduce.  https://stage.philipithomas.com/simple-mapreduce/*

<u>**Observação**</u>: Com o comando acima irá resultar uma url http://**bigdata-srv**:8088/...

Substituir **bigdata-srv** pelo ip da máquina. Neste exemplo, 192.168.15.27.

<u>192.168.15.27:8088/cluster</u> *Vai acessar o Hadoop com All Applications*

<br>

**<u>Restart</u>** 

- Parar tudo

  - Script de Apoio

    ```bash
    sh script_apoio/stop_all_service.sh
    ```

- Start

  - Script de Apoio

    ```bash
    sh script_apoio/start_all_service.sh
    ```

    

*Lendo o input e output da aplicação*

```bash
hdfs dfs -cat /tmp/file_teste.txt
```

```bash
hdfs dfs -ls /tmp/wc_output
```

Ler arquivo Log 

```bash
$ sudo -u hdfs yarn logs -applicationId
application_1611089476809_0001 |more
```

Converter para arquivo

```bash
sudo -u hdfs yarn logs -applicationId
application_1611089476809_0001 > wordcount.log
```

<br>

**<u>RESUMÃO</u>**

- **HDFS** é a camada de armazenamento do Hadoop;
  - Divide os dados em blocos e os distribui pelo cluster;
  - Os workers rodam o daemon DataNode e o master o daemon NameNode;

- **MAPREDUCE** foi o primeiro framework de computação distribuída utilizado com o HDFS;
  - Levou o processamento aos servidores onde o dado está armazenado.
- **YARN** gerencia os recursos no cluster
  - Trabalha com o HDFS para executar as tarefas quando o dado é armazenado;
  - OS workers rodam o daemon "NodeManager" e o master o daemon "ResourceManager";
  - É possível monitorar os jobs através da porta 8088.



<br>

Perguntas

- Problemas no ip. *Copiar ip desse arquivo*

  ```bash
  sudo vim /etc/hosts
  ```

  Comentar # o ip com o bigdata-srv. i ; esc :wq

<br>

<br>

<br>

------

## Orquestrando ambientes de big data distribuídos com Zookeeper, Yarn e Sqoop

*Aprenda mais sobre Zookeeper para gerenciar sistemas distribuídos,Sqoop para transferir dados entre bancos de dados relacionais e o Hadoop e gerencie os recursos de um cluster com Yarn.*

:calendar: 20/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/Aula-20-01-2021.pdf)

*Notas da live*

[Link da MV atualizado](https://hermes.digitalinnovation.one/files/acceleration/Everis_BigData-v3.ova)

<br>

**Parte 1: Zookeeper**

> Zookeeper e Sqoop em um ambiente clusterizado Hadoop

O que é o **Zookeeper**?

- Serviço de coordenação distribuído;
- Gerenciamento de um grande conjunto de hosts (nós);
- Arquitetura simples e API;
- Assim como o Hadoop, vem simplificar o processo do desenvolvedor;
- Fornece as rotas necessárias para as peças do cluster.
- Identifica os nós por nomes (DNS like);
- Gerencia e coordena as configurações;
- Funciona com esquema de eleição de líder (usar-se sempre pelo menos três Zookeeper);
- Pode indisponibilizar o dado enquanto está sendo modificado;
- Ajuda na recuperação automática de falhas (HBase, por exemplo).



**Arquitetura Zookeeper**

- **Leader:** responsável pelo processamento de requests de escrita. Eleito internamente. 
- **Followers:** recebem as requests de leitura

<br>

**Parte 2: Conceito Sqoop**

**Sqoop**

- Originalmente desenvolvido pela Cloudera;
- Movimenta dados entre **banco de dados relacional** e **HDFS**;
- Pode-se **importar** todas as tabelas, apenas uma tabela ou parte de uma tabela para o HDFS;
- Também permite **exportar** de dados do HDFS para um banco de dados;
- Permite **automatização** do processo de ingestão.

*Como funciona? (Ele é um pouco mais lento)*

- Realiza a leitura linha por linha da tabela para escrever o arquivo no HDFS;
- O resultado do import é um conjunto de arquivos contendo a cópia dos dados da tabela importada;
- Under the hood, gera classes Java, permitindo que o usuário possa interagir com o dado importado;
- Pode importar dados e metadados de bancos de dados SQL direto para o Hive;

- Utiliza MapReduce*(Não é tão performático)* para realizar import/ export dos dados, provendo um processamento paralelo e tolerante a falha.
- Permite especificar o intervalo e quais colunas serão importadas;
- Possibilita a especificação de delimitadores e formatos de arquivos;

- Realiza conexões com bancos de dados em **paralelo**, executando comandos de Select(import) e Insert/Update(export);
- Aceita conexão com diversos plug-ins: MySQL, PostgreSQL, Oracle, Teradata, Netezza, Vertica, DB2 e
SQL Server;
- O formato padrão do arquivo importado no HDFS é CSV.

*Exemplo*

![](/.img/sqoop1.png)

![](/.img/sqoop2.png)

```shell
sqoop import \
--connect jdbc:mysql://mysql.example.com/sqoop \
--username sqoop \
--password sqoop \
--table cities
--warehouse-dir /etl/input/ # Pemite especificar um diretório no HDFS como destino
--where "country = 'Brazil'" # Pa importar apenas um subconjunto de registros de uma tabela
-P ou --password-file my-sqoop-password
--as-sequencefile ou --as-avrodatafile # Para escrever o arquivo no HDFS em formato binário (Sequence ou Avro)
--compress # Comprime os blocos antes de gravar no HDFS em formato gzip por padrão
--compression-codec # Utilizar outros codecs de compressão, exemplo: org.apache.hadoop.io.compress.BZip2codec
--direct # Realiza import direto por meio das funcionalidades nativas do BD para melhorar a performance, exemplo: mysqldump ou pg_dump
--map-column-java c1=String # Especificar o tipo do campo
--num-mappers 10 # Especificar a quantidade de paralelismo para controlar o workload
--null-string '\\N'\
--null-non-string '\\N'
--incremental append ou lastmodified # Funcionalidade para incrementar os dados
			--check-column id ou last_update_date # Identifica a coluna que será verificada para incrementar novos dados
			--last-value 1 ou "2013-05-22 01:01:01" # Para especificar o último valor importado no Hadoop
```

<br>

[Documentação do Sqoop](https://sqoop.apache.org/docs/1.4.6/index.html)

<br>

- Import da tabela accounts

```shell
sqoop import --table accounts \
--connect jdbc:mysql://dbhost/loudacre \
--username dbuser --password pw
```

- Import da tabela accounts utilizando um delimitador

```shell
sqoop import --table accounts \
--connect jdbc:mysql://dbhost/loudacre \
--username dbuser --password pw \
--fields-terminated-by "\t"
```

- Import da tabela accounts limitando os resultados

```shell
sqoop import --table accounts \
--connect jdbc:mysql://dbhost/loudacre \
--username dbuser --password pw \
--where "state='CA'"
```

- Import incremental baseado em um timestamp. Dve certificar-se de que esta coluna é atualizada quando os registros são atualizados ou adicionados.

```shell
sqoop import --table invoices \
--connect jdbc:mysql://dbhost/loudacre \
--username dbuser --password pw \
--incremental lasmodified \
--check-column mod_dt \
--last-value '2015-09-30 16:00:00'
```

- Import baseado no último valor de uma coluna específica

```shell
sqoop import --table invoices \
--connect jdbc:mysql://dbhost/loudacre \
--username dbuser --password pw \
--incremental append \
--check-column id \
--last-value 9878306
```

<br>
**Parte 3: Realizar uma ingestão com Sqoop**

- Instalando o Sqoop

[Comandos](/aula20-01-2021/Comandos.txt)

```shell
sudo yum install --assumeyes sqoop # Instalando
cd /tmp # Abre a pasta tmp
wget http://www.java2s.com/Code/JarDownload/java-json/java-json.jar.zip # Pega o arquivo zipado
unzip /tmp/java-json.jar.zip # Descompacta o arquivo
sudo mv /tmp/java-json.jar /usr/lib/sqoop/lib/ # Move o json para a lib do sqoop
sudo chown root: /usr/lib/sqoop/lib/java-json.jar # Altera o dono para o root
sqoop-version
```

Saída do sqoop-version

```bash
21/01/20 17:00:47 INFO sqoop.Sqoop: Running
Sqoop version: 1.4.6-cdh5.16.2
Sqoop 1.4.6-cdh5.16.2
git commit id
Compiled by jenkins on Mon Jun 3 03:34:57 PDT 2019
```

Pegar [install_sqoop.sh](/aula20-01-2021/install_sqoop.sh) , para automatizar.

```shell
vim install_sqoop.sh
```

Clique **i** teclado. Pra colar **shift+insert**. **Esc:wq**

```shell
sh install_sqoop.sh
[sudo] password for everis: everis2021
```

**OBS:** A VM precisa ter acesso a internet.

<br>

**HANDS-ON!**

Arquivos necessários:

- [install_sqoop.sh](/aula20-01-2021/install_sqoop.sh)
- [pokemon.sql](/aula20-01-2021/pokemon.sql)
- [sqoop_import.sh](/aula20-01-2021/sqoop_import.sh)

Colocar comando e colar os arquivos acima. Cada arquivo

```shell
vim install_sqoop.sh
vim pokemon.sql
sqoop_import.sh
```

Rodar o sql dentro do mysql

```shell
mysql -u root -h localhost -pEveris@2021 < pokemon.sql
```

Verificando a existência da tabela

```shell
mysql -u root -h localhost -pEveris@2021
```

Rodar as linhas do arquivo [dontpad](/aula20-01-2021/dontpad.txt)

*Primeira linha somente pra não identificar a segunda linha como password*

```shell
sudo service hadoop-hdfs-namenode start
```

Restante das linhas

```shell
sudo service hadoop-hdfs-secondarynamenode start
sudo service hadoop-hdfs-datanode start
sudo service hadoop-yarn-nodemanager start
sudo service hadoop-yarn-resourcemanager start
sudo service hadoop-mapreduce-historyserver start
sudo service zookeeper-server start
```

sh sqoop_import.sh

O Conteudo está abaixo

```shell
echo "Apagando diretório de output"
sudo -u hdfs hdfs dfs -rm -R /user/everis-bigdata/pokemon

echo "Importando a tabela"
sudo -u hdfs sqoop import \

--connect jdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--fields-terminated-by "|" \
--split-by Generation \
--target-dir /user/everis-bigdata/pokemon \
--query 'SELECT * FROM pokemon WHERE $CONDITIONS' \
--where 'Number IS NOT NULL' \
--compress \
--num-mappers 4
```

-- Vai importar as tabelas, número de linhas, url yarn

-- Precisa modificar a url com o ip da máquina

```shell
ip addr show
```

Exemplo da aula: 

192.168.15.27:8088/proxy/application_1611167972762_0025/

192.168.15.27:8088

*O Sqoop gera um jar, e aplicação MapReduce*. Retrieved 800 records.

Listando

```shell
hdfs dfs -ls /user/everis-bigdata/pokemon
```

Ler arquivos

```shell
hdfs dfs -text /user/everis-bigdata/pokemon/part-m-00000.gz
```

<br>

**Exercícios**

Import subsets com Sqoop seguindo as seguintes premissas:
1. Todos os Pokémon lendários;
2. Todos os Pokémon de apenas um tipo;
3. Os top 10 Pokémon mais rápidos;
4. Os top 50 Pokémon com menos HP;
5. Os top 100 Pokémon com maiores atributos;

<br>

*Testando a query*

```shell
mysql -u root -h localhost -pEveris@2021
```

No Mysql. Exercício 1, todos os lendários

```sql
SELECT * FROM trainning.pokemon WHERE Legendary IS true
```

Retorno: 65 rows in set

No **Sqoop** 

```shell
sudo -u hdfs sqoop import \
```

String de conexão

```shell
--connectjdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--direct \
--table pokemon \
--target-dir /user/everis-bigdata/pokemon/1 \
--where "Legendary=1"
```

Retorno: 65 rows in set

Verificando o diretório

```shell
hdfs dfs -ls /user/everis-bigdata/pokemon/1
```

Found 5 items

Ler todos os arquivos

```shell
hdfs dfs -cat /user/everis-bigdata/pokemon/1/*
```

Contando as linhas

```shell
hdfs dfs -ls /user/everis-bigdata/pokemon/1/* |wc -l
```

Retorno 65

<hr>

Para o Exercício 2, vai utilizar da mesma forma

```shell
--connectjdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--direct \
--table pokemon \
--target-dir /user/everis-bigdata/pokemon/1 \
--where "Legendary=1"
```

*Dicas*

Verificar o yarn

```shell
sudo service hadoop-yarn-resourcemanager status
```

ifconfig

Spoilers Aceleração dos desafios

```shell
SELECT * FROM trainning.pokemon WHERE Legendary IS true; (65)
SELECT * FROM trainning.pokemon WHERE Type2 = ""; (386)
SELECT * FROM trainning.pokemon ORDER BY Speed DESC LIMIT 10;
SELECT * FROM trainning.pokemon ORDER BY HP LIMIT 50;
SELECT Number, Name, SUM(HP+Attack+Defense+SpAtk+SpDef+Speed) AS Total FROM trainning.pokemon GROUP BY Number ORDER BY Total DESC LIMIT 100;

sudo -u hdfs sqoop import \
--connect jdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--direct \
--table pokemon \
--target-dir /user/everis-bigdata/pokemon/1 \
--where "Legendary=1"

sudo -u hdfs sqoop import \
--connect jdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--direct \
--table pokemon \
--target-dir /user/everis-bigdata/pokemon/2 \
--where "Type2=''"

sudo -u hdfs sqoop import \
--connect jdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--split-by 1 \
--target-dir /user/everis-bigdata/pokemon/3 \
--query 'SELECT * FROM pokemon WHERE $CONDITIONS ORDER BY Speed LIMIT 10'

sudo -u hdfs sqoop import \
--connect jdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--split-by 1 \
--target-dir /user/everis-bigdata/pokemon/4 \
--query 'SELECT * FROM pokemon WHERE $CONDITIONS ORDER BY HP LIMIT 50'

sudo -u hdfs sqoop import \
--connect jdbc:mysql://localhost/trainning \
--username root --password "Everis@2021" \
--split-by 1 \
--target-dir /user/everis-bigdata/pokemon/5 \
--query 'SELECT Number, Name, SUM(HP+Attack+Defense+SpAtk+SpDef+Speed) AS Total FROM pokemon WHERE $CONDITIONS GROUP BY Number ORDER BY Total DESC LIMIT 100'
```

<br>

<br>

<br>

------

## Como realizar consultas de maneira simples no ambiente complexo de BigData com HIVE e Impala

*Aprenda mais sobre Hive e Impala*

:calendar: 21/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/Live-21-01-2021-Hive_Impala.pdf)

*Notas da live*



<br>

<br>

<br>

------

## Explorando o poder do NoSQL com Cassandra e Hbase

*Aprenda como trabalhar com NoSql trabalhando com o banco de dados Cassandra e Hbase.*

:calendar: 22/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*



<br>

<br>

<br>

------

## Intensivo de Python - O mínimo que você precisa saber

*Aprenda a base de Python necessária para se dar bem em engenharia de dados , passando pelos conceitos essenciais para trabalhar com uma aplicação corporativa de alto nível.*

:calendar: 25/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*

<br>

<br>

<br>

------

## Trabalhando com serviços de mensageria real time com Python e Kafka na prática

*Aprenda como integrar o Python com Apache Kafka, um dos sistemas de mensageria corporativos mais utilizados no mercado.*

:calendar: 26/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*



<br>

<br>

<br>

------

## Processando grandes conjuntos de dados de forma paralela e distribuída com Spark

*Aprenda mais sobre Apache Spark, a ferramenta Big Data para o processamento de grandes conjuntos de dados mais utilizada em grandes projetos.*

:calendar: 27/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*



<br>

<br>

<br>

------

## Criando pipelines de dados eficientes - Parte 1

*Eleve seus conhecimentos com PySpark e processe grandes quantidades e faça um streaming em tempo real.*

:calendar: 28/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*



<br>

<br>

<br>

------

## Criando pipelines de dados eficientes - Parte 2

*Continue sua jornada para dominar PySpark vendo boas práticas de como ter mais domínio dos seus dados.*

:calendar: 29/01/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*





<br>

<br>

<br>

------

## Orquestrando BigData em Ambiente de Nuvem

*Aprenda como aproveitar o melhor do ambiente de nuvem para montar seu ambiente de big data de uma maneira profissional.*

:calendar: 01/02/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*



<br>

<br>

<br>

------

## Scala: o poder de uma linguagem multiparadigma

*Aprenda como mais sobre uma linguagem Scala, explorando seus principais tópicos e as suas vantagens de utilização em ambiente de Big Data.*

:calendar: 02/02/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*



<br>

<br>

<br>

------

## O que você precisa saber para construir APIs verdadeiramente restfull

*Dicas para construir APIs do rest ao estado restfull, todas as boas práticas que soluções de microserviços de alto nível precisam ter.*

:calendar: 03/02/2021		:timer_clock: 20:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*



<br>

<br>

<br>

------

## Graduação - habilidades que diferenciam um sênior na everis

*ACELERAÇÃO GLOBAL EVERIS*

:calendar: 04/02/2021		:timer_clock: 19:00h		:hourglass: 2 horas

<br>

[Slides](/.pdfs/.pdf)

*Notas da live*

