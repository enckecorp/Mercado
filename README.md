# Mercado
> Sistema de gerenciamento de despesas alimentícias.

Uma aplicação focada na organização de despesas alimentícias residenciais. Ajuda no controle e auxilia na economia das despesas mensais. Gera relatórios em pdf e possui gráficos demonstrativos para facilitar a visualização dos gastos.

[Inserir foto aqui]

## Instalação

OS X & Linux:

```sh
- Apache 2.4.58
- MariaDB 10.4.32
- PHP 8.1.25
```

Windows:

```sh
- Apache 2.4.58
- MariaDB 10.4.32
- PHP 8.1.25
```

## Descrição

Uma aplicação focada na organização de despesas alimentícias residenciais. Ajuda no controle e auxilia na economia das despesas mensais. Gera relatórios em pdf e possui gráficos demonstrativos para facilitar a visualização dos gastos.

## Configuração para desenvolvimento

Para executar a aplicação em seu ambiente, além de instalar os requisitos listados acima é necessário criar o banco de dados "mercado" e importar o arquivo "mercado.sql" em sua versão do MariaDB, para ter as tabelas e colunas iniciais para o funcionamento do sistema. Também é necessário configurar as permissões dos diretórios "mercado/modules/compras
/anexos/" para 775.

## Meta

Encke Corporation – [@EnckeCorp](https://twitter.com/enckecorp) – contato@enckecorp.com.br

Distribuido sobre a licença MIT. See ``LICENSE`` for more information.

[https://github.com/enckecorp/Mercado/](https://github.com/enckecorp/Mercado/)

## Contribuindo

1. Crie um Fork (<https://github.com/enckecorp/Mercado/>)
2. Crie a branch para sua nova feature (`git checkout -b feature/fooBar`)
3. Dê um Commit em suas alterações (`git commit -am 'Add some fooBar'`)
4. Dê um Push para sua branch (`git push origin feature/fooBar`)
5. Crie um novo pull resquest
