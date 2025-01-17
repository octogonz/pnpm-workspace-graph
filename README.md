# pnpm-workspace-graph

A visualizer let you display pnpm workspace graph

# Usage

```shell
pnpx pnpm-workspace-graph
```

or specify another workspace directory

```shell
pnpx pnpm-workspace-graph -C <your-workspace-dir>
```

visit http://localhost:8188 to see the graph

# CLI parameters

## `-C, --cwd`

Default: `process.cwd()`

Specify working directory, this directory must contains `pnpm-workspace.yaml` file.

## `-h, --host`

Default: `127.0.0.1`

Specify host.

## `-p --port`

Default: `8188`

Specify port.

## `-o --open`

Default: `true`

Whether to open browser after server started.

# Development in local

```shell
pnpm install
pnpm dev:client
pnpm dev  # in another shell

node lib/cli.js -C fixture/basic  # basic demo
```

# LICENSE

MIT @[chengcyber](https://github.com/chengcyber)
