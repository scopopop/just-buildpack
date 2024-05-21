# Just buildpack

Install the `just` binary from [https://github.com/casey/just](https://github.com/casey/just)
to handle `justfile` commands.

### Usage

This buildpack has no runtime and must be used in conjunction with other buildpacks.
On the Scalingo platform, you should use the Multi-buildpack through a `.buildpacks` file.

```
https://github.com/scopopop/just-buildpack#main
https://github.com/Scalingo/python-buildpack
```

> Note: the **last** buildpack of the list is your application runtime!

### Documentation

This is designed for the Scalingo platform.

- [just repository](https://github.com/casey/just)
- [Scalingo multi buildpacks documentation](https://doc.scalingo.com/platform/deployment/buildpacks/multi)
- [Scalingo custom buildpack documentation](https://doc.scalingo.com/platform/deployment/buildpacks/custom)

### License

Apache-2.0
