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

- git checkout
    Permite acessar um commit ou branch específico.
    Ex: git checkout 'EF12941D392AFE20'
    Ex: git checkout 'estilizacoes'

- git branch -a
- git checkout -b

- git push
- git pull

- git merge