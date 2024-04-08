# Projeto pass-in

# Sobre o projeto
Pass.in é uma aplicação construída durando o NLW UNITE, organizado pela [Rocketseat](https://rocketseat.com.br/ "Site da Rocketseat").

É uma aplicação de gestão de participantes em eventos presenciais

A ferramenta permite que o organizador cadastre um evento e abra uma página pública de inscrição.

Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.

O sistema fará um scan da credencial do participante para permitir a entrada no evento.

## Requisitos Funcionais
- O organizador deve poder cadastrar um novo evento;
- O organizador deve poder visualizar dados de um evento;
- O organizador deve poser visualizar a lista de participantes;
- O participante deve poder se inscrever em um evento;
- O participante deve poder visualizar seu crachá de inscrição;
- O participante deve poder realizar check-in no evento;

## Regras de Negócio
- O participante só pode se inscrever em um evento uma única vez;
- O participante só pode se inscrever em eventos com vagas disponíveis;
- O participante só pode realizar check-in em um evento uma única vez;

## Diagrama ERB
![Modelo Conceitual](https://github.com/gabrielqporto/assets/blob/main/passin.png)

# Tecnologias utilizadas
- Java
- Spring Boot
- JPA
- Maven
- Banco de dados: hsqldb

# Autor
Gabriel Quintino Porto

https://www.linkedin.com/in/gabriel-quintino-porto-366690159/
