# Formulario-de-cadastro

Este projeto consiste em um formulário de cadastro que coleta informações do usuário, incluindo nome, e-mail, senha, CPF, data de nascimento e endereço. O formulário implementa validações para e-mail e CPF e utiliza a API ViaCEP para buscar o endereço com base no CEP fornecido.

## Funcionalidades
* Cadastro de Usuário: Permite ao usuário se cadastrar fornecendo as informações solicitadas.
Validações:
* Email: Validação para garantir que o formato do e-mail está correto.
* CPF: Validação simples para garantir que o CPF possui 11 dígitos.
* Busca de Endereço: Utiliza a API ViaCEP para preencher automaticamente o endereço a partir do CEP informado.

## Tecnologias ultilizadas 
* HTML: Estrutura da página.
* CSS: Estilização do formulário.
* JavaScript: Lógica de validação e manipulação do DOM.
* API ViaCEP: Para busca de informações de endereço a partir do CEP.

## Imagens do site:
![](imagem%20site.png)
## Como usar
1- Preencha os campos do formulário.
2- Clique no botão "Buscar Endereço" após inserir o CEP para preencher automaticamente os campos de endereço.
3- Após preencher todos os campos, clique em "Cadastrar" para simular o envio do formulário. Validações de e-mail e CPF serão executadas.
5-Caso haja erros, mensagens de alerta serão exibidas.

## Exemplos de validação:
* Email Inválido: Caso o usuário insira um e-mail em um formato inválido, será exibida uma mensagem de alerta.
* CPF Inválido: Se o CPF não tiver 11 dígitos, uma mensagem de alerta será exibida.

## Referências:
* [via cep](https://viacep.com.br/)
* [Validações](https://github.com/Thaynaracarlo/validacoes)






