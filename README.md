# Linux Ubuntu
## Comando para verificar em qual diretorio eu estou:
pwd

## Comando para listar os arquivos e pastas do diretorio:
ls

## Comando para printar mensagens no terminal:
echo (mensagem)
## Salvando uma mensagem em um arquivo:
echo(mensagem) > (arquivo)

Para adicionar conteudo no arquivo sem sobrescreve-lo usar >> no lugar de >

## Comando para ler o conteudo de um arquivo no terminal:
cat (arquivo)
## Comando para limpar o terminal:
clear
## Comando para mostrar TUDO dentro do diretorio:
ls -la
## Comando de ajuda dos outros comandos:
man (comando)
## Comando para mostrar qual usuário esta usando o terminal:
whoami
## Comando para entrar em um diretorio:
cd (nome do diretorio)

## Comando para ir para o diretorio anterior:
cd ..
## Comando para criar um diretorio:
mkdir (nome do diretorio)

## Comando para remover um diretorio:
rmdir (nome do diretorio) 

## Comando para remover um arquivo:
rm (nome do arquivo)

## Comando para remover tudo no diretorio e o diretorio:

rm -r (nome do diretorio)/

## Comando para copiar o conteudo de um arquivo para outro:
cp (nome do arquivo com o conteudo) (nome do arquivo destino)

Para mover no lugar de copiar, usar mv no lugar de cp

## Comando para mover um arquivo para um diretorio:
mv (nome do arquivo) (nome do diretorio)/

## Comando para copiar um diretorio para outro:
cp -r (nome do diretorio a ser copiado) (nome do diretorio destino)

## Comando para compactar um diretorio em um arquivo ZIP:
zip -r (nome do arquivo).zip (nome do diretorio)/

Se for zipar um arquivo apenas nao usa a flag -r

## Comando para descompactar um arquivo ZIP:
unzip (nome do arquivo).zip

Se passar a flag -l ele mostra o que tem no arquivo zip

## Comando para compactar um diretorio em um arquivo TAR:
tar -zcf (nome do arquivo).tar (nome do diretorio)

## Comando para descompactar um arquivo TAR:
tar -zxf  (nome do arquivo).tar

Se usar a flag -v para compactar ou descompactar, ele aumenta as imformações no log

## Comando para alterar a data de modificação de um arquivo:
touch (nome do arquivo)

## Comando para printar x primeiras linhas de um arquivo:
head -n x (nome do arquivo)

Se nao por o x ele printa as 10 primeiras

Se quiser ler as ultimas linhas, usar tail no lugar de head

## Comando para editar um arquivo no terminal:
vi (nome do arquivo)

## Comando para saber quais os processos que estao sendo executados no bash:
ps 

Para mostrar todos os processos do sistema, usar a flag -e 

## Comando para parar um processo:
kill (id do processo)

Se o processo tiver travado, passar a flag -9

## Comando para filtrar a lista de processos por nome:
ps -ef | grep (nome do processo)

Grep tambem serve para filtrar com outros comandos, como o cat por exemplo

## Comando para mostrar uma situação detalhada da cpu:
top

## Comando para matar todos os processos com determinado nome:
killall (nome do processo)

## Comando para vizualizar os processos em forma de arvore:
pstree

## Jogar um processo para o background:
Ctrl + Z para parar o processo
Comando jobs para ver o id do processo parado
bg (id do processo)

## Comando para voltar um processo do background para o foreground:
fg (id do processo)

## Abrir um processo e automaticamente jogar para o background:
(nome do processo) &

## Comando para alterar permissoes nos arquivos:
chmod 

Flags:
+x -> adiciona permissao de execução
+r -> adiciona permissao de leitura
+w -> adiciona permissao de escrita

Se trocar o + por - ele tira a permissao

Se passar uma das tres seguintes letras antes das flags:
o -> altera a permissao para outros
u-> altera permissao para o usuario
g-> altera permissao para o grupo

Ex: chmod o+rw README.md

## Comando para localizar um arquivo:
locate (nome do arquivo)

## Comando para atualizar o banco do linux:
updatedb

## Comando para saber qual arquivo vai executar se usar um comando X:
which X

## Comando para mudar o usuario:
su (nome do usuario)

## Comando para adicionar novo usuario:
adduser (nome do usuario)

## Comando para ver as variaveis de ambiente:
env

## Comando para procurar um programa disponivel para instalação:
apt cache search (nome do programa para busca)

## Comando para instalar um programa:
apt get install (nome do programa)

(Apenas como sudo)

Para remover, no lugar de install poe remove

## Comando para instalar .deb

dpkg -i (nome do arquivo)

(Apenas como sudo)

## Executar o ssh em modo grafico:
ssh -X (nome do usuario)@(ip do servidor)

## Comando para copiar um arquivo via SSH:
scp (nome do arquivo) (nome do usuario)@(ip do servidor):(diretorio de destino)







