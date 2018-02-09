# Weasel

Weasel is a Heroku like fake name generator.

```elixir
iex(1)> Weasel.fake
"misty-flower-444"
iex(2)> Weasel.fake
"winter-dew-724"
```

Elixir clone of https://github.com/usmanbashir/haikunator.

P.S: If you can find out why it's named Weasel, just send me an email :)

## Installation

Weasel can be installed as:

  1. Add `weasel` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:weasel, "~> 0.1.1"}]
end
```

  2. Ensure `weasel` is started before your application:

```elixir
def application do
  [applications: [:weasel]]
end
```

