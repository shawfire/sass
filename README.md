# SASS
## SASS features explained.

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
sass --update blah.scss
```

+ To generate a 'my_blah.css' from 'blah.scss':
```
sass --update blah.scss:my_blah.css
```

+ To convert all the \*.scss files in the sass directory to \*.css files in the css_bin directory.
```
cd ..
sass --update sass:css_bin
```

+ Same as the above; but continue to perform sass compilations as changes are made to the scss files:
```
sass --watch sass:css_bin
```

## SASS variable:

Sass variables are declared with a $ character (as apposed to the @ character for less) and are defined like CSS variables:

1. numbers  '''$myNum: 18px; $myNum: 1.5em; $myNum: .25in; $myNum: 1.25rem;'''
2. strings  $myString: "text of a string..."
3. colors   $myColor: #00f; $myColor: blue;
4. booleans $myBool: false;
5. nulls    $myEmptyVar: null;
6. lists    myList: 2px 4px 6px 8px; myList: 1px solid black;
