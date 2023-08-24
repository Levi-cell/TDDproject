MULTIPLOS 

A ideia desse projeto é conferir se o número inserido é multiplo de 5 e 7 ou apenas de um desses números. se for multiplo de ambos será printado na tela "fizzbuzz". Caso seja apenas de 5 irá printar "fizz", caso seja de 7 irá printar "buzz" e caso não seja multiplo de nenhum deles irá printar "miss"

ORGANIZAÇÃO DOS ARQUIVOS/MÓDULOS

-main.py: irá executar o código para interação 
-Multiple.py: é a função que armazena a lógica do programa
-test.py: irá verificar se a função multiple está sendo executada corretamente e irá garantir a correção da função multiple, para isso use a estrutura do pytest para realizar o teste de caaso
-Dockerfile: irá permitir que você execute o projeto sem precisar baixar todas as ferramentas que utilizei abra seu CMD e confira os comandos no Dockerfile
-requirements.txt: esse arquivo lista todas as dependências do projeto

COMO EXECUTAR:

Para usar este projeto, siga as etapas abaixo:

1- Clone o repositório em sua máquina local usando o seguinte comando: git clone 
2- Abra um terminal ou prompt de comando e navegue até o diretório do projeto.
3 -Execute o arquivo main.py usando o interpretador Python: python main.py
4 -Insira um número natural quando solicitado para verificar se é múltiplo de 5, 7 ou ambos. O programa exibirá a mensagem correspondente.

EXECUTANDO OS TESTES

Para executar os testes automatizados para a função multiplo, execute o seguinte comando no diretório do projeto:
pytest test.py
Os testes serão executados e os resultados serão exibidos no console.

CONTRIBUIÇÃO
Contribuições para este projeto são bem-vindas. Se você quiser contribuir, siga estes passos:
1- Bifurque o repositório e crie um novo branch.
2- Faça as alterações ou acréscimos desejados.
3- Certifique-se de que os testes sejam aprovados com êxito.
4- Confirme suas alterações com uma mensagem de confirmação descritiva.
5- Envie suas alterações para seu repositório bifurcado.
6- Envie uma solicitação pull para o repositório original.

LICENÇA

Este projeto está licenciado sob a licença MIT. 
Sinta-se à vontade para modificar e usar este código para seus próprios fins. Contribuições e sugestões são sempre bem-vindas!

---------------------------------------------------------- ONLY ENGLISH---------------------------------------
MULTIPLES

The idea of this project is to check if the entered number is a multiple of 5 and 7 or just one of these numbers. if it is a multiple of both, it will be printed on the "fizzbuzz" screen. If it is only 5, it will print "fizz", if it is 7, it will print "buzz" and if it is not a multiple of any of them, it will print "miss"

ORGANIZATION OF FILES/MODULES

-main.py: will run the code for interaction
-Multiple.py: is the function that stores the program logic
-test.py: will check if the multiple function is being executed correctly and will ensure the correctness of the multiple function, for this use the pytest framework to perform the case test
-Dockerfile: will allow you to run the project without having to download all the tools I used open your CMD and check the commands in the Dockerfile
-requirements.txt: this file lists all project dependencies

HOW TO EXECUTE:

To use this project, follow the steps below:

1- Clone the repository on your local machine using the following command: git clone
2- Open a terminal or command prompt and navigate to the project directory.
3 -Execute the main.py file using the Python interpreter: python main.py
4 - Enter a natural number when prompted to check if it is a multiple of 5, 7 or both. The program will display the corresponding message.

PERFORMING THE TESTS

To run the automated tests for the multiple function, run the following command in your project directory:
pytest test.py
The tests will run and the results will be displayed on the console.

CONTRIBUTION
Contributions to this project are welcome. If you want to contribute, follow these steps:
1- Fork the repository and create a new branch.
2- Make the desired changes or additions.
3- Make sure the tests pass successfully.
4- Confirm your changes with a descriptive confirmation message.
5- Push your changes to your forked repository.
6- Submit a pull request to the original repository.

LICENSE

This project is licensed under the MIT license.
Feel free to modify and use this code for your own purposes. Contributions and suggestions are always welcome!
