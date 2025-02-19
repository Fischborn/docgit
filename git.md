# Resumo dos comandos mais usados do GIT

### init
*init é usado para iniciar um novo repositório.*

Esse comando cria um novo repositório Git no diretório atual. Após a execução do comando, o diretório se torna um repositório Git e você pode começar a versionar seus arquivos.

### clone
*Clone é usado para copiar um repositório remoto.*

O comando `git clone <url-do-repositório>` cria uma cópia exata de um repositório remoto em sua máquina local. Ideal para começar a trabalhar em um projeto já existente.

### add
*Add é usado para adicionar arquivos ao staging area.*

O comando `git add <arquivo>` adiciona um ou mais arquivos para a área de preparação (staging area) antes de realizar o commit. Para adicionar todos os arquivos de uma vez, use `git add .`.

### commit
*Commit é usado para salvar as mudanças.*

O comando `git commit -m "mensagem"` cria um novo commit, que é uma captura das mudanças feitas. A mensagem de commit deve ser descritiva e explicativa sobre as alterações feitas.

### cd
*cd é usado para navegar entre diretórios.*

O comando `cd <diretório>` permite que você mude de diretório no seu terminal. Use esse comando para navegar entre pastas do seu sistema de arquivos.

### mkdir
*Mkdir é usado para criar novos diretórios.*

O comando `mkdir <nome-do-diretório>` cria um novo diretório com o nome especificado. Ideal para organizar projetos ou arquivos.

### config --local user.name
*Configuração local do nome de usuário.*

O comando `git config --local user.name "Seu Nome"` configura o nome de usuário para o repositório atual. Esse nome será associado aos commits realizados nesse repositório.

### config --local user.email
*Configuração local do e-mail do usuário.*

O comando `git config --local user.email "seuemail@dominio.com"` configura o e-mail para o repositório atual. Esse e-mail será associado aos commits realizados nesse repositório.

### status
*Status mostra o estado atual do repositório.*

O comando `git status` exibe quais arquivos foram modificados, adicionados, ou removidos, e ainda mostra quais arquivos estão prontos para o commit.

### push
*Push envia as alterações para o repositório remoto.*

O comando `git push` envia os commits locais para o repositório remoto. Isso atualiza o repositório com as mudanças feitas em sua máquina local.

### pull
*Pull é usado para atualizar o repositório local.*

O comando `git pull` baixa as alterações do repositório remoto e as aplica ao seu repositório local. Esse comando é usado para manter seu repositório local atualizado com as últimas mudanças feitas no repositório remoto.

### branch
*Branch cria e gerencia ramificações do repositório.*

O comando `git branch` permite que você visualize as branches existentes ou crie novas com `git branch <nome-da-branch>`. Isso permite o trabalho paralelo em diferentes funcionalidades do projeto.

### checkout
*Checkout é usado para mudar de branch ou restaurar arquivos.*

O comando `git checkout <nome-da-branch>` muda para a branch especificada, permitindo que você trabalhe nela. Também pode ser usado para restaurar arquivos individuais.

### merge
*Merge é usado para mesclar branches.*

O comando `git merge <nome-da-branch>` permite mesclar as mudanças de uma branch para a branch atual. Esse comando é comumente usado para integrar o trabalho de diferentes desenvolvedores.

### log
*Log exibe o histórico de commits.*

O comando `git log` mostra um histórico detalhado de todos os commits feitos no repositório, incluindo as mensagens, autores e datas.

### diff
*Diff compara as diferenças entre arquivos ou commits.*

O comando `git diff` permite visualizar as diferenças entre o seu repositório local e o último commit, ou entre dois commits.

### reset
*Reset é usado para desfazer commits.*

O comando `git reset <commit>` pode ser usado para mover a HEAD (referência para o commit atual) de volta a um commit anterior, desfazendo as alterações realizadas após ele. Pode ser útil para corrigir erros cometidos nos commits.
