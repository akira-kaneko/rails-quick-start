# README

## Installed version
- ruby 2.6.3
- rails 5.2.3
- mysql 5.7

## Installation setting

### clone project.
`git clone https://github.com/akira-kaneko/rails-quick-start.git && cd rails-quick-start`

### boot the app.
`docker-compose up -d`

### create databases.
`docker-compose run web rake db:create`

### web browser to see.
http://localhost:3000/

## Appendix

## start a Bash session.
`docker-compose exec web bash`

## stop and remove containers.
`docker-compose down`
