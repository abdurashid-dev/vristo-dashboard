## Installation
1. Clone the repository
```bash
git clone
```
2. Install dependencies
```bash
composer install
```
3. Create a copy of the .env file
```bash
cp .env.example .env
```
4. Generate an app encryption key
```bash
php artisan key:generate
```
5. Create an empty database for our application
6. In the .env file, add database information to allow Laravel to connect to the database
7. Install NPM dependencies
```bash
npm install
```
8. Build assets
```bash
npm run build
```
9. Start the local development server
```bash
php artisan serve
```
10. You can now access the server at http://localhost:8000

## Requirements
- Laravel 8+
- PHP 7.4+
- MySQL 5.7+
- Composer
- Node.js
- NPM
- Git
- Docker (optional)
- Docker Compose (optional)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
- Abdurashid Abdumominov - [GitHub](https://github.com/abdurashid-dev)
