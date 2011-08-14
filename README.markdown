# Big Bang Technology Developer Setup Script:

## Inspired by: 

* http://woss.name/2011/01/23/converging-your-home-directory-with-chef/
* http://robots.thoughtbot.com/post/8700977975/2011-rubyists-guide-to-a-mac-os-x-development

## Prerequisites: 

* git (http://code.google.com/p/git-osx-installer/)
* Install GCC (https://github.com/kennethreitz/osx-gcc-installer)
* Install homebrew (https://github.com/mxcl/homebrew)
* You must own /usr/local

```
    sudo chown -R `whoami`:staff /usr/local
```

## TODO:

* install mysql
 * https://github.com/opscode/cookbooks/tree/master/mysql
* install imagemagick
 * https://github.com/opscode/cookbooks/tree/master/imagemagick
* install ffmpeg
 * https://github.com/37signals/37s_cookbooks/tree/master/ffmpeg
* install ack
* install rvm
* install/configure nginx
 * https://github.com/opscode/cookbooks/tree/master/nginx
* setup cookbook for different applications we have

## License

(The MIT License)

Copyright (c) 2011 Big Bang Technology Inc <cameron@bigbangtechnology.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE
