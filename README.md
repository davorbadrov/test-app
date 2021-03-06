# TestApp repo

![Build Status](https://codebuild.eu-central-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiS2NlUnFVUStQSVB0dXlkNHlUc1lheFdSbjBYQTAvWlF1aTZTNjBOQzRnemlXSlYwUThUaWFDdU8yZW1kMHI5N0xhcDJyN2lQdXIrYlJRQ3JxNnN1a0dnPSIsIml2UGFyYW1ldGVyU3BlYyI6IkdBaTNrY2FLQVNHZXZrTEwiLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master)

To start your Phoenix server:

- Install dependencies with `mix deps.get`
- Create and migrate your database with `mix ecto.setup`
- Install Node.js dependencies with `cd assets && npm install`
- Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

- Official website: https://www.phoenixframework.org/
- Guides: https://hexdocs.pm/phoenix/overview.html
- Docs: https://hexdocs.pm/phoenix
- Forum: https://elixirforum.com/c/phoenix-forum
- Source: https://github.com/phoenixframework/phoenix

## Run DB via Docker

```sh
docker run --name test-db \
  -e POSTGRES_USER=testuser \
  -e POSTGRES_PASSWORD=testpassword \
  -e POSTGRES_DB=caris-test-db \
  -e POSTGRES_HOST=localhost \
  -e POSTGRES_PORT=5432 \
  -p 5432:5432 \
  -d postgres
```
