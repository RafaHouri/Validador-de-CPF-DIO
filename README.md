# Microsserviço Serverless de Validação de CPF 

Este microsserviço serverless em C# valida CPFs via requisição HTTP POST.

## Tecnologias

*   C#
*   .NET 8
*   VS Code
*   Azure Functions Core Tools

## Respostas

*   **200 OK:** "CPF válido e não consta na base de fraudes, débitos ou óbitos."
*   **400 Bad Request:** "CPF inválido." ou "Informe o CPF, por gentileza."

  ![resultado cpf válido](https://github.com/user-attachments/assets/9bfacab9-4a62-4ba7-86f0-be9170a2617c)
  ![resultado cpf inválido](https://github.com/user-attachments/assets/0017de14-4f70-48da-9096-86b0087d5b35)

