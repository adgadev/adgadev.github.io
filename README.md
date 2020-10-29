# adgadev.github.io

This repo contains the source code of the [adgadev.github.io](adgadev.github.io) website.
It is built using [Hugo](https://gohugo.io/) and hosted on [GitHub Pages](https://pages.github.com/).

## Editing

Launch a local Hugo server including live reload by running (append `-F` for including future posts):

```
hugo server -D --debug
```

## Deployment

```
./deploy.sh
```

## Prerequisites: 
```
sudo apt-get install ruby2.5-dev
brew install hugo
gem install asciidoctor rouge
```
