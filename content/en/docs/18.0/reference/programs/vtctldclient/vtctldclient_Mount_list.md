---
title: Mount list
series: vtctldclient
commit: d3012c188ea0cfc6837917fc6642ea23be9bb1ff
---
## vtctldclient Mount list

List all mounted external Vitess Clusters.

```
vtctldclient Mount list
```

### Examples

```
vtctldclient --server localhost:15999 mount list
```

### Options

```
  -h, --help   help for list
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient Mount](./vtctldclient_mount/)	 - Mount is used to link an external Vitess cluster in order to migrate data from it.
