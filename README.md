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
