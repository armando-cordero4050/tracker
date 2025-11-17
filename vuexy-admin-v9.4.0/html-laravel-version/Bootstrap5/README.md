<p align="center">
   <a href="https://1.envato.market/vuexy_admin" target="_blank">
      <img src="https://user-images.githubusercontent.com/5073095/204261769-2df47513-0798-4680-a0b9-1b77673c6fc5.svg" alt="vuexy-logo" width="40px" height="auto">
   </a>
</p>

<h1 align="center">
   <a href="https://1.envato.market/vuexy_admin" target="_blank" align="center">
      Vuexy - Bootstrap 5 HTML Laravel Admin Template
   </a>
</h1>

<p align="center">Most Powerful & Comprehensive Bootstrap 5 HTML Laravel Admin Dashboard Template built for developers!</p>

<p align="center">   
   <a href="https://github.com/pixinvent/vuexy-html-laravel-admin-template/releases">
    <img src="https://img.shields.io/github/release/themeselection/materio-vuetify-vuejs-laravel-admin-template-free.svg" alt="GitHub release">
  </a>
   <a href="https://twitter.com/pixinvents" target="_blank">
      <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/pixinvents">
   </a>
</p>

<p align="center">
   <a href="https://1.envato.market/vuexy_admin" target="_blank" align="center">
      <img src="https://user-images.githubusercontent.com/749684/162939708-f5e4abeb-4c24-439f-8efb-c3f6b8abd402.jpg" alt="Vuexy - HTML Admin Dashboard Template">
   </a>
</p>

## Introduction

Vuexy – HTML Laravel Admin Dashboard Template – is the most developer friendly & highly customizable Admin Dashboard Template based on Bootstrap 5.

If you’re a developer looking for an admin dashboard that is developer-friendly, rich with features, and highly customizable look no further than Vuexy. We’ve followed the highest industry standards to bring you the very best admin template that is not only fast and easy to use but highly scalable. Offering ultimate convenience and flexibility, you’ll be able to build whatever application you want with very little hassle.

Build premium quality applications with ease. Use our innovative admin template to create eye-catching, high-quality WebApps. Your apps will be completely responsive, ensuring they’ll look stunning and function flawlessly on desktops, tablets, and mobile devices.

[View Demo](https://pixinvent.com/demo/vuexy-html-bootstrap-admin-template/landing/)

## Installation ⚒️


> We recommend you use mentioned system configuration
- Node version (^14.17.3  or LTS)
- Composer Version (^2.0.4)
- PHP version (^8.0.2)
- Laravel Version (^9.0.0)
- Laravel-Mix version (^6.0.6)

1. Install the composer packages

   ```bash
    composer install
    ```

2. In the root directory, you will find a file named `.env.example`, rename the given file name to `.env` and run the following command to generate the key (You can also setup your database credentials here).

    ```bash
    php artisan key:generate
    ```

3. By running the following command, you will be able to get all the dependencies in your node_modules folder:
  
    ```bash
    yarn

    # npm install [for npm]
    ```

4. To run the project, you need to run following command in the project directory. It will compile the php files & all the other project files. If you are making any changes in any of the php file then you need to run the given command again.

    ```bash
    yarn dev

    # npm run development [for npm]
    ```

5. To serve the application you need to run the following command in the project directory. (This will give you an address with port number 8000.)

    Now navigate to the given address you will see your application is running.

    ```bash
    php artisan serve
    ```

6. To change the port address, run the following command:

    ```bash
    php artisan serve --port=8080 // For port 8080
    sudo php artisan serve --port=80 // If you want to run it on port 80, you probably need to sudo.
    ``` 

7. `Watching for changes:` If you want to watch all the changes you make in the application then run the following command in the root directory.

    ```bash
    yarn watch

    # npm run watch [for npm]
    ```

8. `Building for Production:` If you want to run the project and make the build in the production mode then run the following command in the root directory, otherwise the project will continue to run in the development mode.

    **Make sure to change the `APP_ENV=local`  variable's value `APP_ENV=production`.**

    ```bash
    yarn prod

    # npm run production [for npm]
    ```

    ### Required Permissions on server

    If you are facing any issues regarding the permissions, then you need to run the following command in your project directory:

    ```bash 
    sudo chmod -R o+rw bootstrap/cache
    sudo chmod -R o+rw storage
    ```
Please [visit](https://pixinvent.com/demo/vuexy-html-bootstrap-admin-template/documentation/laravel-init-installation.html) our docs for installation guide.

## Documentation 📜

Check out our live [Documentation](https://pixinvent.com/demo/vuexy-html-bootstrap-admin-template/documentation/laravel-introduction.html)

## Support 👨‍💻

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
