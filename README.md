# RestClient

The goal of theis project is to have an hands use of [HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP) methods using the Ruby's [rest-client](https://github.com/rest-client/rest-client) [DSL](https://en.wikipedia.org/wiki/Domain-specific_language).This project was undertaken as part of [Microverse](https://microverse.org) curriculum.

The mini-project was completed by:

- [Xarri Jorge](https://github.com/xarrijorge)
- [Sumaer Jolly](https://githhub.com/sumaerjolly)


The Project details are below;

1. Install the rest-client gem  using `gem install rest-client`
2. Open your command line env and start irb by typing `irb` at prompt
3. Load the rest-client gem into your environment using `require rest-client`; You should receive `true` as terminal output.
4. find and url and pull in the contents using `RestClient.get 'url'` and assign the result to a variable: eg `response = RestClient.get 'https://xarrijorge.com'`
5. You can now view the status code `responnse.code`, content `response.body` or cookies `response.cookies` from the respose variable;

Enjoy. 
