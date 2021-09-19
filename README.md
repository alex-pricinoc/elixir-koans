# Elixir Koans

Elixir koans is a fun way to get started with the elixir programming language. It is a tour
of the most important features and idiomatic usage of the language.

### Prerequisites

You need to have Elixir installed. Please refer to the [official guide](http://elixir-lang.org/install.html) for instructions.

First, clone the repository from GitHub:

```sh
$ git clone https://github.com/elixirkoans/elixir-koans.git
$ cd elixir-koans/
```

Next, fetch mix dependencies by running:

```sh
$ mix deps.get
```

### Running

With the dependencies installed, navigate to the root directory of this project and run:

```sh
$ mix meditate
```

To show your previous results, run it with `--no-clear-screen`
```sh
$ mix meditate --no-clear-screen
```

To jump to a specific lesson, run it with `--koan=<koan name>`
```sh
$ mix meditate --koan=PatternMatching
```
