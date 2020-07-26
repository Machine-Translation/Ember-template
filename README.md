# Ember-template

Is a template that Ember projects can be started from with all development and production setup built in.

## Installation

* `git clone https://github.com/Machine-Translation/Ember-template`
* `docker-compose up --build`
* `docker-compose run --service-ports web /bin/sh`
* `(Inside container) yarn install`
* `exit` (get out of container)

## Running / Development

* `docker-compose up`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).
* To run any ember-cli commands, lint commands, or yarn commands, you must be inside docker container

### Code Generators

Make use of the many generators for code, try `ember help generate`, or `ember g --help` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Will come later...

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
