General things
==============
* open the play with docker website
* note that it might not work in Chrome with Company proxy (=> use DSL proxy or IE/FF)
* here you can start new instances to try out docker
* you are already connected to the internet there and can e.g. download images
* if needed, you can start multiple instances, but please note that resources must suffice for all
* we can run docker, docker-compose and use docker stacks/swarm here and will use the environment to showcase some features
* note that your session will be deleted and vanish after 4 hours again!
* also note that this is a public WebSite in the internet, DON'T input private/company data in there!
* have a lot of fun =)

Hands-On Part I
=================
- download the image alpine and run it with a echo command
- list  available images and containers afterwards
- also use inspect to show metadata of both
- remove image and container again
- what happens if we run the container without downloading the image?

Additional tasks for quick people
---------------------------------
- run a webserver in a container using nginx image
- use -p argument to make the port 80 available
- you‘ll see that a button pops up to access your website!
- jump into the container with docker exec
	- can you update  content  at `/usr/share/nginx/html/` ?
  - see config at `/etc/nginx/nginx.conf`

Still time?
-------------
- play with `mbentley/figlet` or take a look at `danielkraic/asciiquarium` :)


Other notes
============

Want to use a more simple text editor like nano?
-------------------------------------------------
You can install it with the package manager of alpine linux:
	
	apk update && apk add nano
	
What are we using here? About play-with-docker
---------------------------------------------
PWD is a Docker playground which allows users to run Docker commands in a matter of seconds. It gives the experience of having a free [Alpine Linux](https://alpinelinux.org/) Virtual Machine in browser, where you can build and run Docker containers and even create clusters in [Docker Swarm Mode](https://docs.docker.com/engine/swarm/). Under the hood Docker-in-Docker (DinD) is used to give the effect of multiple VMs/PCs. In addition to the playground, PWD also includes a training site composed of a large set of Docker labs and quizzes from beginner to advanced level available at [training.play-with-docker.com](http://training.play-with-docker.com/).

