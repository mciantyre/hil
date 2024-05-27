Personal hardware-in-the-loop tests to support [the imxrt-rs
project](https://github.com/imxrt-rs). To see the latest test results, go
[here](https://github.com/mciantyre/hil/actions).

## Capabilities

This repository runs nightly [probe-rs](https://probe.rs) tests against MIMXRT
targets. These tests might include probe-rs patches that I'm waiting to
upstream.

The setup includes an i.MXRT1010EVK attached to a Raspberry Pi. For more
information on the probe-rs testing workflow, see
[here](./.github/workflows/probe-rs-flashing.yml).

## Contributing

Have ideas for other testing capabilities? Open an issue! Those tests should
benefit the imxrt-rs project and work on my available hardware. I give priority
to tests that could benefit other embedded Rust projects.

Have any probe-rs patches that improve MIMXRT targets? I can accept your patches
in [my fork](https://github.com/mciantyre/probe-rs) then test them here. I can't
maintain your patches indefinitely, so please upstream your contributions once
you see it works.

## License

See [LICENSE](./LICENSE).
