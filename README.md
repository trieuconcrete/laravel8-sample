
## SET UP ON MacOS

### Setup sail alias in ~.bash_profile file
 - add `alias sail='bash src/vendor/bin/sail'` in ~.bash_profile file

### Setup Laravel project
 -  use `src/vendor/bin/sail` if without setup alias for sail

1. sail up -d
2. copy .env.example into .env
3. sail composer install
4. sail artisan key:generate
5. sail artisan migrate
6. sail artisan db:seed

## CONFIG
- Access:
   + website: http://localhost
   + Mail: http://localhost:8025

