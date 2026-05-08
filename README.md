# EON Shadow simulations

This repository contains Shadow simulation scenarios for the EON network along
with helper bash scripts.

To run the simulations you need to:
1. Build the Shadow Docker image using `build.sh`
2. Package the `eon-client` binary with `package.sh`
3. Run the necessary tests with `run.sh`

Usage:
```
# ./run.sh <test_set>/<test_file.yaml>
```
Where `test_set` is a subdirectory of `scenario`, and `test_file.yaml` is one of
its files.

For example:
```
# ./run.sh simple/1k.yaml
```

> [!WARNING]
> All helper scripts require superuser permissions to execute!
