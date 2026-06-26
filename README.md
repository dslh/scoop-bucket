# scoop-bucket

A [Scoop](https://scoop.sh) bucket for [dslh](https://github.com/dslh) command-line tools
on Windows. Manifests here are published automatically by
[GoReleaser](https://goreleaser.com) when a tool cuts a release.

## Usage

```sh
scoop bucket add dslh https://github.com/dslh/scoop-bucket
scoop install <app>
```

## Available apps

- **[mm](https://github.com/dslh/mm)** — CLI + MCP server for the mon-marché.fr grocery
  (cart only).

  ```sh
  scoop install mm
  ```
