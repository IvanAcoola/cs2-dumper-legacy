# cs2-dumper

An external offset/interfaces dumper for Counter-Strike 2, written in Rust.

*Note:* Original and modern one -> https://github.com/a2x/cs2-dumper

# Usage

You can either download the latest release from realeases or build it yourself. Note that building it yourself requires Rust's nightly toolchain.

If you want to see more detailed runtime messages, you can pass the `--verbose` flag.

For a complete list of all available flags, use `--help`.

# Generated Files

By default, generated files are stored in the `generated` directory. However, this can be modified by specifying your desired directory using the `--output` flag.

📂 [Pre-generated Files](./generated)

# Running Tests
To run tests, use the following command: `cargo test -- --nocapture`.

# License

Please refer to the [LICENSE](./LICENSE) file for more details.
