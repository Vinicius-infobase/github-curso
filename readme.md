# Teste

Aula 11
Nova mensagem para testes.

Aula 12
Teste para chegagem de versões.

Segundo teste para versões.
Comandos:
 - git reset HEAD arquivo.x
 -- Remove o arquivo do staged, antes do commit. 

 - git checkout
 -- Remove todas mudanças não aplicadas.

 - git diff
 -- Mostra as diferenças de arquivos modificados.

 - git commit -am "msg"
 -- Adiciona ao commit todos os arquivos modificados (a) além da mensagem (m)

 - git add arquivo
 -- Adiciona as modificações ao estado de staged, para ser levado no próximo commit

 - git status
 -- mostra os status dos arquivos do repositório.


- git reset 
 -- soft
 --- Volta um commit, mas deixa o arquivo ainda adicionado

 -- mixed
 --- Volta o commit e remove o arquivo adicionado, mas mantem o arquivo modificado

 -- hard
 --- Volta o commit e remove todas as modificações feitas


 - Aula 16
 Testes de envio de commit para repositório.
 
 - git push origin master
 -- Envia (push) para o repositorio (origin (nome dele)) a branch desejada (master)


 - Aula 20
 - Criaçaõ de Branch
 -- git checkout -b nomebranch

 - Listar branchs
 -- git branch

 - Apagar branch
 -- git branch -D nomebranch

 - Trocar de branch
 -- git checkout nomebranch


 - Aula 25
 - Gitignore
 -- Cria uma blacklist de arquivos específicos ou geral que impedem de serem mandados ao repositório no push
 -- Existe no próprio github um repositório com vários arquivos de .gitignore ja prontos para serem inseridos no projeto
 --- vi .getigore
 --- Editar ele como arquivo texto

 - Aula 27
 -- Alias: cria um apelido para um outro comando
 -- git config --gloval alias.apelido apelidado


