# Simple Blox
Simple and blazing fast Bootstrap 4 Theme for your blog.

build using Bootstrap 4.1.3

![Hugo Artists Theme screenshot](https://raw.githubusercontent.com/okabrionz/simpleblox/master/images/screenshot.webp)


## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/okabrionz/simpleblox

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Getting started

After installing the Artists Theme successfully it requires a just a few more steps to get your site finally running.


### The config file

Take a look inside the [`exampleSite`](//github.com/okabrionz/simpleblox/tree/master/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/okabrionz/simpleblox/blob/master/exampleSite/config.toml). To use it, copy the [`config.toml`](//github.com/okabrionz/simpleblox/blob/master/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to customize this theme as you like.

### Config Settings

```
baseurl = "https://example.com/"
title = "Your Website Title"
author = "John Doe"
copyright = "Copyright © 2008–2018, John Doe all rights reserved." #You can also use HTML code here.
canonifyurls = true
paginate = 3
theme = "simpleblox" #This parameter is required to use this theme

[params]
facebook = "antihacx"
twitter = "antihacx"
github = "okabrionz"

[menu]
    [menu.main]
    name = "Home"
    url = "/"
    weight = "-10"
```