# Locadora
## Projeto de locadora seguindo os princípios de SOLID e teste com JUnit. 

O objetivo deste trabalho é avaliar o conhecimento e domínio do aluno em relação à aplicação dos cinco princípios de desenvolvimento de software para criar códigos limpos e fáceis de manter. Além disso, o aluno será avaliado em relação ao uso da implementação voltada a testes. 

A implementação deve conter os paradigmas de SOLID e deve ser implementado um conjunto de testes usando o JUnit.

A implementação deve conter os paradigmas de SOLID. Além disso, o aluno deve implementar um conjunto de testes usando o JUnit, pelo menos um teste para cada métodos de cada classe(com exceção de sets e gets).

Locadora: 
O programa gerencia uma locadora de filmes e series. 

O usuário(funcionário) deve ser capaz de inserir um novo filme ou serie na locadora. 

Cada um possui: Titulo; tempo de fita; gênero(pode haver mais de um gênero); se é Fita cacete ou  DVD; Setor (onde se localiza o produto na loja)(o setor é um código numérico); Código do produto (valor numérico para verificar o produto) (Series possui mais de uma Fita ou DVD, neste caso as series devem vim com uma lista de códigos); se está alugado ou não.

Também deve ser capaz de cadastrar um cliente. Cada cliente possui: Nome; CPF; Endereço (Rua/AV, número, Bairro, CEP, complemento).

Além disso, o usuário pode cadastrar uma locação. Cada locação vem com as seguintes informações: Lista de produtos a serem alugados; cliente; valor; tempo de locação. Lembrando que produtos já alugados não podem ser alugados novamente. O usuário deve ser capaz de:

➢Consultar dados do produto;

➢Consultar dados do Cliente;

➢Verificar se um produto está alugado ou não, e que data ele estará disponível;

➢Verificar quantos produtos com o mesmo título existem;

