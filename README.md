# ELK stack on Docker
> Fast and easy way to run ELK on Docker

## tl;dr
🔸 Clone it

🔸 Change domain.com on `docker-compose.yml`

🔸 Add your config

🔸 Run it


## Usage
Clone the repo
```sh
git clone https://github.com/brunopadz/docker-elk.git
```

As it runs jwilder's nginx reverse proxy on top of the stack, you have to change the domain configuration on `docker-compose.yml`

Create a new docker network called proxy (or whatever you want - just make sure to change it on `docker-compose.yml`)

Run it!
```sh
docker-compose up
``` 

### TODO
* Create examples of how add customized config on ELK like filters and stuff...
