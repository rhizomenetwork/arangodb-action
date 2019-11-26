# ArangoDB GitHub Action

This [GitHub Action](https://github.com/features/actions) sets up ArangoDB.

# Usage

See [action.yml](action.yml)

Basic:
```yaml
steps:
- uses: xinova/arangodb-action@v1
  with:
    arangodb version: 'latest'  # See https://hub.docker.com/_/arangodb for available versions
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)