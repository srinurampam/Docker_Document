Today, we will see Docker architecture to understand its working well. Also, we will see the brief description of Docker objects such as images, containers etc. However, to understand about Docker architecture well, it is must to know about Docker first. 

So, let’s start tutorial – Docker Architecture.

What is Docker?
Simply put, a tool which is designed to make it easier to create, deploy, and run applications by using containers is what we call Docker. It is an open platform for developing, shipping, as well as running applications.

As its best feature, it enables us to separate our applications from our infrastructure so delivering software quickly will become easy. Moreover, usage of Docker helps to manage the infrastructure easily and in the same ways, one manages their applications.

Docker Architecture
While it comes to Docker architecture, it uses a client-server architecture. And, its architecture consists of 3 major parts, such as:

Docker Host
Docker Client
Registry
At very first, Docker client talks to the Docker daemon, which performs the heavy lifting of the building, running, as well as distributing of our Docker containers. Basically, both the Docker client and daemon can run on the same system or we can connect a Docker client to a remote Docker daemon.

In addition, by using a REST API, the Docker client and daemon communicates, over UNIX sockets or a network interface. Now, let’s learn about all three components of Docker Architecture in detail:


i. Docker Host
Basically, a Docker Host runs the Docker Daemon. As its job role, the daemon listens for Docker API requests such as ‘docker run’, ‘docker builds’, anything and also manages Docker objects like images, containers, networks, etc.

Moreover, one daemon can easily communicate with other daemons in order to manage Docker services.

ii. Docker Client
Here, the Client is nothing but the primary way by which many Docker users interact with Docker.

While we use various commands like (docker build, docker run, etc) the Docker client sends these commands to the Docker Daemon, which carries them out. One of the best features of Docker client is, it can easily communicate with more than one daemon.

iii. Docker Registries
A stateless, highly scalable server-side application, which stores and lets us distribute Docker images is what we call the Registry. There is a flexibility that either we can create our own image or we can use public registries such as Docker Hub and Docker Cloud.

By default, Docker is configured to look for images on one of its public registries “Docker Hub”. One of the advantages it offers is we can create our own registry as well.

i. Docker Images
In simple words, a read-only template with instructions for creating a Docker container is what we call Docker Images. Many times, an image is based on another image, but with some additional customization.


In other words, an inert, immutable, file that’s essentially a snapshot of a container is what we call an image. Also, we can say that an image is a template with instructions for creating a Docker container.

In addition, images are so lightweight, small, as well as fast, when compared to other virtualization technologies.

ii. Docker Containers
Let’s understand about containers in a different way that, if an image is a class, then a container is an instance of a class—a runtime object. So, a runnable instance of an image is what we call a container. By using the Docker API or CLI, it is possible to create, start, stop, move, or delete a container.

Some more functions possible with Containers are, we can connect a container to one or more networks or we can attach storage to it, or also we can create a new image on the basis of its current state.
