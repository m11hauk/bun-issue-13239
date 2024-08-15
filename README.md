# workspaces

Clean:

```bash
bun clean
```

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run build
```

According to the documentation here:
https://bun.sh/docs/cli/filter#dependency-order

The package manager should consider dependencies between packages in monorepo when running 
the same scripts via --filter. So if one package depends on another the execution of the 
scripts across packages shouldn't be simultaneous.

