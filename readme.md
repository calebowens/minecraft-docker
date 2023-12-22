# Caleb's Minecraft docker compose setup

This project is part of my move to run all of my servery things off of just one VPS using reverse proxying and docker
compose.

A large part of the code for this was taken from [this fantastic project](https://hub.docker.com/r/phyremaster/papermc).

I've chosen not to use their image directly as I would like to integrate things like [pluGET](https://github.com/Neocky/pluGET)
and I've introduced some some ENVVars for setting my minecraft user as an operator
