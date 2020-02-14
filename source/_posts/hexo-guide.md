---
title: Blogging with Hexo
thumbnail: /images/hexo.png
---
Welcome to the first post of our blog! We are using Hexo[Hexo](https://hexo.io/) to generate most of this website. In order to use Hexo, check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can check open issues on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
hexo server
```

More info: [Server](https://hexo.io/docs/server.html)
 
### Generate static files

``` bash
hexo generate
```
 
More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
hexo deploy
```

### How to do Code blocks

``` cs
using System;
using System.IO;

var today = DateTime.Now.ToString();
var message = $"Hello World, This file is created at {today}";

// Some fancy comment here

class Foo
{
  public void Bar()
  {
    Console.WriteLine("Hello World!");
  }
}

var obj = new Foo();
obj.Bar();

Console.WriteLine(message);
```


More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
