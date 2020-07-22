# status
[![npm version](https://badge.fury.io/js/hexo-cute.svg)](https://badge.fury.io/js/hexo-cute)

# Hexo-cute

I want a perfect page to show for my blog, so I made [this plugin](https://github.com/rozbo/hexo-neat), but one day some guys said it was too slow
[https://github.com/rozbo/hexo-neat/issues/13](https://github.com/rozbo/hexo-neat/issues/13), and I try to fix it, but I can't, hexo
doest provide any api to get the resource that changed.
I have tried many methods, including reading the database, comparing hashes myself, etc., but the coupling in this place is so high that we have no chance to intervene.

Finally, as a last resort, I used this solution, monkey patch, which is hooked by myself and is not officially supported by hexo. To make matters worse, with the hexo update, this scheme may fail. So the risk is controlled by yourself.

## Installation
``` bash
$ npm install hexo-cute --save
```


## Options
To Enable Auto neat , you must config like this:
``` yaml
cute:
  enable: true
  html:
    enable: true
    #....
  css: 
    enable: true
    #.....
  js: 
    enable: true
    #.....
```
## Sponsor
The project is develop by [JetBrains Ide](https://www.jetbrains.com/?from=puck)

[![](https://www.jetbrains.com/company/brand/img/logo1.svg)](https://www.jetbrains.com/?from=puck)
