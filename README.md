# Comandos inseridos para o primeiro PUSH
#### Ciando Pasta aulaGIT
<br> 
$ mkdir aulaGIT
<br>
$ cd aulaGIT/
<br>
#### Inicializando o GIT
$ git init
<br>
#### Criando o arquivo README.md
$ touch README.md
<br>
#### Verificando se o repositório contem alterações
$ git status
<br>
No ramo master

Submissão inicial.

Arquivos não monitorados:
  (utilize "git add <arquivo>..." para incluir o que será submetido)

    README.md

nada adicionado ao envio mas arquivos não registrados estão presentes (use "git add" to registrar)
#### Adicionando os arquivos e commitando
$ git add README.md
<br>
$ git commit -m "add primeiros passos do GIT no arquivo  README.md"
<br>
[master (root-commit) 1f05653] add primeiros passos do GIT no arquivo  README.md
<br>
 1 file changed, 5 insertions(+)
 <br>
 create mode 100644 README.md
<br>
#### Na pagina do Git Hub
Entrar na pagina do Github.
<br>
Clicar em "New Repository"
<br>
No campo "Repository name" inserir o nome do seu Repositorio que será "aulaGit"
<br>
Clicar em "Creat Repository"
<br>
#### Adicionando o remote
$ git remote add origin https://github.com/thiagotobias/aulaGit.git
<br>
#### Efetuando o primeiro push
$ git push origin master
