## História de Usuário: Cadastro de Aluno

- Como estagiária
- Quero realizar o cadastro de um aluno
- Para que ele posso realizar o empréstimo de um livro

## Cenários

### Fluxo Principal

- Dado que o aluno ainda não possui uma conta
- Quando for realizado o cadastro
- Então o sistema deve adicionar o usuário e atribuir o status "Ativo" para ele.

### Usuário já possui uma conta

- Dado que o usuário já possui um conta 
- Quando for realizada a tentativa de cadastro
- Então o sistema deve exibir "Usuário já cadastrado" e mostrar o status desse usuário (Ativo ou Bloqueado)

### Tipo de Usuário
- Dado que o usuário é um aluno
- Quando for selecionado o tipo de usuário (Aluno, Professor ou Funcionário)
- Então o sistema deve solicitar um campo adicional "Matrícula" para ser preenchido (tanto para aluno quanto para professor)


## História de Usuário: Cadastro de livro

- Como bibliotecária
- Quero cadastrar um livro
- Para que ele seja catalogado no sistema

## Cenários

### Fluxo Principal
- Dado que o livro ainda não está cadastrado no sistema
- Quando for catalogar o livro
- Então o sistema deve solicitar pelo título, autor, editora, ano, ISBN, categoria, condição, valor em caso de dano ou perda e número de tombo para concluir o cadastro

### Livro já está Cadastrado
- Dado que o título do livro que está sendo cadastrado já esteja no sistema
- Quando for realizada a tentativa de cadastro
- Então o sistema deve aumentar a quantidade de livros com o título cadastrado em uma unidade.

### Livro Danificado
- Dado que o livro está em más condições
- Quando o livro for cadastrado
- Então o sistema deve catalogar o livro, porém não deve disponibilizá-lo para empréstimo





  

