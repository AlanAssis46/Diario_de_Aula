## História de Usuário: Cadastro

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



