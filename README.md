A Dockerfile for Phoenix built from elixir:alpine.

The same commands from elixir should run, additionally hex.pm and Phoenix command should work.

Examples:

    docker build . -t elixphx
    docker run -it --rm -v `pwd`:/usr/src/myapp -w /usr/src/myapp elixphx mix phx.new helloworld
    docker run -it --rm -v `pwd`:/usr/src/myapp -w /usr/src/myapp elixphx iex 

