## Run locally

`yarn develop`

If errors show up, make sure you're using latest yarn release (v3+)

`yarn set version stable`

## Deployment

To deploy the latest from main:

`git push heroku main:main`

or

`git push heroku [branch-to-deploy]:main`

## Extras

### Generate typescript types

Using [strapi-generate-types](https://www.npmjs.com/package/strapi-generate-types) you can generate typescript types based on your strapi models to use in your frontend app

To generate types run:
`yarn strapi-generate-types generate`
