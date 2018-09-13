Here i will explain how to start learn cake framework. (version 2.0)

Cake php is open source web framework.It follows the model–view–controller approach and is written in PHP.

CONTROLLER: Controllers handle requests and help co-ordinate and prepare responses for the client.
VIEW: Views are the presentation layer in CakePHP. They convert the data fetched from Models into the output format requested by the client.
MODEL: Models are the heart of your application. They handle the validation, storage and retrieval of your data.

Important Points to be know before start work on cake framework.

1. CakePHP Conventions
    -> Controller Conventions
    -> Model and Database Conventions
    -> View Conventions
    -> File and Class Name Conventions
        The Controller class KissesAndHugsController would be found in a file named KissesAndHugsController.php
        The Component class MyHandyComponent would be found in a file named MyHandyComponent.php
        The Model class OptionValue would be found in a file named OptionValue.php
        The Behavior class EspeciallyFunkableBehavior would be found in a file named EspeciallyFunkableBehavior.php
        The View class SuperSimpleView would be found in a file named SuperSimpleView.php
        The Helper class BestEverHelper would be found in a file named BestEverHelper.php
        
2. Helpers
    ->Helpers are the component-like classes for the presentation layer of your application.
        CacheHelper,
        FlashHelper,
        FormHelper,
        HtmlHelper,
        JsHelper,
        NumberHelper,
        PaginatorHelper,
        RssHelper,
        SessionHelper,
        TextHelper,
        TimeHelper
3. Elements
Many applications have small blocks of presentation code that need to be repeated from page to page, sometimes in different places in the layout. CakePHP can help you repeat parts of your website that need to be reused. These reusable parts are called Elements. Ads, help boxes, navigational controls, extra menus, login forms, and callouts are often implemented in CakePHP as elements. An element is basically a mini-view that can be included in other views, in layouts, and even within other elements. Elements can be used to make a view more readable, placing the rendering of repeating elements in its own file. They can also help you re-use content fragments in your application.

4. Scaffolding
    Application scaffolding is a technique that allows a developer to define and create a basic application that can create, retrieve, update and delete objects. Scaffolding in CakePHP also allows developers to define how objects are related to each other, and to create and break those links.
    
5. Folder Struture.
    

  1.bin folder => The bin folder holds the cake console executables.
  2. The config folder holds the  configuration files cakePHP uses. Database connection details, core configuration files.
  3.The plugin folder is where the plugins your application uses are stored.
  4.The logs folder normally contains your logs files, depending on your log configuration.
  5.The src folder will be where your applications source files will be placed.
  6.Test folder will be where you put the test cases for your application.
  7.The tmp folder is where cakephp store temporary date.
  8.The vendor folder is where cakphp and other application dependencies will be installed by composer. Editing these files is not advised,as composer will overwrite your changes next time you update.
  9.webroot directory is the public document root of your application. it contains all the files you want to be publicly reachable.
      
The src folder
  cake php src folder is where you will do most of your application development.
  
closer at the folder inside src.

    1.controller
      contains your application's controllers and their components
    2.Locale
      Stores string files for internationalization.
    3.Model 
      contains your applications tables, entities and behaviours.
    4.Shell
      contains the console command and console tasks for your application. 
    5.view
      Presentational classes are placed here: view, cells, helpers.
    6.Template
      Presentational files are places here:
      elements, error page, layouts, and view template files


