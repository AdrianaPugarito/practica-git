# practica-git
# Comandos do Bash (para criar titulos)

# Aprendendo CLI

-pwd ele te mostra onde vc esta

-touch README.md para criar um readme a mão

-mv mais o nome da pasta ou arquivo para mover para esse lugar. Exemplo:
mv README.md => isso se criou fora da pasta a usar ele move esse arquivo parea lá, ou usar o:
echo "# practica-git" >> README.md => nesse caso ele cria um arquivo ja preenchido

-echo => para escrever algo no terminal ou em um arquivo

-cd mais o nome de um arquvio ou pasta para ir até outro lugar/diretorio

# Comandos Git

-git config --global --list 
> para ver as listas
-git config --global user.name "nome" 
>para definir nome global
-git config --global user.email "email@" 
>definir email
-git init 
>para iniciar o repositorio desde o Git bash
-git branch -M main ou master
>inicia pela primeira vez um branch
-git branch -v 
>para visualizar a branch criadas no projeto
-git branch -a -v 
>para visualizar os branchs remotos
-git add . 
>para adicionar todo os aqruivos modificados
-git add mais o nome de um arquivo 
>e só para dicionar esse arquivo
-git commit -m "primeiro commit"
>sempre que for subir um alteração devemos usar o commit, a letra -m e para identificar que e um msg
-git remote add origin "url do repositorio do GitHub"
>para adicionar esse commit ou alterações no repositorio
-git remote -v
>para visualizar os repositorios que estão no meu porjeto
-git -h 
>exibe os comandos gerais mais usados e para que se usam
-git comando -h 
> exibe ajuda sobre um comando especifico. Exemplo: git remote -h
-git clone + url de um reporsitorio
>para ter una copia de esse repositorio



