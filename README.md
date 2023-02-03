# Pinga PHP framework

[![StandWithUkraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/badges/StandWithUkraine.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)

[![SWUbanner](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://github.com/vshymanskyy/StandWithUkraine/blob/main/docs/README.md)

Pinga is a modern, easy-to-use PHP framework designed to streamline web development and make it accessible to everyone. With Pinga, you can easily build powerful web applications using a variety of user-friendly components and features.

## Initial set of components

[Router](https://github.com/getpinga/router)

[DB](https://github.com/getpinga/db)

[Auth](https://github.com/getpinga/auth)

[HTTP](https://github.com/getpinga/http)

[Base64](https://github.com/getpinga/base64)

[Cookie](https://github.com/getpinga/cookie)

[Templates](https://github.com/thephpleague/plates) / external component

### Planned features

**Fast router:** Quickly and easily route requests to the appropriate handler using pinga/router or league/route

**[Authentication](https://github.com/getpinga/auth):** Powerful and user-friendly tool for implementing a secure login system for your web application. It allows you to easily customize the login process to suit your specific needs and provides a comprehensive user permission system for controlling access to different parts of your application. With Pinga's streamlined sign-up process, you can quickly and easily add new users to your application. In addition, Pinga's user impersonation feature allows you to easily debug and test your application by impersonating different users. This saves you time and helps ensure the quality of your application

**Database ORM:** Simplify database management and querying, using [pinga/db](https://github.com/getpinga/db)

**Database Optimizer:** [soar-php](https://github.com/guanguans/soar-php)

**Database Replication:** Database replication thanks to MariaDB Galera Replication or [php-mysql-replication](https://github.com/Gemini-D/php-mysql-replication)

**Audit log:** Keep track of your web application's activity, based on [Utopia Audit](https://github.com/utopia-php/audit)

**Database history generation:** Ensure data integrity and version control, with the great help of [PhpAudit](https://github.com/SetBased/php-audit)

**Datatables server pagination:** Efficiently handle large amounts of data with the help of [DataTables](https://datatables.net/) and [n1crack/datatables](https://github.com/n1crack/datatables)

**Messaging system:** Communicate with users and send notifications, thanks to [Utopia Messaging](https://github.com/utopia-php/messaging)

**Two factor authentication:** Add an extra layer of security to your login process, using [robthree/twofactorauth](https://github.com/robthree/twofactorauth) or [Authy](https://github.com/rinvex/authy)

**Logger:** Keep track of errors and debugging information with the help of [Monolog](https://github.com/Seldaek/monolog)

**Cache:** Make your app faster thanks to [Utopia Cache](https://github.com/utopia-php/cache) or [Phpfastcache](https://www.phpfastcache.com/)

**Payment providers:** Integrate with popular payment gateways, with a library based on [Utopia Pay](https://github.com/utopia-php/pay)

**Backup system:** Protect your data with regular backups, thanks to [PHPBU](https://phpbu.de/) or [Restic](https://restic.net/)







**Load balancing:** Load balancing for your apps via [pdoload](https://github.com/gonzie/pdoload)

**Machine learning/AI:** Soon we will support systems like [Jina AI](https://jina.ai/) or [MindsDB](https://mindsdb.com/)

**Templating engine:** Powerful and easy-to-use PHP templating engine for creating dynamic and customizable views for your web application, built on top of [Plates](https://github.com/thephpleague/plates)

**Admin panel UI:** Beautiful and intuitive admin panel UI crafted by [Tabler](https://tabler.io/)

To get started with Pinga, simply download the latest release from Github and follow the installation instructions in the documentation. Whether you are a seasoned web developer or just starting out, Pinga is the perfect choice for building modern, professional web applications.

## Support for Swoole

Swoole is a high-performance PHP networking extension that can greatly improve the speed and performance of your web applications. It is often used in conjunction with PHP frameworks like Pinga to enable real-time communication and asynchronous processing, which can be useful in a variety of scenarios, including:

* Real-time chat and messaging systems

* Online gaming and multiplayer applications

* Data streaming and event-driven applications

* Job queues and task scheduling

* Server-side rendering of dynamic web pages

By using Swoole, Pinga already integrates powerful asynchronous programming capabilities into your web applications, allowing you to create fast and responsive applications with real-time communication, server-side rendering of dynamic web pages, and much more.

We also use [SMProxy](https://github.com/louislivi/SMProxy)

# Installation instructions

To install the Pinga PHP framework, follow these steps:

1. Open a terminal or command prompt and navigate to the directory where you want to build your project.

2. Run the following command: ```composer require getpinga/pinga```

3. Wait for the installation to complete.

That's it! You can now start using the Pinga framework to build your web application. For more information on how to use Pinga, refer to the documentation and examples provided with the framework.
