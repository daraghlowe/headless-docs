## wpeh alpha apps create

Create a new headless application

### Synopsis

The create command allow to create a new headless application.

```
wpeh alpha apps create [flags]
```

### Options

```
  -e, --environments string   Environments in JSON format (use with -n, -r flags; surround value with single quotation marks)
  -f, --filepath string       Path to file with JSON of the app to create (use without -e, -n, -r flags)
  -h, --help                  help for create
  -n, --name string           Assign a name to the app (optional use with -e, -r flags)
  -r, --repo string           GitHub repo associated with the app (use with -e, -n flags)
```

### Options inherited from parent commands

```
      --account string   account name (default "test_account_name")
      --config string    config file (default is $HOME/.wpe/config.yaml)
  -d, --debug            print logs
```

### SEE ALSO

* [wpeh alpha apps](wpeh_alpha_apps.md)	 - Manage headless applications

###### Auto generated by spf13/cobra on 13-Aug-2020