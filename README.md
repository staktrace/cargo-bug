STR:
1) Go into subproj1/ and run `cargo update`. Observe how the Cargo.lock file doesn't contain ipc-channel.
2) Go to the workspace root, `mv Cargo.toml-workspace Cargo.toml` and run `cargo update`. Observe how the Cargo.lock file contains ipc-channel.

y u no behave the same?!
