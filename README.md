## Welcome to Sherpa server page
*Sherpa is a simple http server serving static html files, it's written in c*  

## Initial motivations

We're making static web pages in our everyday life as Rails developer.

My principal tool is (Stasis)[http://stasis.me], I even build a ready to use template at [StasisTPL](https://github.com/FranckyU/StasisTPL). 

The problem was that stasis is buggy in development mode when I tried to run `stasis -d port` where I expect to have my static mockups served at `http://127.0.0.1:port`

So I decided to seek for a lightweight web server, written in C so it could fit within an executable, then I saw [this blog post](http://blog.abhijeetr.com/2010/04/very-simple-http-server-writen-in-c.html) and decided to build a version of it.

## What's Sherpa ?

Sherpa is a simple server that's able to serve static assets over http.

## How to use it ?

I compiled Sherpa in my linux box, but I think everyone could compile it on Mac or Windows without any problem.  
Just put the executable in a folder of your choice and execute `./sherpa.out -r /home/your_project_path/` and you get your project visible at http://127.0.0.1:3030  
*That's it, enjoy \!*

## Licence

Sherpa is released under BSD licence, feel free to use/modify/embed it in your project.