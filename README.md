# HeatTags

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


COMANDS>>

. criar novo projeto
  mix phx.new heat_tags --no-html --no-assets
. criar o banco de dados
  mix ecto.create
. iniciar o servidor
  mix phx.server
. criar migration
  mix ecto.gen.migration <migration_name>
. rodar migration
  mix ecto.migrate
. 


>>
Ler do banco de dados todos os emails unicos
 . fazer uma lista de emails diarios
Enviar para esses emails o report diarios de palavras
 . bamboo lib
guardar o report no banco de dados
 . para ter um historico e acompanhamento
 . campo do tipo jsonby, para guardar o mapa lá no campo
fallback_controller e utilizar para validação de erros


