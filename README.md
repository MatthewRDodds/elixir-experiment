# Elixir Science

## What is Elixir?

Elixir is a dynamic, functional language designed for building scalable and maintainable applications.

Elixir leverages the Erlang VM, known for running low-latency, distributed and fault-tolerant systems, while also being successfully used in web development and the embedded software domain.

## Is Elixir well supported?

Yes! 6,700 stars on github, 2,200 resolved issues (only ~30 unresolved currently).

## When does Elixir excel and when is it not the right solution?

### What Elixir excels at

Elixir is designed from the ground up to be highly scalable. Using a functional paradigm, Elixir runs inside of a 'process', which is a lightweight thread of execution. Hundreds of thousands of these processes can run concurrently on one machine, so it's also designed for maximum efficiency this way given limited resources.

Elixir has fault tolerance in its ability to define 'supervisors' which are able to detect downed parts of the system and restart them. This way the system is always kept in the same state it starts out at.

Elixir runs on the Erlang VM giving developers complete access to Erlang’s ecosystem, used by companies like Heroku, Whatsapp, Klarna, Basho and many more to build distributed, fault-tolerant applications. An Elixir programmer can invoke any Erlang function with no runtime cost.

See this discussion about transitioning away from rails to languages like Elixir: https://www.amberbit.com/blog/2015/12/22/when-choose-elixir-over-ruby-for-2016-projects/

### When it isn't the right choice

While Elixir does really well in the web programming space, it isn't the right choice for highly algorithmic applications that need to perform lots of intensive calculation. This use case is more suitable to either the Go or Rust languages.

## OSX Installation

```
brew install elixir
```

It is highly recommended to add Elixir’s bin path to your PATH environment variable to ease development.

```
export PATH="$PATH:/path/to/elixir/bin"
```

## Demo

Build a small elixir demonstration of elixir working with react to render a react component server side.
