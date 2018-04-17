# yaki Project

#   BUILD AND COMPILE ASSETS

If you haven't install node, <a src="https://nodejs.org/en/download/">download it now</a>

Run: npm install

Then: npm run dev and wait for it to compile (currently, only admin assets are being compiled)

#   How to configure

composer install

Copy .env.example cp .env.example .env

Run migration and seed default data with <b>php artisan migrate --seed</b>

Symlink the storage folder to public. Run <b>php artisan storage:link</b>. This is important to display the uploaded images

If you run your app with <b>php artisan serve</b> connect to your installed db connection
