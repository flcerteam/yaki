# yaki

BUILD AND COMPILE ASSETS

If you haven't install node, install it now

Run: npm install

Then: npm run dev and wait for it to compile (currently, only admin assets are being compiled)

How to configure

composer install

Copy .env.example cp .env.example .env

Run migration and seed default data with php artisan migrate --seed

Symlink the storage folder to public. Run php artisan storage:link. This is important to display the uploaded images

If you run your app with php artisan serve connect to your installed db connection
