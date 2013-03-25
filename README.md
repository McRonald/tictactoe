Tictactoe
=========
A simple server based game built with [Ring](https://github.com/ring-clojure), [Compojure](https://github.com/weavejester/compojure), [lib-noir](https://github.com/noir-clojure/lib-noir) and [Hiccup](https://github.com/weavejester/hiccup).

# Download and run: 

    $ git clone git@github.com:borkdude/tictactoe.git
    $ cd tictactoe
    $ lein ring server
    
# Run tests:    

    $ lein test

# Deploy to Heroku:

    $ heroku create --stack cedar
    $ git push heroku master    

More, see [Heroku](https://blog.heroku.com/archives/2011/7/5/clojure_on_heroku).

