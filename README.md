# GO COBRA POC

This is a proof of concept cli tool built with cobra.

Init a cobra project inside a go module

```bash
cobra-cli init
```

Add commands

```bash
cobra-cli add config
cobra-cli add buildWeb
cobra-cli add seedDatabase
cobra-cli add runNode
```

Add sub-commands

```bash
cobra-cli add create -p configCmd
cobra-cli add production -p runNodeCmd
```
