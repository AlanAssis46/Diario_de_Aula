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
- Então o sistema deve solicitar pelo título, autor, editora, ano, ISBN, categoria e número de tombo para concluir o cadastro

### Livro já está Cadastrado
- Dado que o título do livro que está sendo cadastrado já esteja no sistema
- Quando for realizada a tentativa de cadastro
- Então o sistema deve informar que o título do livro já está cadastrado e, em seguida, perguntar se deseja adicionar mais uma unidade do título ao sistema (ex: Pequeno principe - 1x Disponível | "Deseja adicionar mais uma unidade ao sistema? sim:não" se sim, atualizar para 2x Disponível)

### 
- Dado que o livro está em más condições 
- Quando for cadastrar o livro

  

