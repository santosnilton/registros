--
#ligando e enviando alterações do Repo local para um Repo remoto 
--
Criar Pasta(Diretório)
<br>
	mkdir <name>
		rm <name> |ou| rm -f <name>
Inicializar o Repo
<br>
	git init
Criar Arquivo
<br>
	touch <name.type>
Salvar o Arquivo no Git
<br>
	git add <name.type>
Snapshot(package)
<br>
	git commit -m "Digite a mensagem"
Verificar Chave SSH
<br>
	https://docs.github.com/pt/authentication/connecting-to-github-with-ssh

Ligando o Repo local com um remoto
<br>
	git remote add <origin> git@github.com:santosnilton/<name>
Consultando o Repo
<br>
	git remote
	git remote -v
Enviando os arquivos do Repo local para o Repo remoto
<br>
	git push -u origin master
--
Movimentação de arquivos
--
Status
<br>
	git status
Logs
<br>
	git log
Detalhes
<br>
	git diff
Criar Arquivo
<br>
	touch <name.type>
Salvar o Arquivo no Git
<br>
	git add <name.type>
Snapshot(package)
<br>
	git commit -m "Digite a mensagem"
--
Movimentação de Branch
--
Criar a Branch
<br>
	git checkout -g <name>
Listar as Branch
<br>
	git branch
Movimentar a Branch
<br>
	git checkout <name>
Deletar a Branch
<br>
	git branch -D <name>
--
Merge
--
Merge da Branch
<br>
	git merge <nome>
--
--
