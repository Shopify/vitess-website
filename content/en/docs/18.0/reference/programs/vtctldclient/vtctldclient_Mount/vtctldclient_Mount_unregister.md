---
title: Mount unregister
series: vtctldclient
commit: 9a6f5262f7707ff80ce85c111d2ff686d85d29cc
---
## vtctldclient Mount unregister

Unregister a previously mounted external Vitess Cluster.

```
vtctldclient Mount unregister
```

### Examples

```
vtctldclient --server localhost:15999 mount unregister --name ext1
```

### Options

```
  -h, --help          help for unregister
      --name string   Name of the mount.
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --server string             server to use for the connection (required)
```

### SEE ALSO

* [vtctldclient Mount](../)	 - Mount is used to link an external Vitess cluster in order to migrate data from it.
