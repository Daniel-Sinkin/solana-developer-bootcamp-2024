# Solana Developer Bootcamp 2024
This repo contains my personal implementations for the Solana Developer Bootcamp from 2024.

## Roadmap (0 / 9)
* [ ] Project 1
* [ ] Project 2
* [ ] Project 3


# Getting it to run
This is mainly general Rust stuff, but might be helpful.

## VSCode specific
Add the following entry to your `.vscode/settings.json`, so rust-analyzer can find the modules.
```
    "rust-analyzer.linkedProjects": [
        "./project_01/Cargo.toml",
        "./project_02/Cargo.toml",
        "./project_03/Cargo.toml",
        "./project_04/Cargo.toml",
        "./project_05/Cargo.toml",
        "./project_06/Cargo.toml",
        "./project_07/Cargo.toml",
        "./project_08/Cargo.toml",
        "./project_09/Cargo.toml",
        "./project_10/Cargo.toml",
        "./project_11/Cargo.toml",
        "./project_12/Cargo.toml",
        "./project_13/Cargo.toml",
    ]
```


## MacOS specific
On MacOs, if your System Library is not found while compiling you could try adding
```
export RUSTFLAGS='-L /Library/Developer/CommandLineTools/SDKs/MacOSX.sdk/usr/lib'
```
to your .zshrc

# References
* Solana Developer Bootcamp 2024:
    * [YouTube](https://www.youtube.com/watch?v=amAq-WHAFs8)
    * [GitHub](https://github.com/solana-developers/developer-bootcamp-2024)
* [Solana Playground](https://beta.solpg.io)
* [Anchor](https://github.com/coral-xyz/anchor)
* [Seahorse Lang](https://www.seahorse.dev)
  * Python Module built on top of Anchor
