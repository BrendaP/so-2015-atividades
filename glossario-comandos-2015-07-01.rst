======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Brenda Patricia dos Santos Nascimento
:Matrícula: 20121144010176
:Data: 01/07/2015

cat
 Este comando envia o conteúdo de um ou mais arquivos para a saída padrão ou para um outro arquivo.
 Exemplo: Podemos usar o comando cat para exibir os arquivos na tela. Por exemplo,
cat > teste1- Serve para criar arquivo teste1 e escrever algo nele
cat teste1- mostra o que há no arquivo.
cat teste2 > Cria o arquivo teste2
cat teste1 >> teste2- O que há em teste1 é escrito em teste2.
Mostra na tela o conteúdo dos arquivos teste1 e teste2.


cd
O comando “cd” serve para acessar e mudar de diretório corrente. Ele é utilizado para a navegação entre as pastas do computador.
Exemplo: cd /home/baixaki/Desktop – Acessa a pasta correspondente à área de trabalho do usuário baixaki.

cp
copia arquivos e diretórios.
Exemplo: 
 Copiar o arquivo passwd do diretório /etcpara o diretório /home/fabio/.
$ cp  /etc/passwd   /home/fabio/
Se o diretório de trabalho atual já for o /home/fabio, podemos também usar o ponto (.) para indicá-lo como local de destino, como a seguir:
$ cp  /etc/passwd   .
2. Copiar o arquivo passwd do diretório /etc/ para o diretório /home/fabio/ renomeando a cópia como usuarios.txt:
$ cp  /etc/passwd   /home/fabio/usuarios.txt
3. Copiar todos os arquivos cujo nome se inicia com a letra l do diretório /lib/ para o diretório atual:
$ cp /lib/l* .
4. Criar um link simbólico no diretório atual para o arquivo /etc/group:
$ cp  -s  /etc/group .
5. Fazer uma cópia de backup de um arquivo no mesmo diretório, com outro nome (muito útil quando precisamos alterar arquivos de configuração do sistema):
$ cp  passwd  passwd.bkp
6. Copiar o diretório /home/fabio/Documentos e todo o seu conteúdo recursivamente para o diretório /home/fabio/backup/:
$ cp /home/fabio/Documentos  /home/fabio/backup/



cowsay
 Cowsay é um programinha onde uma vaca desenhada em ascii fala uma frase escolhida por você.
 Exemplo:
 Depois de instalado, pode chamar o programa desta forma:
 cowsay MundoLunga.com
 Outro exemplo:
cowsay -f tux seutexto
A sintaxe é:
cowsay -f [nomedodesenho] [oquequerfalar]


echo
  Mostra uma mensagem que você escreveu no termial do computador.
  Exemplo:
  echo "MENSAGEM"
  MENSAGEM.
   Ou, aparece o nome do usuário:
   echo $USER
   


env
  Exibi as variáveis de ambiente.


exit
  Descrição do comando


help
Mostra como utilizar os comnados.


HISTTIMEFORMAT="%d/%m/%y
  List os comandos que você digitou junto com a data e a hora.
  Exemplo:  
  HISTTIMEFORMAT="%d/%m/%y %T "
  history.


hostname
  Exibe o nome da máquina


ifconfig
  Configurar e posteriormente manter as interfaces da rede.
  Exemplo: ifconfig -a: exibe informações sobre todas as interfaces de rede (ativadas e desativadas).


last
  Descrição do comando


lastb
  Descrição do comando


ls
Exibe os arquivos que estão dentro da pasta na qual o usuário está no momento.
Para usá-lo basta digitar ls. Existem variações, tais como ls -l, com a qual é possível obter informações mais detalhadas sobre os arquivos, como permissões e tamanho.


mkdir
Este comando cria diretórios.
Exemplo: mkdir DIRETORIO – A pasta DIRETORIO foi criada no local onde o usuário se encontrava.

mv
O comando mv pode ser usado para mover ou renomear arquivos.
Exemplo:


nome="fulano
  Descrição do comando


passswd
  Mudar a senha do seu usuário.


pwd
Exibe a pasta atual na qual o usuário se encontra.
Exemplo: Se o usuário baixaki digitar cd ~/ e em seguida digitar pwd, o retorno será /home/baixaki .


set
  Descrição do comando


tree
  Este utilitário lista o conteúdo de um diretório usando o formato de árvore. Ele tem a mesma função do comando ls. A diferença consiste na maneira como as informações são exibidas.
  Exemplo:
tree /etc
exibe arquivos e diretórios que estã abaixo do diretório /etc.


tty
  Descrição do comando


vim
  Editor de texto.


wait
  Descrição do comando


wall
  Descrição do comando


which
  Descrição do comando


while
  Descrição do comando


who
 Quem está ligado a rede.


whoami
  Mostra o nome do usuário.
  


    write
        Escreve mensagem para alguém que está na mesma rede que você.
        Exemplo:
         write antunes
         olaa!
         

