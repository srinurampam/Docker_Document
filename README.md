What is Docker?
Simply put, a tool which is designed to make it easier to create, deploy, and run applications by using containers is what we call Docker. It is an open platform for developing, shipping, as well as running applications.

As its best feature, it enables us to separate our applications from our infrastructure so delivering software quickly will become easy. Moreover, usage of Docker helps to manage the infrastructure easily and in the same ways, one manages their applications.

Docker Architecture
While it comes to Docker architecture, it uses a client-server architecture. And, its architecture consists of 3 major parts, such as:

Docker Host
Docker Client
Registry

i. Docker Host
Basically, a Docker Host runs the Docker Daemon. As its job role, the daemon listens for Docker API requests such as ‘docker run’, ‘docker builds’, anything and also manages Docker objects like images, containers, networks, etc.

Moreover, one daemon can easily communicate with other daemons in order to manage Docker services.

ii. Docker Client
Here, the Client is nothing but the primary way by which many Docker users interact with Docker.

While we use various commands like (docker build, docker run, etc) the Docker client sends these commands to the Docker Daemon, which carries them out. One of the best features of Docker client is, it can easily communicate with more than one daemon.

iii. Docker Registries
A stateless, highly scalable server-side application, which stores and lets us distribute Docker images is what we call the Registry. There is a flexibility that either we can create our own image or we can use public registries such as Docker Hub and Docker Cloud.
