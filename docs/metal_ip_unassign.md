## metal ip unassign

Unassigns an IP address.

### Synopsis

Example:

metal ip unassign --id [assignment-UUID]

	

```
metal ip unassign [flags]
```

### Options

```
  -h, --help        help for unassign
  -i, --id string   UUID of the assignment
```

### Options inherited from parent commands

```
      --config string     Path to JSON or YAML configuration file
      --exclude strings   Comma seperated Href references to collapse in results, may be dotted three levels deep
      --include strings   Comma seperated Href references to expand in results, may be dotted three levels deep
  -o, --output string     Output format (*table, json, yaml)
      --search string     Search keyword for use in 'get' actions. Search is not supported by all resources.
      --token string      Metal API Token (METAL_AUTH_TOKEN)
```

### SEE ALSO

* [metal ip](metal_ip.md)	 - IP operations

