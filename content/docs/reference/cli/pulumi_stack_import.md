---
title: "pulumi stack import"
---



Import a deployment from standard in into an existing stack

### Synopsis

Import a deployment from standard in into an existing stack.

A deployment that was exported from a stack using `pulumi stack export` and
hand-edited to correct inconsistencies due to failed updates, manual changes
to cloud resources, etc. can be reimported to the stack using this command.
The updated deployment will be read from standard in.

```
pulumi stack import [flags]
```

### Options

```
      --file string   A filename to read stack input from
  -f, --force         Force the import to occur, even if apparent errors are discovered beforehand (not recommended)
  -h, --help          help for import
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
  -i, --show-ids                     Display each resource's provider-assigned unique ID
      --show-secrets                 Display stack outputs which are marked as secret in plaintext
  -u, --show-urns                    Display each resource's Pulumi-assigned globally unique URN
  -s, --stack string                 The name of the stack to operate on. Defaults to the current stack
      --tracing string               Emit tracing to a Zipkin-compatible tracing endpoint
  -v, --verbose int                  Enable verbose logging (e.g., v=3); anything >3 is very verbose
```

### SEE ALSO

* [pulumi stack](/docs/reference/cli/pulumi_stack/)	 - Manage stacks

###### Auto generated by spf13/cobra on 11-Sep-2019
