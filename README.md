# isbnnetinclj2 #

A quick way to find the online prices for a book in India.

Written using [Clojure](http://clojure.org) programming language.

Special thanks to [@ghoseb](https://twitter.com/ghoseb) for the
inspiration and [guidance](https://github.com/ghoseb/isbn.clj/blob/master/src/isbn/core.clj).

If you're curious about the history of the project, see <http://swaroopch.com/tag/isbnnetin/>.

## Usage ##

1. Create AWS DynamoDB table
2. Install [Leiningen 2.x](http://leiningen.org/).
3. Get dependencies and run:

    ```bash
    lein deps
    lein ring server
    ```
4. Push to [Heroku](http://www.heroku.com).

## Dedication ##

This new rewritten version (0.8) is dedicated to:

1. [Atul Chitnis](http://www.nextbigwhat.com/atul-chitnis-obituary-297/),
   an inspiring person who I miss.
2. Dedicated users of isbn.net.in who badgered me continuously to fix
   the site which had stopped working!

## License ##

Copyright © 2012-2013 [Swaroop C H](http://swaroopch.com)

Distributed under the Eclipse Public License, the same as Clojure.
