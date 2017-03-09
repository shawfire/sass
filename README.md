# SASS [reference](http://sass-lang.com/)

## SASS installation and command line basics explained.

*Make sure you have ruby (https://www.ruby-lang.org/en/) and gem (https://rubygems.org/) installed.*
+ To install sass:
```
gem install sass
```

+ To get sass help:
```
sass -?
```

+ To generate a 'blah.css' from 'blah.scss':
```
sass --update Sass_Ex1_Variables.scss
```

+ To generate a 'my_blah.css' from 'blah.scss':
```
sass --update Sass_Ex1_Variables.scss:Sass_Ex1_Variables_bin.css
```

+ To convert all the \*.scss files in the sass directory to \*.css files in the css_bin directory.
```
cd ..
sass --update sass:sass_bin
```

+ Same as the above; but continue to perform sass compilations as changes are made to the scss files:
```
sass --watch sass:sass_bin
```

+ Test your Sass examples on a simple web server ([reference](http://sweetme.at/2013/08/28/simple-local-http-server-with-ruby/)):
```
ruby -run -e httpd . -p 8000
http://localhost:8000
```

## SASS variables:

Sass variables are declared with a $ character (as apposed to the @ character for less) and are defined like CSS variables:

1. numbers  ```$myNum: 18px; $myNum: 1.5em; $myNum: .25in; $myNum: 1.25rem;```
2. strings  ```$myString: "text of a string..."```
3. colors   ```$myColor: #00f; $myColor: blue;```
4. booleans ```$myBool: false;```
5. nulls    ```$myEmptyVar: null;```
6. lists    ```myList: 2px 4px 6px 8px; myList: 1px solid black;```

## Defining nested rules:

## Working with mixins:

## Using operators:

## Defining mixins with auguments:

## Using output-style formatting:

## Importing external files:

## Other options:
+ [Stylus](stylus-lang.com)
+ [PostCSS](https://github.com/postcss/postcss)
