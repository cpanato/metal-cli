## metal hardware-reservation get

Retrieves all hardware reservations of a project or a single hardware reservation

### Synopsis

Example:

Retrieve all hardware reservations of a project:
metal hardware_reservations get -p [project_id]

When using "--json" or "--yaml", "--include=project,facility,device" is implied.
	

```
metal hardware-reservation get [flags]
```

### Options

```
  -h, --help                help for get
  -i, --id string           UUID of the hardware reservation
  -p, --project-id string   Project ID (METAL_PROJECT_ID)
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

* [metal hardware-reservation](metal_hardware-reservation.md)	 - Hardware reservation operations

