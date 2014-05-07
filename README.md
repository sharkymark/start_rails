start_rails
===========

As you get going, you'll want ways to run multiple Rails apps at the same time, as well as run the same app across environments.

To run Rails on a specific port:

rails server -p 3001
OR
rails s -p 3001

Put whatever port number you want, just make sure your firewall lets traffic through it, if a browser is trying to access your app from outside the firewall.

To run Rails for a specific environment:

rails s -e production

rails s -p development

I think by default, Rails runs your development environment, unless you configure it otherwise.

rails s

To do both!!!

rails s -e production -p 3001
