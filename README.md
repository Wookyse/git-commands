# git-commands
Comandos para configurar o Git e comandos usados no Git ✔


Fluxos 

	||||| • $ git init: inicializa o repositório GIT (necessário)
	||||| • $ git  add .: prepara os arquivos para serem commitados
	||||| • $ git commit -m "mensagem": faz o commit dos arquivos preparados com uma mensagem


Configurar Git

	||||| • $ git config --global user.name "your_name"
	||||| • $ git config --global user.email "your_mail"


Navegação Git

	||||| • $ git status: mostra as modificações.
	||||| • $ git rm --cached: remove os arquivos para serem commitados
	||||| • $ git log: consegue ver todos os commits e o id da versão do commit
	||||| • $ git branch "nome": criar uma branch
	||||| • $ git branch: mostra todos os branch
	||||| • $ git checkout "nome_do_branch": entrar no branch pelo nome
	||||| • $ git merge "nome_do_branch": adicionar um branch ao branch atual.
	||||| • $ git pull: atualiza o branch selecionado

Exemplo: entra no branch master: $ git checkout master
Adicionar o branch staging ao master: $ git merge master (Lembrando que você tem que estar no Branch que vai receber o merge)


Upload on GitHub

	||||| • $ git remote add nome-do-repositório-remoto https://github.com/wookyse/nome-do-projeto.git (adiona o projeto e os branch da pasta que está aberta)
	||||| • $ git remote: aparece os repositórios adicionados
	||||| • $ git branch -M main: muda o nome do master (padrão) para main
	||||| • $ git push -u nome-do-repositório-remoto main: vai puxar tudo o que ta no repositório local, para o repositório remoto no branch main
	||||| • $ git clone https://github.com/wookyse/nome-do-projeto.git
