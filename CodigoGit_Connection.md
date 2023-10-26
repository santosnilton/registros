# Conectando um Repositório local no Repositório remoto  
## Inicializar o Repositório Local
	git init  
## Verifique a Conexão com o GitHub
	ssh -T git@github.com
## Gerar uma chave SSH LOCAL
	ssh-keygen -t ed25519 -C "seu_email@example.com"  	
## Copie a chave SSH
	type C:\Users\adm\.ssh\id_ed25519.pub  # para Windows  
## Faça a conexão no Host do GitHub
	Acesse sua conta no GitHub.
	Vá para as configurações de segurança.
	Selecione "SSH and GPG keys."
	Clique em "New SSH key" e cole a chave pública que você copiou no passo anterior.
 ## Verifique a existência de Repositórios Remotos  
	git config --get remote.origin.url  
## Adicionar/Ligar o Repositório local ao remoto  
	git remote add <origin> <URL-do-Repositório-Remoto>  
## Consultando um Repositório  
	git remote  
	git remote -v  
## Enviando arquivos do Repositório local para o Repositório remoto  
 	
  O uso da opção "-u" (ou "--set-upstream") configura o branch local para rastrear o branch remoto  
  
	git push -u <repositório remoto> <branch local>  
 
 Envie um branch local específico para um branch remoto específico no repositório remoto. 

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
---   

  
