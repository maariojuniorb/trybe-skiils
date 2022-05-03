comandos:
git init ( iniciar o git)

git branch -m master main ( alterar o nome da branch principal de master para main )

git remote add origin "URL_DO_REPOSITÓRIO" ("Para vincular o reposório local com o do github")

git remote -v ("verificar se está configurado com o github")

git add ( . para referenciar todos arquivos da pasta atual ou nome do arquivo: exemplo "git add . " ou "git add arquivo.txt", sempre adicionar antes de realizar o commit)

git commit -m " * " ( para comitar um arquivo, o "*" siginifica descrição, sempre colocar o mais detalhado possível)

git push -u origin main ( manda os arquivos para o github. usar -u origin main na primeira vez que for utilizar, após isso somente git push)

git clone (e chave SSH sem parênteses) ( para clonar um projeto do github, exemplo "git clone git@github.com:maariojuniorb/trybe-skiils.git")

git log (" verificar os commits ou auterações ")

git branch "nome da nova branch sem aspas" ("cria uma branch separada para não alterar a branch main, não esquecer depois de tudo ok dar o merge")

git merge (" fanexa as modificações de branch separada para branch main ou para outra branch ")

git checkout "nome da branch" ( muda para branch selecionada, sem aspas exemplo: git checkout main)
