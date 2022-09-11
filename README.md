# Old-A10dance
This is A10dance at the point of having it up and running using nginx and Docker.
No Kubernetes at this point. 

Good for demos and for editing the webui, database, and node without worrying about the cloud stuff.

##Get Website Up and Running
1. Open a CloudLab instance for docker
2. ssh into cloudlab in terminal
  a. Clone this git hub repository
3. Update uri for current instance
  a. Go to: client-experimental/build/static/js/main.835a8558.js
    - update uri so that it is your current cloudlab Ex. http://clnodevm085-1.clemson.cloudlab.us
4. Go back to the main A10Dance directory
5. Run command: docker-compose up
6. Clean up after running docker-compose(needs to be done if you edit the code and then want to run the website again)
  a. Run command: docker system prune -a
