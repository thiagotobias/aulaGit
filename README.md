$ mkdir aulaGIT
$ cd aulaGIT/
$ git init
$ touch README.md
$ git status
No ramo master

Submissão inicial.

Arquivos não monitorados:
  (utilize "git add <arquivo>..." para incluir o que será submetido)

    README.md

nada adicionado ao envio mas arquivos não registrados estão presentes (use "git add" to registrar)

$ git add README.md
$ git commit -m "add primeiros passos do GIT no arquivo  README.md"
[master (root-commit) 1f05653] add primeiros passos do GIT no arquivo  README.md
 1 file changed, 5 insertions(+)
 create mode 100644 README.md

Após isto.
Entrar na pagina do Github.
Clicar em "New Repository"
No campo "Repository name" inserir o nome do seu Repositorio que será "aulaGit"

Clicar em "Creat Repository"

Quick setup — if you’ve done this kind of thing before
or

We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line

echo "# aulaGit" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/thiagotobias/aulaGit.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/thiagotobias/aulaGit.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.



