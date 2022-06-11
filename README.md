# Git

- git status
    Retorna qual é o estado de como estão os status das diferentes "áreas" do git;
    ex.: Fiz alterações, quero commit-á-las MAS não dei "git add .";

- git init
    Inicializa um repositório .git na sua pasta local;

- git clone
    Inicializa um repositório .git, porém, clonando um repositório já existente para a sua pasta local;
    ex.: git clone "https://github.coom/algum-repositorio.git

- git remote add origin [link para o repositório remoto]
    Pede para o git atribuir um repositório remoto à uma variável específica.
    Por convensão, nós damos a essa variável o nome "origin".
    ex.: git remote add origin "https://github.coom/algum-repositorio.git

- git add .
    Rastrea todas as alterações, adições e remoções feitas nos arquivos da pasta que contém o .git
- git commit -m "Alguma coisa"
    Cria uma referência para as alterações feitas no último git add .
    Você pode ver todos os commits do projeto através do comando git log --all

- git branch [nome da branch]
    Cria uma nova branch com o nome passado no terminal git
- git branch -a
    Lista todas as branches criadas no seu projeto .git

- git checkout [nome da branch]
    Permite o desenvolvedor navegar entre branches ou commits
    Ex: git checkout master
    Ex: git checkout estilizacoes
    Ex: git checkout '1ED3F6381'

- git branch -d
    Deleta uma branch com o nome passado no terminal git
    Obs: Para deletar uma branch você primeiro precisa dar checkout para uma outra branch

- git checkout -b [nome da branch]
    Cria uma nova branch (assim como o git branch) com o nome especificado, e em seguida faz o checkout para ela

- git merge

- git push
- git pull
