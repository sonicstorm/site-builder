Site Builder
============

Introduction
------------
Site Builder is a HTML5 Website Builder written in PHP. 
Site Builder is used to build amazing Web 3.0 HTML5 Applications.

Installation
------------

Using Composer (recommended)
----------------------------
The recommended way to get a working copy of this project is to clone the repository
and use `composer` to install dependencies using the `create-project` command:

    curl -s https://getcomposer.org/installer | php --
    php composer.phar create-project -sdev --repository-url="http://packages.zendframework.com" zendframework/skeleton-application path/to/install

Alternately, clone the repository and manually invoke `composer` using the shipped
`composer.phar`:

    cd my/project/dir
    git clone git://github.com/zendframework/ZendSkeletonApplication.git
    cd ZendSkeletonApplication
    php composer.phar self-update
    php composer.phar install

(The `self-update` directive is to ensure you have an up-to-date `composer.phar`
available.)

Another alternative for downloading the project is to grab it via `curl`, and
then pass it to `tar`:

    cd my/project/dir
    curl -#L https://github.com/zendframework/ZendSkeletonApplication/tarball/master | tar xz --strip-components=1

You would then invoke `composer` to install dependencies per the previous
example.

Using Git submodules
--------------------
Alternatively, you can install using native git submodules:

    git clone git://github.com/zendframework/ZendSkeletonApplication.git --recursive

Virtual Host
------------
Afterwards, set up a virtual host to point to the public/ directory of the
project and you should be ready to go!
