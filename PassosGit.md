#Comandos Úteis
	mkdir NomeDaPasta         -- cria pasta no diretorio local
	mv arquivo diretorio
	git init RelembrandoGit/  -- serve para iniciar um repositório	
	git add NomeDosArquivos   -- coloca os arquivos/diretorios em STAGED
	git commit -m "Descrição" -- faz um snapshot do STAGE e volta todos para UMMODIFIED
	git status                -- visutalizar status de todos do repositório
	git push origin master    -- empurra repositório para servidor remoto
	git remoto - v 			  -- mostra o link do repositório remoto
	git pull origin master    -- traz os arquivos em conflitos para repositório local
	git clone LinkRep         -- clona um repositório localmente