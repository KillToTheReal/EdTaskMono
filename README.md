## Есть отдельная ветка с чистым проектом если нужно начать сначала

## Практические задания: 
### 1. Реализовать REST API для просмотра и редактирования личных данных пользователя: 
имя, фамилия. согласие на рассылку и адреса доставки. Адресов может быть несколько, каждый содержит регион, населенный пункт, улицу, дом, а также почтовый индекс, должна быть возможность создания, редактирования и удаления адресов. При сохранении данных необходимо осуществить валидацию данных (при помощи Form Request), и возвращать ошибки в виде, пригодном для отображение на клиентской стороне (возможно использование локализации).
	
### 2. Реализовать пример стандартного шаблона для клиентской части сайта, учитывая следующее: 
Наличие отдельного блока для SEO-тегов (include)
Использование шаблона на всех страницах сайта (extends)
Передача из дочерних компонент дополнительного кода - к примеру JS-script, которые необходимо подключать к странице напрямую. (push - stack) 
Включение в шаблон собираемых JS и CSS файлов, c учетом версии сборки.
Динамические страницы, которые создаются в админке при помощи текстового редактора. 
### 3. Отправить письмо менеджеру, отправив скрытую копию разработчику. 
### 4. Необходимо создать миграцию, наполнить ее данными при помощи сидера, создать запрос при помощи QueryBuilder, создать консольную команду, которая создаст файл с результатами запроса в формате csv. 
Существуют следующие сущности: 
пользователь, с именем, фамилией и городом.  
товар, с названием и ценой
рейтинг, выставленный пользователем товару, рейтингу может соответствовать отзыв
отзыв на товар, оставленный пользователем, с текстом, и количеством отметок “отзыв полезен”, отзыву может соответствовать выставленный рейтинг
	Получить все отзывы, оставленные пользователями из Самары или Волгограда, отзывы которых были полезны для более чем 10 пользователей, или которые оставили более 10 отзывов на товары стоимостью более 3 т.р., при среднем рейтинге всех отзывов пользователя на такие товары более 4.




<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

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
