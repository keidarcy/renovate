# renovate config

## usage

- renovate.json

```json
{
    "extends": ["github>keidarcy/renovate:auto"]
}
```

- package.json(deprecated)

```json
{
  "name": "pkg-name",
  "version": "0.0.1",
  ...
  "renovate-config": {
    "default": {
      "extends": ["github>keidarcy/renovate:auto"]
    }
  }
}
```
