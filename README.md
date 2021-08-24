# Heroku buildpack for Coupa

This is a Heroku buildpack for Coupa standard tooling

## Usage

Run the following commands to overwrite existing buildpacks:

    $ heroku buildpacks:clear
    $ heroku buildpacks:add --index 1 git@github.com:tivonahaug/heroku-buildpack-coupa.git
