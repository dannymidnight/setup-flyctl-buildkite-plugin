# Setup `flyctl`

Installs [`flyctl`](https://github.com/superfly/flyctl) for use on [Buildkite](https://buildkite.com) Pipelines.

## Example

```yaml
steps:
- name: Deploy
  plugins:
    - dannymidnight/setup-flyctl
  command: flyctl deploy
```

## Requirements
- `FLY_ACCESS_TOKEN` – The token to use for authentication. You can find a token by running `flyctl auth token` or going to your [user settings on fly.io](https://fly.io/user/personal_access_tokens).
