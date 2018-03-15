# TODO

## Webpack

* define `DEV` globally
  * remove `process.env.NODE_ENV === 'production'` and `process.env.NODE_ENV !== 'production'`
* shrink bundle size
  * use uglifyjs (with `screw_ie8` option)

## Apollo

* add error handling to GraphQL Apollo Links
* precompile queries (https://www.apollographql.com/docs/react/recipes/babel.html)

## Server-Side Rendering

* html
  * uglify html in prod
  * pretty-print html in dev
* routing
  * respect redirects
  * respect 404s
    * render 404 using react, but add information to context, then use status from there for response-status-code on server

## GraphCool

* add permissions / restricted views

## Dev Exp

* add ESlint
* add Jest
* add Enzyme

## CI / CD

* setup CircleCI
* add E2E