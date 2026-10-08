# mach-encoding

<p>
  <a href="https://github.com/briar-systems/mach-encoding/actions/workflows/ci.yml"><img src="https://github.com/briar-systems/mach-encoding/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/briar-systems/mach-encoding?color=FF00FF&labelColor=000000" alt="License"></a>
</p>

**A Mach library for binary-to-text encodings, starting with base64.**

## Usage

Add the dependency to `mach.toml`:

```toml
[dep.encoding]
git = "https://github.com/briar-systems/mach-encoding"
version = "^0.1"
```

Then bind the library in a source file:

```mach
use encoding;
```


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
