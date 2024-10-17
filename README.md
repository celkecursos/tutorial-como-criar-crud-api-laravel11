Neste tutorial, será apresentado como criar um CRUD com Laravel 11, ou seja, cadastrar, listar, editar e apagar.<br>
Por fim, será mostrado como integrar o framework Bootstrap no Laravel com Vite.<br>

## Requisitos

* PHP 8.2 ou superior
* Composer
* Node.js 20 ou superior<br>

## Como rodar o projeto baixado

Duplicar o arquivo ".env.example" e renomear para ".env".<br>
Alterar no arquivo .env as credenciais do banco de dados<br>

Instalar as dependências do PHP.
```
composer install
```

Instalar as dependências do Node.js.
```
npm install
```

Gerar a chave no arquivo .env.
```
php artisan key:generate
```

Executar as migration para criar a base de dados e as tabelas.
```
php artisan migrate
```

Iniciar o projeto criado com Laravel.
```
php artisan serve
```

Executar as bibliotecas Node.js.
```
npm run dev
```

Acessar o conteúdo do projeto no navegador.
```
http://127.0.0.1:8000
```

## Sequencia para criar o projeto

Criar o projeto com Laravel
```
composer create-project laravel/laravel .
```

Iniciar o projeto criado com Laravel
```
php artisan serve
```

Acessar o conteúdo padrão do Laravel
```
http://127.0.0.1:8000
```

Criar Controller
```
php artisan make:controller NomeController
```
```
php artisan make:controller UserController
```

Criar View
```
php artisan make:view nome
```
```
php artisan make:view users/show
```

Executar as migration
```
php artisan migrate
```

Criar Models
```
php artisan make:model NomeDaModel
```
```
php artisan make:model Course
```

Criar um arquivo de Request com validações
```
php artisan make:request NomeDoRequest
```
```
php artisan make:request UserRequest
```

Criar componente
```
php artisan make:component nome --view
```
```
php artisan make:component alert --view
```

Instalar as dependências do Node.js
```
npm install
```

Instalar o framework Bootstrap
```
npm i --save bootstrap @popperjs/core
```

Instalar o sass.
```
npm i --save-dev sass
```

Executar as bibliotecas Node.js
```
npm run dev
```

## Como usar o GitHub
Baixar os arquivos do Git
```
git clone --branch <branch_name> <repository_url> .
```
```
git clone https://github.com/celkecursos/tutorial-como-criar-crud-api-laravel11.git .
```

Listar o histórico de commits para identificar o hash do commit desejado.
```
git log
```

Fazer checkout para o commit específico.
```
git checkout <hash_do_commit>
```

