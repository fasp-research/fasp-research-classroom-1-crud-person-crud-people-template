# Desafio CRUD de Pessoas

Bem-vindo! Este desafio faz parte de uma pesquisa de mestrado e foi desenvolvido para testar suas habilidades de programação.

## Objetivo do Desafio

Você deverá implementar um programa que realiza as operações básicas de um CRUD (Create, Read, Update, Delete). No repositório, você encontrará duas classes que servirão de base para o desafio:

1. **Person.java**  
   Esta classe representa uma pessoa, contendo três atributos: `id`, `name` e `age`. A implementação desta classe já está finalizada, não sendo necessária nenhuma modificação adicional.

2. **CrudPeople.java**  
   Esta é a classe onde você implementará o desafio. O objetivo é criar um menu no método `main`, com as seguintes opções:

   1: **Create**  
   2: **Retrieve**  
   3: **Update**  
   4: **Delete**  
   5: **Exit**

Cada opção do menu deve chamar o método correspondente para realizar a operação indicada. Por exemplo, a opção 1 deve chamar o método `create()`.

### Detalhes das Operações

- **Create**:  
  No método `create()`, o sistema deve solicitar ao usuário os valores de `id`, `name` e `age`. Após receber esses dados, eles devem ser armazenados na memória.

- **Retrieve**:  
  No método `retrieve()`, o sistema deve solicitar ao usuário o `id` da pessoa que deseja consultar. Se o `id` existir, os dados da pessoa devem ser exibidos na tela. Caso contrário, o sistema deve exibir a mensagem "Pessoa não encontrada".

- **Update**:  
  No método `update()`, o sistema deve solicitar ao usuário o `id` da pessoa cujos dados deseja alterar. Em seguida, deve solicitar o novo `name` e a nova `age`. Se o `id` informado não existir, o sistema deve exibir a mensagem "Pessoa não encontrada".

- **Delete**:  
  No método `delete()`, o sistema deve solicitar ao usuário o `id` da pessoa que deseja excluir. Se o `id` existir, o registro deve ser removido da memória. Caso contrário, o sistema deve exibir a mensagem "Pessoa não encontrada".

---