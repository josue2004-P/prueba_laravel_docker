# INSTALAR CONTENEDOR 

docker-compose up -d --build

# ACCEDER AL SH DEL CONTENEDOR
docker exec -it <container_id> sh

# INSTALAR PAQUETES DE COMPOSER
composer i

# COPIAR .ENV E INSTALAR LA KEY
cp .env.example .env
php artisan key:generate


