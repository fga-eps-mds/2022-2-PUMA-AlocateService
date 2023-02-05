# 2022-2-PUMA-AlocateService
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=fga-eps-mds_2022-2-PUMA-AlocateService&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=fga-eps-mds_2022-2-PUMA-AlocateService) [![npm version](https://img.shields.io/badge/npm--express-v4.17.1-blue)](https://www.npmjs.com/package/express/v/4.17.1)

O Alocador é o serviço essencial para o produto, para que seja feita, de forma automática, a relação entre a proposta feita e a disciplina a qual ela deve ser alocada.


## Como rodar

### Todos os microsserviços

Para utilizar o projeto com todos os microsserviços, é necessário seguir as instruções presentes em  [Api Gateway](https://github.com/fga-eps-mds/2022-2-PUMA-ApiGateway) ou na [Documentação](https://github.com/fga-eps-mds/2022-2-PUMA-Doc).


### Apenas Alocate Service

Para buildar e iniciar este serviço individualmente, execute:

``` $ make dev ```

Para apenas buildar, execute:

```$ make build ```

Para apenas iniciar, execute:

```$ make up ```

Para encerrar os containers de desenvolvimento execute:

``` $ make down ```

É necessário preencher o arquivo .env na raiz com as informações necessárias.

### Testes

Para rodar os testes, execute:

``` $ sudo make test```

``` $ sudo make test-debug```

É necessário preencher o arquivo .env na raiz com as informações necessárias.
