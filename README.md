# How to make a static Single page website with gulp and shit
## What i need
* Nodejs
* Ruby
* SASS
* Compass
* SUSY
* Breakpoint
* Gulp
* Git

###Step 1 Installing
Install git 
~~~
https://git-scm.com/download/win
~~~
Install nodejs 
~~~
https://nodejs.org
~~~
Install ruby 
~~~
https://rubyinstall.org/download
~~~
**Installing continues in git bash**
Install sass
~~~
gem install sass
~~~
Install compass
~~~
gem install compass
~~~
Install susy
~~~
gem install susy
~~~
Install breakpoint
~~~
gem install breakpoint
~~~
Install gulp
~~~
 npm -g install gulp or sudo npm install -g gulp
~~~

###Step 2 Make required files
**Required files**
* package.json
* gulpfile.js

**Look at examples**

###Step 3 Download and install dependencies from package.json
~~~
npm install
~~~

###Step 4 Run gulp
In the project root folder start gulp with the gulp command
~~~
gulp
~~~


```
project
│   README.md
│   .gitignore    
│   gulpfile.js
|   package.json
|   
└───builds
|   ├───development
|       ├───css
|       ├───js
|       ├───images
|       │   index.html
|
└───components
    ├───sass
    |   ├───modules
    |   |   | _example_partial1.scss
    |   |   | _example_partial2.scss
    |   | _example_layout.scss
    |   | _mixins.scss
    |   | _variables.scss
    |   | style.scss
    ├───scripts
        | script.js
```

`marked`

**Note**
