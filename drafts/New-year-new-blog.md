## New year new Blog

Hello there, and Happy New Year 2022!

I decided to move my blog from static files to the dynamic site, in my case it is Ghost. 

I like the easy setup of ghost and how it looks, tried this a few times before but mostly returned to the static page generator. One I'm using at most is Hugo, it's fast, written in go so installation is like copying one executable file to your computer. Ok back to the theme.

Ghost is a blogging platform (like WordPress). It is written in Javascript (you can put it on shared Webhosting - mostly, as its needs a server to execute serverside javascript). You have more options on how to run in: You can buy a ghost-hosted version (it's paid monthly, price going up by tier you select) or you can self-host on your server. I've chosen the latter one.

I'm running my Ghost with docker-compose on 4$ Virtual machine, with daily off-site backups. As my site doesn't have many visitors a day I choose SQLite as my database server. SQLite doesn't need any special installation, just access rights to database files on your filesystem. By tests, SQLite can server 100k concurrent sessions per hour, and 90% of all sites not going that high traffic. Maybe in the future, who knows.

Ghost by default uses their Casper theme which in my opinion is one of the most beautiful themes for blogging. You can customize color, site icon, fonts. It also allows you to inject your code.

It has a minimalistic back-end where you can manage your blog posts, pages, links, and more. Like most modern sites, it allows you to copy-paste images into your post (for example screenshots), but you can insert some royalty-free images. By default, Ghost uses the Unsplash database, so insert image is by a simple click. You don't need to resize images, upload them somewhere, and create an attribute for it. It will do everything above automatically.

In the case of memberships, It allows you to set up your newsletter without any plugin as it contains it out of the box. For emailing you will need an account at nailgun. Out-of-box it also has the option to allow access to your posts by the membership (free) or paid membership (Premium). The latter requires you to have a stripe account.

It also has many integrations by default which I didn't have time to test. So that's it. Thank you for reading and Have a nice day (or evening or morning by the time you read this.) Bye!