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
ref = "branch/dev"
```

Then import each module by its source path in the package:

```mach
use encoding.base64;
```

`base64.encode` writes padded standard base64 and `base64.encode_url` writes unpadded url-safe base64, each sized by `base64.encoded_len`. `base64.decode` reads either alphabet, padded or not, into a buffer sized by `base64.decoded_len`.


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
