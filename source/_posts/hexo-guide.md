---
title: Blogging with Hexo
thumbnail: /images/hexo.png
---
Welcome to the first post of our blog! We are using [Hexo](https://hexo.io/) to generate most of this website. In order to use Hexo, check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can check open issues on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start From Scratch
Install [npm](https://www.npmjs.com/)
Open the command line and run the following commands:
``` bash
$ hexo init <folder>
$ cd <folder>
$ npm install
```
\<folder\> is the location that you want to install your hexo server.
More info: [Download npm](https://www.npmjs.com/)

## Clone Repository (Optional)
In our case, we host the code in [Github](https://github.com/Nowhere-Know-How/HexoBlog). You can clone it by installing [git](https://git-scm.com/) and running the following commands.

``` bash
$ git clone https://github.com/Nowhere-Know-How/HexoBlog.git
```
More info: [Our Github Repository](https://github.com/Nowhere-Know-How/HexoBlog)
More Info: [Install git](https://git-scm.com/)

### Create a new draft
Hexo works with a templating system using markdown. To make a draft for local writing, you can run the following command. Each draft is created with a folder corresponding to the images and other assets the article requires. 
``` bash
$ hexo new draft "<title>"
```

### Writing
While writing, you can reference the writing [documentation](https://hexo.io/docs/writing.html) to link images, videos, and even code snippets.
More info: [documentation](https://hexo.io/docs/writing.html)

### Promote draft to a post 
When you are done modifying that markdown file, you can promote it to a post with the following command.
``` bash
$ hexo publish post "filename"
```

### Run server
For development, you can run a test server by running the following command and navigating to "localhost:4000" with any browser!
``` bash
hexo server
```

More info: [Server](https://hexo.io/docs/server.html)
 
### Generate static files
To generate the final deployable server files, run this command.
``` bash
hexo generate
```
More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites
You can also one-line deploy to git or heroku. Please refer to the documentation for this.
``` bash
hexo deploy
```
More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)


### Appendix - How to do Code blocks
Code blocks are done with triple backtick strings. Syntax highlighting is achieved through a hexo-plugin.
``` csharp
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
More info: [Code Blocks](https://hexo.io/docs/writing)
More info: [Plugins](https://hexo.io/docs/plugins)
