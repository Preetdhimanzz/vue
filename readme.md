
# Install Dependencies
composer install

# Run Migrations
php artisan migrate

# Import records
php artisan db:seed

# If you get an error about an encryption key
php artisan key:generate

# Install Dependencies
npm install

# Watch Files to start VUE
npm run watch 
