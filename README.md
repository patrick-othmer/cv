# CV Generator with hugo, docker & wkhtmltopdf

A modern solution to create a CV / Resume page including PDF export.

## Screenshot

![Orbit screenshot](https://raw.githubusercontent.com/aerohub/hugo-orbit-theme/master/images/screenshot.png)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* [docker-compose](https://github.com/docker/compose)
* [docker](https://www.docker.com/)

### Installing

Install all above mentioned programs.

### Configure

The configuration is done via config.toml for Hugo & docker-compose.yml for Docker.

## Workflow

Adapt your CV via config.toml. The result will be automatically rendered to localhost:1313. As soon as you are finished you can create the PDF file via `docker-compose up -d wkhtmltopdf`. The result will be saved in the dist folder. The HTML files can be rendered by `docker-compose run hugo hugo`. The result can be found in public.

## Built With

* [Hugo](https://gohugo.io/) - Hugo - The world’s fastest framework for building websites
* [hugo-orbit-theme](https://github.com/aerohub/hugo-orbit-theme) - Great looking resume/CV theme designed for developers.
* [docker-compose](https://github.com/docker/compose) - Docker compose
* [docker](https://www.docker.com/) - Docker
* [surnet/alpine-wkhtmltopdf](https://hub.docker.com/r/surnet/alpine-wkhtmltopdf) - wkhtmltopdf docker image
* [monachus/hugo](https://hub.docker.com/r/monachus/hugo) - Hugo Docker image

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/patrick-othmer/cv/releases).

## Authors

* **Patrick Othmer**

See also the list of [contributors](https://github.com/patrick-othmer/cv/graphs/contributors) who participated in this project.
