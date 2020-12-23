# Meu Currículo
> Mini projeto feito no curso de Git da Geek Academy, para aprender os comandos, funcionalidades e boas práticas do Git.

Esse projeto é um exercício de fixação do conteúdo aprendido no curso de Git da Geek Academy.

## Comandos Básicos de Git

Para iniciar um repositório Git:

```sh
git init
```

Para adicionar as configurações locais do usuário:

```sh
git config user.name "Pedro Botolli Santos"
git config user.email "pedrobotolli.santos@gmail.com"
```

Para verificar o status dos arquivos no repositório:

```sh
git status
```

Para ver as infos resumidas dos últimos 5 commits da *branch*:

```sh
git log --oneline -5
```

Para adicionar o arquivo.txt ao status *staged*:

```sh
git add arquivo.txt
```

Para consolidar (commitar) as alterações (pode ser adicionado o argumento --amend para colocar as alterações em cima do último *commit* ou alterar a mensagem do último *commit*) :

```sh
git commit -m "descrição das alterações"
```

Para verificar as alterações entre o último *commit* e o que está em *staged* antes de commitar:

```sh
git diff --staged
```

Para tirar o arquivo.txt do status *staged*:

```sh
git restore --staged arquivo.txt
```

Para voltar o arquivo.txt à versão do último *commit* (o *checkout* também é usado para alternar entre *commits* usando o id hash ou *branches*):

```sh
git checkout arquivo.txt
```

Para voltar o arquivo.txt à versão do último *commit* (o checkout também é usado para alternar entre *commits* usando o id hash ou *branches*):

```sh
git checkout arquivo.txt
```

Para voltar a última versão commitada mesmo que existam arquivos modificados:

```sh
git reset head --HARD
```

Além desses comandos, na parte básica do curso foi explicado a função e como usar o arquivo .GITIGNORE arquivo criado para apontar para o Git quais arquivos e diretórios que estão dentro do diretório do projeto e não serão versionados pelo Git.


## Exemplo de uso

Sinta-se a vontade caso queira usar esse projeto para consultar algum comando ou queira clonar para alterar adicionando as suas informações pessoais.


## Contato

Pedro Botolli Santos - [Linkedin](https://https://www.linkedin.com/in/pedro-botolli/) - pedrobotolli.santos@gmail.com
