# Identicon

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:identicon, "~> 0.1.0"}
  ]
end
```

## Notes
EGD - Erlang Graphical Drawer
`:egd` is no longer available in Elixir OTP, so to get around this

in mix.exs file,  add:

`{:egd, github: "erlang/egd"}`
To install dependencies:

```
mix deps.clean --all
mix deps.get
mix deps.compile
```

## Run

```
iex -S mix
iex(1)> Identicon.main("username")
```

See if `username.png` file is created

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/identicon>.

