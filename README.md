# kryptokrauts.com
[https://kryptokrauts.com/](https://kryptokrauts.com/)

contains all sources and content for kryptokrauts.com

## Development
Just clone the repo:

``` sh
$ git clone git@github.com:kryptokrauts/hugo-icarus-theme.git
```

And run development server:

``` sh
$ docker-compose up server
```

To build static files:

``` sh
$ docker-compose run hugo
```

## Deployment
Project is setup to automatically deploy `source` branch with CircleCI. Just
merge changes to it and it will soon be deployed.