## havener upgrade

Upgrades Helm Charts using a havener configuration

### Synopsis

Upgrades Helm Charts using a havener configuration file.

```
havener upgrade [havener config file] [flags]
```

### Options

```
      --config string   havener configuration file
  -h, --help            help for upgrade
      --reuse-values    reuse the last release's values and merge in any overrides
      --timeout int     upgrade timeout in minutes (default 40)
```

### Options inherited from parent commands

```
      --debug                 debug output - level 5
      --error                 error output - level 2
      --fatal                 fatal output - level 1
      --kubeconfig string     Kubernetes configuration file (default "~/.kube/config")
      --terminal-height int   disable autodetection and specify an explicit terminal height (default -1)
      --terminal-width int    disable autodetection and specify an explicit terminal width (default -1)
      --trace                 trace output - level 6
  -v, --verbose               verbose output - level 4
      --warn                  warn output - level 3
```

### SEE ALSO

* [havener](havener.md)	 - Convenience wrapper around both kubectl and helm

###### Auto generated by spf13/cobra on 19-Oct-2019
