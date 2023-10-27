# Conectando um Repositório local no Repositório remoto  

## Verifique a Conexão com o GitHub
	ssh -T git@github.com

## Gerar uma chave SSH local
	ssh-keygen -t ed25519 -C "seu_email@example.com"  	

## Copie a chave SSH
	type C:\Users\adm\.ssh\id_ed25519.pub  # para Windows  

## Faça a conexão no Host do GitHub
	Acesse sua conta no GitHub.
	Vá para as configurações de segurança.
	Selecione "SSH and GPG keys."
	Clique em "New SSH key" e cole a chave pública que você copiou no passo anterior.
---
## Inicializar o Repositório Local
	git init 
---
## Listando os Repositórios  
	git remote  
	git remote -v  

---
## Para adicionar/ligar uma conexão do repositório remoto no repositório local
	git remote add <nome_do_repositório_remoto> <URL_do_repositório>
  
## Para (Fork), adicionar uma conexão extra do repositório remoto no repositório local
	git remote add upstream <URL_do_repositório_upstream> 


## Para configurar a relação de rastreamento entre um branch local e um branch remoto especificado  
	git branch --set-upstream-to=<nome_do_repositório_remoto>/<branch_remoto> <branch_local>  

---
### Mapear Repositórios  

## Descubra a URL do Repositórios Remotos  
	git config --get remote.<nome_do_repositório_remoto>.url  

## Descubra o <nome_do_repositório_remoto> pela URL
	git remote -v | grep 'https://github.com/seu-usuario/seu-repositorio.git'

---
### Movimentar Repositórios  

## Para remover repositório remoto
	git remote remove <nome_do_repositório_remoto>
	git remote rm <nome_do_repositório_remoto>


## Para push com configuração
	git push --set-upstream <nome_do_repositório_remoto> <branch local>  

	git push -u <nome_do_repositório_remoto> <branch local>
 
## Para enviar um branch local específico para um branch remoto específico no repositório remoto 
	git push <repositório remoto> <branch local>:<branch remoto>

---   
  
## Movimentação de arquivos  
---   

## Status  
	git status  
## Logs  
	git log  
## Detalhes  
	git diff  
 ### Criar Arquivo  
	touch <name.type>   
## Criar/Remover Pasta(Diretório)  
	mkdir <name>  
		rm <name> |ou| rm -f <name>  
## Salvar o Arquivo no Git  
	git add <name.type>  
## Snapshot(package)  
	git commit -m "Digite a mensagem"  

---    
# Movimentação de Branch  
---    
## Criar a Branch  
	git checkout -g <name>  
## Listar as Branch  
	git branch  
## Movimentar a Branch  
	git checkout <name>  
## Deletar a Branch  
	git branch -D <name>  
---    
## Merge  
---    
## Merge da Branch  
	git merge <nome>  


## Para desfazer merge
	git merge --abort


## Para criar uma nova branch e fazer um commit dos arquivos não rastreados:
	git checkout -b temp-branch  
	git add bilixapp/  
	git commit -m "Committing untracked files in bilixapp"  


## Para guardar as mudanças temporariamente 
	git stash
---   

  
