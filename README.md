# LiveViewStudio

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

## Additional notes

This system is a pain in the butt to get spun up. 
First you have to install phx.new
but it complains about having too old a version
I have 12, but it asks for 14
I guess 14 isn't available on ubuntu, so I have
to specify phx.new version 1.6.16 (I think)
Then you have to go configure the database 
with postgres, but it's not obvious how to do that. 
So I had to go mess with psql until I got
a user and password combination for localhost
PLUS a corresponding database table that matches
the one provided in the project. 
But also these involve using commands I'm not familiar 
with, mainly from mix. 
e.g. mix ecto.create, ecto.setup, 
mix ecto.gen.migration create_users, 
and more
