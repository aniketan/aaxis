
## Installation

- Clone seat- with git

```bash
  git clone https://github.com/aniketan/aaxis.git
```
- Install all project dependencies using composer
```bash
   cd aaxis
   composer install
```
- Create .env file from .env.example 

```bash
   cp .env.test .env
```
- update .env file with database configuration (`DB_DATABASE` , `DB_USERNAME` , `DB_PASSWORD`) 
 DATABASE_URL="mysql://DB_USERNAME:DB_PASSWORD@127.0.0.1:3306/DB_DATABASE?serverVersion=8.0.32&charset=utf8mb4"

- Execute DB migration 

```bash
   php bin/console doctrine:migrations:migrate
```


- Run application via LAMP or symfony 

```bash
   symfony server:start
```

Working Demo can be found here https://aaxis.buffernow.com/ 

