
# Git | Git Hub | DIO

Resumo para aprender e memorizar os "md", a sintaxe do Git e Git Hub e como usá-lo.

## 📚 Documentação
- [Documentação Git](https://git-scm.com/docs/git/pt_BR)
- [Documentação Git Hub](https://docs.github.com/pt)
- [Documentação Python](https://docs.python.org/pt-br/3.12/tutorial/)

## 💻 Resumos das Aulas

- O que são Branch:

- **Git log:** Nos mostra as informações dos nossos commit

- **Git reflog:** Nos dá uma tetalhação maior refente aos nosso commit, diferente de apenas "git log"

- **Git init:** Inicializa um repositório Git em um diretório local. Este comando cria um repositório Git vazio ou reinicializa um repositório existente.

- **Git clone:** Clona um repositório Git existente de um servidor remoto para o seu diretório local. Isso cria uma cópia local do repositório.

- **Git add:** Adiciona arquivos ao índice (staging area) para prepará-los para o commit. Você pode adicionar arquivos específicos usando git add nome_do_arquivo ou adicionar todos os arquivos com git add ..

- **Git commit:** Registra as mudanças feitas nos arquivos no repositório. Você precisa fornecer uma mensagem de commit para descrever as alterações. Por exemplo: git commit -m "mensagem do commit"

- **Git push:** Envia os commits locais para um repositório remoto, como o GitHub. Por exemplo: git push origin nome_do_branch

- **Git pull:** Obtém e mescla as alterações de um repositório remoto para o seu repositório local. Isso atualiza seu repositório local com as alterações mais recentes do repositório remoto.

- **Git branch:** Lista, cria ou exclui branches (ramos) no repositório. Por exemplo: git branch nome_do_branch cria um novo branch chamado nome_do_branch.

- **Git checkout:** Muda entre branches no repositório. Por exemplo: git checkout nome_do_branch muda para o branch chamado nome_do_branch

- **Git merge:** Combina as alterações de um branch com outro. Por exemplo: git merge nome_do_branch mescla as alterações do branch nome_do_branch com o branch atual.

- **Git status:** Mostra o estado atual do repositório Git, incluindo arquivos modificados, arquivos não rastreados, etc

- **Commit:** Um commit no Git é uma operação que registra as mudanças feitas nos arquivos do seu projeto. É como tirar uma fotografia do estado atual do seu código e salvar essa imagem no histórico do projeto.
- git add nome_do_arquivo_modificado
- git commit -m "Mensagem descrevendo as alterações feitas"

- **.Gitkeep:** é para o Git reconhecer um diretório vazio

- **rm -rf:** Usado para remover a força um vercionamento (.git) dentro de uma pasta

- **Git store:** Após fazer uma alteração indesejada, usamos esse argumento para restaurar o arquivo no estado anterior, ou seja, o estado do ultimo commit do arquivo. (git store "nome do arquivo")

- **Git commit --amend -m "nova mensagem":** Usamos para alterar a ultima mensagem do ultimo commit de um arquivo

- **Git reset --(soft, mixed e hard) + hash do commit:**
  - - **Soft:**Basicamente, o que esse comando nos dá é estarmos na ação posterior ao commit do hash selecionado; Ou seja, se fizemos um commit e depois estavmos em preparação de outro commit, esse comando nos leva a preparação do commit que iriamos fazer;
  - - **Mixed:** Poderiamos usar apenas "git reset" que dariamos no mesmo. Diferente do soft, nesse caso, ele não estaria na espera de preparação ou espera de um commit, ele nos levaria para a tela onde os arquivos do commit posterios estavam como "untrecked" e não aguardando commit, ou seja, ainda estaria na tela onde teriamos que usar "git add ." e depois  usarmos o "git commit -m"mensagem desejada";
  - - **Git reset <file> ou fit reset -- staged<file>**: remove o arquivo da arvore de preparação para area do "untracked"
    
