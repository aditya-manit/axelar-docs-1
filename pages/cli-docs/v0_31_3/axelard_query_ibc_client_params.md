## axelard query ibc client params

Query the current ibc client parameters

### Synopsis

Query the current ibc client parameters

```
axelard query ibc client params [flags]
```

### Examples

```
`<appd>` query ibc client params
```

### Options

```
      --height int    Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help          help for params
      --node string   `<host>:<port>` to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
```

### Options inherited from parent commands

```
      --chain-id string     The network chain ID (default "axelar")
      --home string         directory for config and data (default "$HOME/.axelar")
      --log_format string   The logging format (json|plain) (default "plain")
      --log_level string    The logging level (trace|debug|info|warn|error|fatal|panic) (default "info")
      --output string       Output format (text|json) (default "text")
      --trace               print out full stack trace on errors
```

### SEE ALSO

- [axelard query ibc client](/cli-docs/v0_31_3/axelard_query_ibc_client) - IBC client query subcommands