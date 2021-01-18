# Aceleração Global Dev Everis #4 :rocket:

Anotações das aulas. :pencil2::books:

- [Linux: A introdução ao sistema operacional](#Linux---A-introdução-ao-sistema-operacional)
- [Shell script - Manipulando Arquivos](#Shell-script---Manipulando-Arquivos)







<br><br><br>

------

## Linux - A introdução ao sistema operacional

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



- **Praticando no terminal os comandos de diretórios e sistema - Parte 1**



- **Praticando no terminal os comandos de diretórios e sistema - Parte 2**



- **Revisão do conteúdo**



- **Certifique seu conhecimento**



<br><br><br>

------

## Shell script - Manipulando Arquivos

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

- **Certifique seu conhecimento**



