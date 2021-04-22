# victus
A Jekyll Theme design for food blogging.

## Docker Development

This project is being developed via Docker

### Jekyll version

This project uses Jeykll 3.8.6 which is the latest Docker image available that works with Github Pages.

### Third-party dependencies

Uses Bootstrap and Font-Awesome

### Running the Site Locally

`$ docker run -d --name victus --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:3.8 jekyll serve --watch --drafts`


## Configuration

### Site variables

`lang` = sets the language of the HTML. If not specified, the default is `en`

### Footer Urls

The footers will show up if a URL and Title is specified