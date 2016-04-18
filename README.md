# app

Built from an instance of a project generated by yeoman angular generator this seed has all the bits I want and follows a component based structure, viz:
* assets: app/assets/{css,img,..}
* code: 
  * app definition: app/app/app.module.js
  * UI router states: app/app/app.states.js
  * app configuration: app/app/configuration.js
  * components: app/app/components
  * services: app/app/services
  * filters: app/app/filters
  * test data: app/app/test-data
  * example code (components, services, filters and spec files): app/app/examples

## Setup
`npm install && bower install`

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `karma start test/karma.conf` and then connect a browser by connecting to http://($host):8080

