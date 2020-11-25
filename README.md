# Docker-python


## to build docker image use the command 
> docker build -t dockerpython .       
## in the same dir as the Dokcerfile

## then run the image
> docker run -p 5000:5000 dockerpython
## you can run it in detached mode with this command 
> docker run -d -p 5000:5000 dockerpython

## you can then go to your localhosr port 5000, to see the application running

