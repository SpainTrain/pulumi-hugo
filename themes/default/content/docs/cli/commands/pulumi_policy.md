---
title: "pulumi policy"
aliases:
  - /docs/reference/cli/pulumi_policy/
---



Manage resource policies

### Options

```
  -h, --help   help for policy
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

* [pulumi](/docs/cli/commands/pulumi/)	 - Pulumi command line
* [pulumi policy disable](/docs/cli/commands/pulumi_policy_disable/)	 - Disable a Policy Pack for a Pulumi organization
* [pulumi policy enable](/docs/cli/commands/pulumi_policy_enable/)	 - Enable a Policy Pack for a Pulumi organization
* [pulumi policy group](/docs/cli/commands/pulumi_policy_group/)	 - Manage policy groups
* [pulumi policy ls](/docs/cli/commands/pulumi_policy_ls/)	 - List all Policy Packs for a Pulumi organization
* [pulumi policy new](/docs/cli/commands/pulumi_policy_new/)	 - Create a new Pulumi Policy Pack
* [pulumi policy publish](/docs/cli/commands/pulumi_policy_publish/)	 - Publish a Policy Pack to the Pulumi Cloud
* [pulumi policy rm](/docs/cli/commands/pulumi_policy_rm/)	 - Removes a Policy Pack from a Pulumi organization
* [pulumi policy validate-config](/docs/cli/commands/pulumi_policy_validate-config/)	 - Validate a Policy Pack configuration

###### Auto generated by spf13/cobra on 17-May-2023