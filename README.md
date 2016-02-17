#Linux Ubuntu
##Comando para verificar em qual diretorio eu estou:
pwd

##Comando para listar os arquivos e pastas do diretorio:
ls

##Comando para printar mensagens no terminal:
echo (mensagem)
##Salvando uma mensagem em um arquivo:
echo(mensagem) > (arquivo)

Para adicionar conteudo no arquivo sem sobrescreve-lo usar >> no lugar de >

##Comando para ler o conteudo de um arquivo no terminal:
cat (arquivo)
##Comando para limpar o terminal:
clear
##Comando para mostrar TUDO dentro do diretorio:
ls -la
##Comando de ajuda dos outros comandos:
man (comando)
##Comando para mostrar qual usuário esta usando o terminal:
whoami
##Comando para entrar em um diretorio:
cd (nome do diretorio)

##Comando para ir para o diretorio anterior:
cd ..
##Comando para criar um diretorio:
mkdir (nome do diretorio)

##Comando para remover um diretorio:
rmdir (nome do diretorio) 

##Comando para remover um arquivo:
rm (nome do arquivo)

##Comando para remover tudo no diretorio e o diretorio:

rm -r (nome do diretorio)/

##Comando para copiar o conteudo de um arquivo para outro:
cp (nome do arquivo com o conteudo) (nome do arquivo destino)

Para mover no lugar de copiar, usar mv no lugar de cp

##Comando para mover um arquivo para um diretorio:
mv (nome do arquivo) (nome do diretorio)/

##Comando para copiar um diretorio para outro:
cp -r (nome do diretorio a ser copiado) (nome do diretorio destino)

##Comando para compactar um diretorio em um arquivo ZIP:
zip -r (nome do arquivo).zip (nome do diretorio)/

Se for zipar um arquivo apenas nao usa a flag -r

##Comando para descompactar um arquivo ZIP:
unzip (nome do arquivo).zip

Se passar a flag -l ele mostra o que tem no arquivo zip


