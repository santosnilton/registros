# Sequência para realizar Push no GitHub via CLI
---
# Ligando e enviando alterações do Repo local para um Repo remoto  

## Atualizando Repositorio
Identificar a branch  

	git branch  
 Listar o Repositório  
 
 	git remote  

  
  	git remote -v

   Trocar de branch  
   
	git checkout <branch>

Salvar alterações  

	git add .  
Commitar alterações  

 	git commit -m "Mensagem do commit"  

  Empurrar as alterações

	git push <repositório remoto> <branch local>:<branch remoto>  
 Mostrar processo de pull/push

  	git show
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
 	ou  
 	git push origin HEAD:main

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

## Listar as Branch  
	git branch 
 
## Criar a Branch  
	git checkout -g <name>  
 
## Movimentar a Branch  
	git checkout <name>  
## Deletar a Branch  
	git branch -D <name>  

# Merge  

## Merge da Branch  
	git merge <nome>  
---
 
