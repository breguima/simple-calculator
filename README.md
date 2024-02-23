Importamos a classe HTML do módulo IPython.display, que nos permitirá exibir HTML dentro de uma célula no Google Colab.
Definimos uma string multiline que contém o código HTML e JavaScript da calculadora. Este código define a estrutura da calculadora (campos de entrada, botões) e inclui estilos CSS embutidos para estilização.
A função HTML() é usada para exibir o código HTML no Google Colab. Ela renderiza a string HTML definida anteriormente e exibe a calculadora dentro de uma célula do notebook.

Examinando mais detalhadamente o código HTML e JavaScript:

- A estrutura HTML define uma página da web básica com um título "Calculadora".
- O CSS embutido estiliza os elementos HTML para criar a aparência da calculadora.
- Os botões numéricos e operadores são definidos como `<input type="button">`, e cada um tem um evento `onclick` que chama a função JavaScript correspondente.
- As funções JavaScript `appendToDisplay`, `calculate` e `clearDisplay` manipulam o campo de entrada para exibir números, calcular expressões e limpar o campo.

Esse código cria uma interface de usuário simples de uma calculadora e a exibe dentro de uma célula no Google Colab.
