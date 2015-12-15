# RestApi

To start your Phoenix app:

  1. Install dependencies with `mix deps.get`
  2. Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  3. Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix


## Docker

### Running the application

```shell
docker-compose run --rm local
```

### Provisioning the Database

```shell
docker-compose run --rm local sh -c "mix ecto.create"
```

### Running Migrations

```shell
docker-compose run --rm local sh -c "mix ecto.migrate"
```

### Running Tests

```shell
docker-compose run --rm test
```
