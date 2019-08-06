# atlassian-docker-compose
Deploys Atlassian Jira Software, Confluence and Bitbucket with a PostgreSQL 9.6 database.

Usage:

 - Clone the repo
 - Copy env.example to .env and fill out the variables
 - Copy scripts/atlassian.sql.example to scripts/atlassian.sql and change the password
 - Run docker-compose up -d
