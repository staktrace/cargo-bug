STR:

1) Go into subproj2/ and run `cargo update`. Observe how the Cargo.lock file doesn't contain ipc-channel.

2) Go to the workspace root, run `mv Cargo.toml-workspace Cargo.toml` and `cargo update`. Observe how the Cargo.lock file contains ipc-channel. But all this Cargo.toml does is act as a workspace for subproj2.

y u no behave the same?!
