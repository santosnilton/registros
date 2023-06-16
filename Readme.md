# Sequência para realizar Push no GitHub via CLI
# Ligando e enviando alterações do Repo local para um Repo remoto 
---
## Criar Pasta(Diretório)  
	mkdir <name>  
## Remover pasta	
    rm <name>  
    |ou| 
    rm -f <name>  
		  
## Inicializar o Repo  
	git init  
### Criar Arquivo  
	touch <name.type>  
## Salvar o Arquivo no Git  
	git add <name.type>  
## Snapshot(package)  
	git commit -m "Digite a mensagem"  
## Verificar Chave SSH  
	https://docs.github.com/pt/authentication/  connecting-to-github-with-ssh
  
## Ligando o Repo local com um remoto  
	git remote add <origin> git@github.com:santosnilton/<name>  
## Consultando o Repo  
	git remote  
	git remote -v  
## Enviando os arquivos do Repo local para o Repo remoto  
	git push -u origin master  

# Movimentação de arquivos  

## Status  
	git status  
## Logs  
	git log  
## Detalhes  
	git diff  
## Criar Arquivo  
	touch <name.type>  
## Salvar o Arquivo no Git  
	git add <name.type>  
## Snapshot(package)  
	git commit -m "Digite a mensagem"  

# Movimentação de Branch  

## Criar a Branch  
	git checkout -g <name>  
## Listar as Branch  
	git branch  
## Movimentar a Branch  
	git checkout <name>  
## Deletar a Branch  
	git branch -D <name>  

# Merge  

## Merge da Branch  
	git merge <nome>  


  # Lei até aqui ?