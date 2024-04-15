# pratica-git
Uso exclusivo para prática de comandos git

~~~bash
git config --global core.editor "code --wait"
~~~

O comando acima define o Visual Studio Code como editor padrão das mensagens de commit

~~~bash
git commit --allow-empty
~~~

O parâmetro `--allow-empty` permite a criação de um commit vazio para fins de testes e prática do Git.

~~~bash
git commit -a 
~~~

O parâmetro `-a` adiciona todos os arquivos modificados ou não ignorados ao commit atual.

~~~bash
git checkout -b novoBranch
~~~

O parâmetro `-b` alterna  para `novoBranch` criando o branch. O mesmo acontece com o comando `git switch` com o parâmetro `-c`.