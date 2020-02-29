# Movies
Displays summary information about a movie.

## movies (Project Info)
[Website](https://github.com/alexanderepstein/Bash-Snippets)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/movies/)

## Build image
`$ docker build -t macabees/movies:latest .`

## Run image
`$ docker run -it --rm macabees/movies batman`

## Docker Push
`$ docker push -t macabees/movies:latest`

Note: requires `docker login`

## Help
`$ docker run -it --rm macabees/movies help`
