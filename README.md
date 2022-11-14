# Labenu Music Awards.


### Sobre o projeto:

O LAMA, Labenu Musical Awards, um festival  com várias bandas famosas. A ideia desse projeto é criar um sistema de cadastro de bandas. Existe dois tipos de usuário sendo eles: 'NORMAL' e 'ADMINISTRADOR'.

### Funcionalidade:
- ```Cadastro.``` O usuário só precisa informar: email, nome, senha e o tipo de usuário (normal) ou (admin) para realizar o cadastro.

- ```Login.``` Para login é preciso informar: email e senha.

- ```Registrar bandas.``` O sistema deixará salvo as bandas que participarão dos três dias de shows, (sexta, sábado ou domingo). Para registrar a banda precisa informar: nome da banda ```name```, gênero da música ```musicGenre.```, e o nome de um responsável ```responsible.```  ***somente usuários admins podem registrar bandas***

- ```Visualização de detalhes sobre a banda.``` Recebendo o id da banda ou o nome da banda retornará todas as informações salvas sobre ela.

- ```Adicionar um show a um dia.``` Para cadastrar um show preciso do id da banda e o dia (sexta, sábado ou domingo) e o horário em que ela irá se apresentar.
 Os horários válidos são entre 08h e 23h e só podem ser marcados em horários redondos, ou seja, pode ser 08h - 09h ou 09h - 13h mas não pode ser 09h - 10h30 ou 10h30 - 14h.
 
- ```Pegar todos os shows de uma data.``` Recebe um dia (sexta, sábado ou domingo) e retorna todos os shows daquela data (ordenados pelo horário), mostrando somente o nome da banda e o gênero musical principal.


### Tecnologias
 - NodeJs
 - Typescript
 - Express
 - Postman
 - Mysql
 - Knex
 - Paradigma de orientação a objetos
 - Arquitetura em camadas
 - Testes unitários
 - jest

 ### Documentação

[Documentação](https://bit.ly/documenter-lama)

## Autor

- [@ViniciusDuarte17](https://github.com/ViniciusDuarte17)
