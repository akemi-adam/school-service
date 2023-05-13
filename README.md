# School Service
API em Laravel que simula o serviço de uma escola para ser intregada com outros serviços. Isso faz parte de um projeto da disciplina de Programação Orientada a Serviços.

Para rodar o serviço, use o seguinte comando:

```shell
php artisan serve
```

Ou, caso queira determinar qual porta rodar a aplicação:

```shell
php artisan serve --port <Alguma porta não reservada>
```

## Endpoints

|Verbo|Endpoint|Descrição
|-|-|-|
|GET|http://localhost:8000/|Lista todos os endpoints do serviço|
|GET|http://localhost:8000/hello|Retorna a mensagem: `Hello, World!`|

## Dependências

- <a href="https://laravel.com/docs/10.x">Laravel</a>