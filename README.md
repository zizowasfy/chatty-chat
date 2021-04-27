# Chatty Chat

This repo is based on [https://github.com/juli1/flask-chat](https://github.com/juli1/flask-chat) to make a Server-Client chat program in python using Flask framework. 

This Program is Dockerized into a Docker image which can be used on any operating system without worrying about dependancies and packages 
needed to be installed for running this program.

## Instructions for using the Docker image:
1) In the termminal, Pull the image from Docker Hub

```bash
docker pull zizowasfy/chatty-chat:latest
```

2) Run the image in a container using the following command:

```bash
docker run -p 10000:5000 zizowasfy/chatty-chat
```

3) This creates a private server in the local network that can be accessed in any browser through the following *http* link 
[http://localhost:10000/](http://localhost:10000/)
Start with the user *admin*, password *admin*.


### Bonus addition
if you want to take it to the next level and chat with your friends/family that are connected to the same WIFI network, 
* replace *localhost* with your public network IP address which can be found from the WiFI network settings.
[http://<YOUR_IPv4_Address>:10000/](http://<YOUR_IPv4_Address>:10000/)



## Resources

* [https://github.com/juli1/flask-chat](https://github.com/juli1/flask-chat)
* [The Flask Website](http://flask.pocoo.org/)
* [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
* [Docker container for Flask](http://containertutorials.com/docker-compose/flask-simple-app.html)
* [The Amazing Flask Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
