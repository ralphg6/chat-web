
# WebTier

Camada Web para interface com o usuário, desenvolvida em JS/HTML/CSS.
Na comunicação entre o cliente e o servidor para que se possa ter a experiência realtime será utilizado a estratégia de [HTTP Long Polling](https://www.pubnub.com/blog/2014-12-01-http-long-polling/).

# angular2-quickstart

This tiny repo is done according to angular2 quickstart guide
just to show how simple it is to use angular2 with 3rd party ng2-* modules
like this one: https://github.com/valor-software/ng2-bootstrap

# Quick start

Clone this repo
`npm i` and `npm start` and you are ready!

## Couple of things you should pay attention
1. Install and add `map` for `moment.js` in system.js config
  ```js
  'moment': 'node_modules/moment/moment.js'
  ```

2. Import `ng2-bootstrap` in `index.html` before starting application
  ```html
  <script src="node_modules/ng2-bootstrap/bundles/ng2-bootstrap.min.js"></script>
  ```

3. Use new forms
  ```js
  import {provideForms, disableDeprecatedForms} from '@angular/forms';

  bootstrap(AppComponent, [disableDeprecatedForms(), provideForms()]);
  ```
  
Good luck with angular2 hacking!
