---
title: "pulumi stack export"
aliases:
  - /docs/reference/cli/pulumi_stack_export/
---



Export a stack's deployment to standard out

### Synopsis

Export a stack's deployment to standard out.

The deployment can then be hand-edited and used to update the stack via
`pulumi stack import`. This process may be used to correct inconsistencies
in a stack's state due to failed deployments, manual changes to cloud
resources, etc.

```
pulumi stack export [flags]
```

### Options

```
      --file string          A filename to write stack output to
  -h, --help                 help for export
      --show-secrets false   Emit secrets in plaintext in exported stack. Defaults to false
  -s, --stack string         The name of the stack to operate on. Defaults to the current stack
      --version string       Previous stack version to export. (If unset, will export the latest.)
```

### Options inherited from parent commands

```
      --color string                 Colorize output. Choices are: always, never, raw, auto (default "auto")
  -C, --cwd string                   Run pulumi as if it had been started in another directory
      --disable-integrity-checking   Disable integrity checking of checkpoint files
  -e, --emoji                        Enable emojis in the output
      --logflow                      Flow log settings to child processes (like plugins)
      --logtostderr                  Log to stderr instead of to files
      --non-interactive              Disable interactive mode for all commands
      --profiling string             Emit CPU and memory profiles and an execution trace to '[filename].[pid].{cpu,mem,trace}', respectively
      --tracing file:                Emit tracing to the specified endpoint. Use the file: scheme to write tracing data to a local file
  -v, --verbose int                  Enable verbose logging (e.g., v=3); anything >3 is very verbose
```

### SEE ALSO

* [pulumi stack](/docs/cli/commands/pulumi_stack/)	 - Manage stacks

###### Auto generated by spf13/cobra on 17-May-2023