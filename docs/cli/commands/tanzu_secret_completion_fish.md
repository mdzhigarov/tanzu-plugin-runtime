## tanzu secret completion fish

Generate the autocompletion script for fish

### Synopsis

Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	secret completion fish | source

To load completions for every new session, execute once:

	secret completion fish > ~/.config/fish/completions/secret.fish

You will need to start a new shell for this setup to take effect.


```
tanzu secret completion fish [flags]
```

### Options

```
  -h, --help              help for fish
      --no-descriptions   disable completion descriptions
```

### Options inherited from parent commands

```
      --kubeconfig string   The path to the kubeconfig file, optional
      --verbose int32       Number for the log level verbosity(0-9)
```

### SEE ALSO

* [tanzu secret completion](tanzu_secret_completion.md)	 - Generate the autocompletion script for the specified shell

###### Auto generated by spf13/cobra on 14-Sep-2022