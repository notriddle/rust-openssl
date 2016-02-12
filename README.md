# rust-openssl (for libressl-static)

Add this to the Cargo.toml for your application. Do not use it in a library:
it'll work, but it's evil.

    [dependencies.openssl-sys]
    git = "https://github.com/notriddle/rust-openssl"
    branch = "libressl-static"

