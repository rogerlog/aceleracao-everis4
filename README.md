# Aceleração Global Dev Everis #4 :rocket:

Anotações das aulas. :pencil2::books:

- [Linux: A introdução ao sistema operacional](#Linux-:-A-introdução-ao-sistema-operacional)
- [Shell script - Manipulando Arquivos](#Shell-script---Manipulando-Arquivos)







<br><br><br>

------

## Linux : A introdução ao sistema operacional

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
- **Configuralção do Sistema Operacional - Parte 1**

Em Settings... Notifications... Search...  Privacy

Diagnostics - Enviar relatório de erros.

Atalhos do Ubuntu - Settings/Keyboard Shortcuts

- **Configuralção do Sistema Operacional - Parte 1**

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