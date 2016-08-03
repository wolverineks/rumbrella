# Rumbrella

```git clone git@github.com:wolverineks/rumbrella.git```

```cd rumbrella```

```mix deps.get```

```npm install```

```echo "use Mix.Config\nconfig :info_sys, :wolfram, app_id: 'your-app-id-here'" >> apps/config/dev.secret.exs```

```cd apps/rumbl && mix ecto.create && mix ecto.migrate && mix run priv/repo/seeds.exs && priv/repo/backend_seeds.exs```

```mix phoenix.server```
