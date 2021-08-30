# MVC assignment

**Problem Statement** :

You have to reconstruct the application you built for your Backend assignment using the MVC architecture.

While doing your MVC assignment keep these things in mind:-

* A README with setup instructions is compulsory and should have all the steps to set up your project successfully. Brownie points for anyone who automates this process.
* Bonus points will be awarded to those who build a good frontend :p
* Most importantly do not commit files where you have stored your passwords. Add that filename to .gitignore. 
* Place the config files (sample vhost file, db username/passwords, etc) in another folder 'config'.
* Make sure your vendor files are not uploaded.
* Again, Write good design.

**Resources:-**

* Object Oriented Programming in PHP
    \- http://php.net/manual/en/language.oop5.php
    \- https://valuebound.com/resources/blog/object-oriented-programming-concepts-php-part-1
    \- https://daylerees.com/php-namespaces-explained/
* Composer
    \- https://getcomposer.org/doc/00-intro.md
* MVC concepts
    \- https://medium.freecodecamp.org/model-view-controller-mvc-explained-through-ordering-drinks-at-the-bar-efcba6255053
    \- https://www.tomdalling.com/blog/software-design/model-view-controller-explained/
* PDO
    \- https://phpdelusions.net/pdo
* ToroPHP
    \- https://github.com/anandkunal/ToroPHP
    \- How you can write a simple router: http://blogs.shephertz.com/2014/05/21/how-to-implement-url-routing-in-php/
* twig
    \- https://twig.symfony.com/doc/2.x/
* vhost
    \- https://tecadmin.net/create-virtual-hosts-in-apache-on-ubuntu
* mod_rewrite
   \- https://code.tutsplus.com/tutorials/an-in-depth-guide-to-mod_rewrite-for-apache--net-6708

An MVC application for example : https://github.com/sin3point14/mvc-lecture

If you run into any error, try to resolve the error by yourselves to some extent using these two magic tricks:-

* var_dump($variable); die() ;
* tail -f /var/log/apache2/mvc.error.log
