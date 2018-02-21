## pks login

Login to PKS

### Synopsis

The login command requires -a to target the IP of your PKS API, -u for username and -p for password

```
pks login [flags]
```

### Examples

```
  pks login -a <API> -u <USERNAME> -p <PASSWORD> [--ca-cert <PATH TO CERT> | -k]
```

### Options

```
  -a, --api string              The PKS API server URI
      --ca-cert string          Path to CA Cert for PKS API
  -h, --help                    help for login
  -p, --password string         Password
  -k, --skip-ssl-verification   Skip SSL Verification
  -u, --username string         Username
```

### SEE ALSO

* [pks](pks.md)	 - The PKS CLI is for interacting with the PKS API
