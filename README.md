# todolist

Projeto realizado nas aulas de java com spring boot da Rocketseat. Se trata de um WebService em java para cadastrar tarefas.
Funcionalidade:
{
  Controle de usuários {
    Cadastrar usuário onde a senha seja gravada criptografada;
  }
  Controle de tarefas(tasks) {
    Cadastrar tarefa para o usuário autenticado;
    Visualizar tarefas para o usuário autenticado;
    Editar tarefa usando o Id da tarefa, podendo informar no JSON apenas o campo que dejesa modificar;
  }
  Controles e validações adicionais {
    Autenticação de usuário para poder criar ou editar tarefas;
    Validações de cadastro e edição de tarefas, como tamanho de campos, usuário inexistente ou sem permissão(tentaiva de editar terefa que não é do usário);
    Uso de utilidades para ao editar apenas um campo, salvar os dados dos demais campos existentes.
  }
}
