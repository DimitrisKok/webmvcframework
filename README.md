![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/webmvclogo.png)
# PHP WEB MVC Framework
The package **webmvcframework**, with the acronym of **WebMVC**, is an **object oriented** PHP framework that uses the **MVC architectural  pattern** for building web-based MySQL applications.

It offers to developers a complete set of functionalities for rapid development of data intensive web applications. Generally, it provides services for system decomposition that developers can do at different levels when they coding a complex web application. Firstly it provides the classes to achieve the Model, View, Controller decomposition and also to divide PHP code from HTML during the GUI designing. However, this is not the only feature provided by the Framework for acting on the application's decomposition.


The **Component Based Development**, that was used for building many framework’s features, permits to developers to apply another level of software decomposition and reuse. Framework’s components, in fact, realize **recurrent aspects** of web applications. Many of these aspects are regarding database, e.g. data listing, data listing and sorting, data listing and filtering, data listing and pagination, record management and the common table’s operations of select, insert, delete and update. 

> Framework offers a set of pre-built components for implementing the necessary server logic for frequently database management operations. Each component is itself designed with a MVC architecture, and is equipped by a Controller,Model,View, and HTML Template. 
Components are easy to use and developers can aggregate them into a root controller by using a composite criteria when building complex web pages. 
The component GUI can also easily updated or replaced to reflecting the graphic experience, simply by editing or replacing the component  HTML template. The component server logic will remain fully reusable without the need of any source code modifications.

## How to install
To install the framework download and copy it into an Apache web folder. Then go to the config directory and modify application.config.php according to your MySQL server configuration and Apache web folder you want to use for your application.
By default framework provides a small set  of examples. In a future time, I will provide you with more examples illustrating its functionalities.

## How to autogenerate PHP Model classes from your MySQL database
The util directory contains a file named **app_create_beans.php**.
Run it from your browser or from command line for executing ORM classes code auto generation regarding tables of a given MySQL database.

Warning !
Before running it you must configure MySQL access parameters by modifying **util\mysqlreflection\mysqlreflection.config.php** according to your MySQL configuration.
After running the utility you will find the autogenerated PHP classes into the **models\beans directory**.

## Documentation

###  WebMVC official wiki
You can start reading the wiki from [here](https://github.com/rcarvello/webmvcframework/wiki)

### Other information
You can dowload some PDFs, PPTs, and diagrams from [here](https://github.com/rcarvello/webmvcframework/tree/master/docs)

### Video Tutorial
An introduction to PHP WebMVC Framework   

[![IMAGE Video Tutorial](https://i.ytimg.com/vi/7zJFXLd4rk8/hqdefault.jpg?custom=true&w=196&h=220&stc=true&jpg444=true&jpgq=90&sp=67&sigh=5Dym90YTR05kyX82Kg8gW9VseUk)](https://www.youtube.com/watch?v=7zJFXLd4rk8&t=37s)

## Diagrams

### Main classes
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/framework.png)

### Handling HTTP requests - Loading and dispatching controllers
![alt tag](https://raw.githubusercontent.com/rcarvello/webmvcframework/master/docs/Dispatch%20and%20Create%20MVC%20Instance.png)


