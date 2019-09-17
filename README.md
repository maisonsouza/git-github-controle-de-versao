# Curso de Git e Github: Controle e compartilhe seu código
![](https://www.alura.com.br/assets/api/share/curso-git-github-controle-de-versao.png)

## O que é GIT?

## Iniciando os trabalhos

## Compartilhando o trabalho

## Trabalhando em equipe

## Manipulando as versões
Nesta aula, aprendemos:

Nesta aula, aprendemos:

- Que o Git pode nos ajudar a desfazer alterações que não vamos utilizar;
- Que, para desfazer uma alteração antes de adicioná-la para `commit` (com `git add`), podemos utilizar o comando `git checkout -- <arquivos>`;
- Que, para desfazer uma alteração após adicioná-la para `commit`, antes precisamos executar o `git reset HEAD <arquivos>` e depois podemos desfazê-las com `git checkout -- <arquivos>`;
- Que, para revertermos as alterações realizadas em um `commit`, o comando `git revert` pode ser a solução;
- Que o comando `git revert` gera um novo `commit` informando que alterações foram desfeitas;
- Que, para guardar um trabalho para retomá-lo posteriormente, podemos utilizar o `git stash`;
- Que, para visualizar quais alterações estão na `stash`, podemos utilizar o comando `git stash list`;
- Que, com o comando `git stash apply <numero>`, podemos aplicar uma alteração específica da `stash`;
- Que o comando `git stash drop <numero>` remove determinado item da `stash`;
- Que o comando `git stash pop` aplica e remove a última alteração que foi adicionada na `stash`;
- Que o `git checkout` serve para deixar a cópia do código da nossa aplicação no estado que desejarmos:
 - `git checkout <branch>` deixa o código no estado de uma `branch` com o nome `<branch>`;
 - `git checkout <hash>` deixa o código no estado do *commit* com o hash `<hash>`.

## Gerando entregas
- Que é possível visualizar quais alterações foram realizadas em cada arquivo, com o comando `git diff`;
- Que, digitando apenas `git diff`, vemos as alterações em nossos arquivos que não foram adicionadas para `commit` (com `git add`);
- Que é possível comparar as alterações entre duas *branches* com `git diff <branch1>..<branch2>`
- Que é possível comparar as alterações feitas entre um `commit` e outro, através do comando `git diff <commit1>..<commit2>`;
- Que o Git nos possibilita salvar marcos da nossa aplicação, como por exemplo, lançamento de versões, através do `git tag`;
- Que o comando `git tag -a` é utilizado para gerar uma nova *tag*;
- As ***Releases*** do GitHub, que são geradas para cada *tag* do Git criada em nosso repositório.


https://cursos.alura.com.br/user/maisongalvao/course/git-github-controle-de-versao/certificate
