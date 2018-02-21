## pks resize

Increases the number of worker nodes for a cluster

### Synopsis

Resize requires a cluster name, and the number of desired worker nodes. Users can only scale UP clusters, to a maximum of 50 worker nodes and not scale down

```
pks resize <cluster-name> [flags]
```

### Examples

```
  pks resize my-cluster --num-nodes 5
```

### Options

```
  -h, --help              help for resize
  -n, --num-nodes int32   Number of worker nodes (default 1)
```

### SEE ALSO

* [pks](pks.md)	 - The PKS CLI is for interacting with the PKS API
