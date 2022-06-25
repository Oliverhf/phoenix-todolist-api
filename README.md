# Creating an API with Phoenix(CRUD). | Todolist

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup` 
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

## The Main Goal

Create an API with Phoenix(CRUD). Understanding how Phoenix works with requests and creating an API REST that does CRUD operations.

## Side Notes

  Phoenix when gets a request its store in a variable called `conn` (connection)
  |> endpoint()
  |> router()
  |> controler()
  |> action()
  |> model_context()
  |> render()


  $ iex -S mix -> Executing the imperative prompt of elixir for compile the project, so that I can create new tasks from it.

  The Phoenix organizes the code complexity in layers, helping with the maintainability of the system.
