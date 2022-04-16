# dragon-build

Github action to build a `dragon` package

## Usage

`dragon-build` takes no arguments when used in any workflow. Just use
the action like any other action under any workflow job.

```yaml
steps:
    - name: Build packages
      uses: DragonBuild/build@master
```

*You can also refer to any of the release tags, rather than using the
master version of the action.*
