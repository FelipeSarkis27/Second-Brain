## Noções básicas do ambiente Linux
### SUSE SLES 15 SP2
- Definição
SUSE é uma distribuição Linux desenvolvida na Alemanha, SLES significa SUSE Linux Enterprise Server, 15 é a versão estável (uma das últimas) e SP2 significa Service Pack 2, que é um conjunto de pacotes adicionados na versão 15 do Linux. As questões da Cesgranrio caem os seguintes tópicos:
	- Diretórios
	- Permissões
	- Comandos
### Diretórios
- /opt
É o diretório opcional, são os complementos que se adiciona na distribuição Linux, seria como a pasta arquivos de programas do windows, em que se instala programas adicionais.
- /Home
São os arquivos do usuário
- /mnt
Montagem de dispositivos externos e leitores de mídia óptica.
- /lib
Bibliotecas
- usr
User, são as configurações para todos os usuários. Quando se abre o Linux pela primeira vez é criado um perfil baseado nessas configurações do /usr e depois que o perfil é criado ele fica disponível em /home.
- bin
São os binários, ou seja, os executáveis.
- /sbin
São os binários do sistema, ou seja, os executáveis do sistema.
- /root
É o diretório do administrador, super usuário, do *root* dentro do Linux.
- /var/log
É o diretório de armazenamento dos logs e eventos gerados pelo sistema operacional. Logs são os registros daquilo que foi realizado no sitema.
- /temp
São armazenados os arquivos temporários.
### Permissões
- chmod
É usado para alterar as permissões no Linux, que são escrever; ler e executar.
- chown
- É usado para alterar o proprietário, ou seja, o dono do item.
![[Pasted image 20210805191837.png]]
	- Essa tabela indica as permissões do SUSE para diferentes usuários, que são: o proprietário; grupo e público. 
	- Existem 3 casas, que são as da centena, dezena e unidade. As permissões são dadas para os 3 usuários, que dependendo da soma das casas é possível saber quais são as permissões de cada usuário diferente.
	- As permissões são: Read (Ler); Write (escrever) e Execute (executar).
	- Cada casa tem um tipo de usuário definido. A soma da casa das Centenas indica as permissões do proprietário, a soma das dezenas são as permissões do grupo e das unidades são as permissões do público.
	- Os números indicam as diferentes permissões e a soma deles indicam quais as permissões cada usuário tem. O número 1 indica execute; o número 2 indica escrita e o número 4 indica leitura.
		- Para memorizar é bom pensar da seguinte forma: o deus é o proprietário, depois vem um grupo de pessoas pra depois tornar aquilo público. E os números pode-se pensar assim: é preciso 1 executar o bloco de notas (só uma analogia para lembrar) para então 2 escrever e 4 ler.
	- Exemplo: 644.
		- 600 = centenas é proprietário. Soma: 200 (escrever) + 400 (ler) = 600. Então o administrador tem as permissões de leitura e escrita.
		- 40 = dezenas é grupo. Soma: 40 (ler). Então o grupo tem permissão apenas de leitura.
		- 4 = unidades é público. Soma: 4 (ler). Então o público tem permissão apenas de leitura.
	- O comando pode não vir em forma de números, mas em forma de letras, como: 
	-rw - r - - r - -.
	- O primeiro - indica que é um arquivo, se fosse um diretório seria D.
	- São 3 blocos, cada um está na ordem normal de proprietário (rw), grupo (r) e público (r).
	- **r** de *Read* significa 4; **w** de *write* significa 2 e **x** de *Execute* significa 1. Logo, o 644 = -rw - r - - r - -. rw = 400 + 200 = 600; r = 40 e r = 4.
	- r = 4; w = 2 e x = 1.
### Comandos
- du
Uso do disco (disco usage)
- kill
Matar processos
- uname
Conhecer a versão da distribuição (do sistema que está usando)
- ls
Lista os itens de um diretório
- zypper
É usado para instalar pacotes de software na versão SUSE, gerenciar atualizações e instalações de patches, gerenciar repositórios, etc.
- pwd
Imprimir o diretório atual (Print working directory)
- ln
Criação de links simbólicos (atalho)
- Find
Procurar uma informação nos itens
- netstat
Existe no win e no Linux, server para dar estatísticas da conexão de rede e da placa de rede
- cat
Juntar e mostrar
- cd
Alterar diretório
- toutch
Criar um arquivo vazio ou alterar as informações de metadados dos arquivos que já existem
- rm
Remover
- rmdir
Remover diretório
- mkdir
Criar diretório
- su
Executar como super usuário
- ifconfig
É o mesmo que ipconfig, configurar a interface de rede
- passwd
Senha
- top
Verificar processos
- grep
Localizar uma informação ou filtro para visualizar apenas algumas informações dos arquivos como um resumo

## Referências
https://www.youtube.com/watch?v=x_QD36teqNY