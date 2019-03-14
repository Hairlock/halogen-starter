# Halogen Starter

## Ui

Built in purescript halogen with hot reloading using parceljs

### Build commands
* yarn setup
* yarn serve-dev

### Alternatively
* docker-compose up

## Deployment

### Travis ci 
* Travis performs Docker build and deploys ui and nginx images
* If on staging branch then trigger deploy on amazon elb (see .travis.yml)
