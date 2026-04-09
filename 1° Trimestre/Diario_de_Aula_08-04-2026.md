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

- Dado que o usuário já possui um cadastro 
- Quando for realizada a tentativa de cadastro
- Então o sistema deve exibir "Usuário já cadastrado" e mostrar o status desse usuário (Ativo ou Bloqueado)




