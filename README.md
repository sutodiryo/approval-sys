**Approval System API with swagger docs**

## Expense management
- Create new expense
- View existing expense
- Edit expense
- Approval expense
- Delete expense

**Instalation**

1. Open directory on bash/terminal.
2. Create a mysql database then prepare and apply settings to the .env file :
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_approval_expense_sys
DB_USERNAME=root
DB_PASSWORD=
```
3. Generate artisan key:
```bash
php artisan key:generate
```
4. Dependency install:
```bash
composer install
```
5. Execute database migration & seeder :
```bash
php artisan migrate --seed
```
6. Run application:
```bash
php artisan serve
```
7. You can open application documentation on `http://localhost:8000/api/documentation`
