# RustCrypto: OFB

[![crate][crate-image]][crate-link]
[![Docs][docs-image]][docs-link]
[![Build Status][build-image]][build-link]
![Apache2/MIT licensed][license-image]
![Rust Version][rustc-image]
[![Project Chat][chat-image]][chat-link]

Generic implementation of the [Output Feedback][OFB] (OFB) block cipher mode
of operation.

<img src="https://raw.githubusercontent.com/RustCrypto/media/26acc39f/img/block-modes/ofb_enc.svg" width="50%"><img src="https://raw.githubusercontent.com/RustCrypto/media/26acc39f/img/block-modes/ofb_dec.svg" width="50%">

See [documentation][cipher-doc] of the `cipher` crate for additional information.

## License

Licensed under either of:

 * [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
 * [MIT license](http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

[//]: # (badges)

[crate-image]: https://img.shields.io/crates/v/ofb.svg?logo=rust
[crate-link]: https://crates.io/crates/ofb
[docs-image]: https://docs.rs/ofb/badge.svg
[docs-link]: https://docs.rs/ofb/
[license-image]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
[rustc-image]: https://img.shields.io/badge/rustc-1.85+-blue.svg
[chat-image]: https://img.shields.io/badge/zulip-join_chat-blue.svg
[chat-link]: https://rustcrypto.zulipchat.com/#narrow/stream/308460-block-modes
[build-image]: https://github.com/RustCrypto/block-modes/actions/workflows/ofb.yaml/badge.svg
[build-link]: https://github.com/RustCrypto/block-modes/actions/workflows/ofb.yaml

[//]: # (general links)

[OFB]: https://en.wikipedia.org/wiki/Block_cipher_mode_of_operation#Output_feedback_(OFB)
[cipher-doc]: https://docs.rs/cipher/
