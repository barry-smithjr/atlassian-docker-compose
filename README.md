# atlassian-docker-compose
Deploys Atlassian Jira Software, Confluence and Bitbucket with a PostgreSQL 9.6 database.

Usage:

 - Clone the repo
 - Copy env.example to .env and fill out the variables
 - Copy scripts/atlassian.sql.example to scripts/atlassian.sql and change the password
 - Copy traefik/traefik.toml.examle to traefik/traefik.toml and change the email, domain and password
 - Run docker-compose up -d
