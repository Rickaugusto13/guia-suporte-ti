# 🗄️ SQL Server para Analistas de Suporte e Sistemas

## Objetivo

Este documento reúne conceitos, comandos e boas práticas do SQL Server
utilizados no suporte e na sustentação de sistemas.

## Principais conhecimentos

-   SELECT
-   WHERE
-   ORDER BY
-   GROUP BY
-   INNER JOIN
-   LEFT JOIN
-   Views
-   Stored Procedures

## Consultas básicas

### Buscar todos os registros

``` sql
SELECT * FROM Clientes;
```

### Filtrar informações

``` sql
SELECT Nome, Cidade
FROM Clientes
WHERE Cidade = 'São Paulo';
```

### Ordenar resultados

``` sql
SELECT *
FROM Clientes
ORDER BY Nome;
```

## Boas práticas

-   Evitar `SELECT *` em consultas de produção quando não for
    necessário.
-   Validar consultas em ambiente de homologação sempre que possível.
-   Comentar consultas complexas.
-   Fazer backup antes de alterações críticas.

## Diagnóstico de incidentes

Checklist:

-   Validar se há conexão com o banco.
-   Verificar mensagens de erro.
-   Conferir parâmetros enviados pela aplicação.
-   Analisar logs.
-   Testar a consulta diretamente no SQL Server.

## Minha experiência

Durante minha atuação na SRM Asset utilizei o SQL Server para análise de
dados, investigação de incidentes, execução de consultas, apoio à
sustentação de sistemas financeiros e validação de informações para
usuários e áreas de negócio.

## Perguntas comuns em entrevistas

-   Qual a diferença entre INNER JOIN e LEFT JOIN?
-   O que é uma Stored Procedure?
-   Quando utilizar GROUP BY?
-   Como identificar uma consulta lenta?
-   O que é um índice?
