# {plumber2}: Streamlining Web API Development in R

Slides: https://schloerke.com/presentation-2025-08-09-user-plumber2/

## Links

* `{plumber2}`: https://posit-dev.github.io/plumber2/
* Supporting packages:
  * `{fiery}`: https://fiery.data-imaginist.com/
  * `{routr}`: https://routr.data-imaginist.com/
  * `{reqres}`: https://reqres.data-imaginist.com/

## Abstract

Over the past nine years, the R package {plumber} has simplified the creation of web APIs using annotations over existing R source code with roxygen2-like comments. During this time, the community has gathered valuable insights and identified numerous areas for improvement. To invest in a way forward, a new package called {plumber2} has been created.

{plumber2} is designed from the ground up to be highly extensible, enabling developers to easily integrate custom decorators to modify the behavior of their APIs. Furthermore, {plumber2} is built using a modern foundation, leveraging the latest packages associated with the {fiery} framework. This modern architecture is built upon middleware (the ability to introduce custom logic at specific points within the API's request handling process).  One of the many fine-grained controls over how your API can behave.

By incorporating these improvements and embracing a modern framework, {plumber2} offers a sustainable path forward for building web APIs in R. This new approach avoids the need for short-term fixes and ensures that {plumber2} can continue to evolve and adapt to the changing needs of developers.
