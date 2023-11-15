# Desafio HSL - ViaCEP

## Objetivo

O objetivo deste desafio é criar uma aplicação utilizando Docker e Docker Compose para configurar um ambiente no Azure com 1 CPU e 1GB de memória. A aplicação deve integrar uma API para carregar informações de CEP do Via-CEP, armazenar os dados em um banco de dados PostgreSQL e fornecer uma interface web para consulta.

## Requisitos do Desafio

Ambiente

- Utilizar Azure com 1 CPU e 1GB de memória.
- Instalar Docker e Docker Compose no ambiente.

## Tecnologias Obrigatórias

- Docker Compose: Configurar a aplicação utilizando o Docker Compose.
- HTTP Request: Carregar os dados do Via-CEP por meio de uma única requisição HTTP.
- Tempo de Resposta: Garantir que o tempo de resposta da requisição não ultrapasse 5 minutos.
- Resposta da Requisição: Comunicar a resposta da requisição com um status code e JSON.
- Banco de Dados: Cadastrar os dados no banco de dados relacional PostgreSQL.
- Componentes Docker: Utilizar obrigatoriamente 1 API, 1 Nginx e 1 banco de dados no escopo do Docker Compose.
- Frontend: Desenvolver o frontend em React, Vue ou Angular.
- CSS: Não será permitido o uso de CSS.
- Estrutura de Classes e POO: Utilizar estrutura de classes e programação orientada a objetos.
- Arquivo HTML: Limitação de 1 arquivo HTML para a interface web.

## Metas Adicionais

- Testes Automatizados: Implementar testes automatizados para verificar a integridade e a funcionalidade do aplicativo.
- Documentação da API: Criar documentação clara e completa para a API, descrevendo endpoints, métodos e exemplos de solicitações e respostas.

## Como Executar o Projeto

- Clone este repositório.
- Execute docker-compose up para iniciar a aplicação.
- Acesse a interface web em http://localhost:3000.

## Testes Automatizados

Para executar os testes automatizados, utilize o seguinte comando:

```
docker-compose run nome-do-servico-de-teste
```

## Documentação da API

A documentação da API está disponível em link-da-documentacao.

## Considerações Finais

Este desafio visa avaliar suas habilidades em configurar um ambiente Docker, integrar serviços externos, desenvolver uma interface web e realizar testes automatizados. Certifique-se de seguir as instruções e boas práticas de desenvolvimento.

Boa sorte!