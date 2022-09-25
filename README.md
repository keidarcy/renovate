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
  "name": "renovate-config-fastcore",
  "version": "0.0.1",
  ...
  "renovate-config": {
    "default": {
      "extends": ["github>keidarcy/renovate:auto"]
    }
  }
}
```
