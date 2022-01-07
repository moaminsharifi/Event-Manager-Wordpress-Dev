# docker-wordpress-theme-setup



## Installation

If you don’t have Docker and Docker Compose installed follow the steps outlined in the blog post linked above.

With Docker installed and running, in Terminal:

````
git clone --recurse-submodules -j8 https://github.com/bigmpc/Event-Manager-Wordpress-Dev-Env.git
cd Event-Manager-Wordpress-Dev-Env
````

Then:

````
docker-compose up -d
````

Then in your browser:
````
http://localhost:8000/
````

The aforementioned blog post has more information.
