## pks create-cluster

Creates a kubernetes cluster, requires cluster name and an external host name

### Synopsis

Create-cluster requires a cluster name, as well as an external hostname. External hostname can be a loadbalancer, from which you access your kubernetes API (aka, your cluster control plane)

```
pks create-cluster <cluster-name> [flags]
```

### Examples

```
  pks create-cluster my-cluster --external-hostname example.hostname --plan production
```

### Options

```
  -e, --external-hostname string   Address from which to access Kubernetes API
  -h, --help                       help for create-cluster
      --json                       Return the PKS-API output as json
  -n, --num-nodes string           Number of worker nodes
  -p, --plan string                Preconfigured plans. Run pks list-plans for more details
```

### SEE ALSO

* [pks](pks.md)	 - The PKS CLI is for interacting with the PKS API
