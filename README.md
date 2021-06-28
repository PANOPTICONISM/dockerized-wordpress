# Instructions written by Panopticonism.

## SET UP:

- Install Docker + Docker-compose (Docker Desktop, preferably)
- Clone the repository into your local machine
- cd into the repository folder
- Begin by checking out docker-compose.yml file

- To get SSL(HTTPS), install mkcert (https://github.com/FiloSottile/mkcert) and create certificates into the certs folder
- Run 'docker-compose --env-file ./variables.env up' or 'docker-compose --env-file ./variables.env up -d'
- Open 'localhost' for WordPress, open 'localhost:8080' for phpMyAdmin
