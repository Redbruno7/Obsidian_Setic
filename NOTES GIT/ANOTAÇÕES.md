___

Inicializar repositório = git init
___

Ciclo de Vida dos Status dos Arquivos

- **Untracked**: Momento que o arquivo foi adicionado, mas ainda não foi reconhecido pelo Git;
- **Unmodified**: Existe no Git, mas não foi modificado;
- **Modified**: Arquivo modificado;
- **Staged**: Momento que a versão for concluída, retorna para _Unmodified_.
___

Comandos

- **git status**: Estado do repositório no momento;
- **git add**: Adiciona o arquivo;
- **git commit -m "Mensagem"**: Faz um commit referente ao estado do arquivo;

- **git log**: Exibe a Hash do commit, o autor, a data e a mensagem do commit;
- **git log --decorate**: Mais infos;
- **git log --author="nome"**: Modificações de um autor específico;
- **git shortlog**: Nome dos autores, quantos commits, e quais commits foram;
- **git shortlog -n**: Nome dos autores, quantidade de commits;
- **git log --graph**: O que está acontecendo e quais as versões da branch;
- **git show (hash)**: Mudanças dos commits.

- **git diff**: Mostra a modificação que foi feita;
- **git diff --name-only**: Somente o nome do arquivo que foi modificado.

- **git checkout**: Retorna o arquivo para antes da edição;
- **git reset HEAD**: Retorna o arquivo para o status inicial (Ex: Tira do Stage e recoloca no Modified);
- **git reset --soft --mixed --hard**: Soft (retorna o commit para status de stage), Mixed (Retorna o arquivo para Modified), Hard (Reseta pro ponto inicial do commit), sempre pro commit para baixo.

- **git branch -b nome_da_branch**: Cria branch;
- **git branch**: Mostra todas as branchs
- **git checkout nome_da_branch**: Troca determinada branch;
- **git branch -D nome_da_branch**: Apaga a branch.