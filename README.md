# azenv

Set Azure CLI environment variables and execute.

## Requirements

- [azure-cli](https://github.com/Azure/azure-cli)

## Features
- Run command with specified profile's configuration.
- Export configuration environment variables.

## Usage

Login and save configuration to my-profle:

```
% azenv -p my-profile az login --tenant xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx
```

Run a command with my-profle:

```
% azenv -p my-profile az account show
```

Use profile in current shell session with my-profile:

```
% eval $(azenv -p my-profile)
```

## See Also
- https://github.com/buzztaiki/awsenv

## License

MIT
