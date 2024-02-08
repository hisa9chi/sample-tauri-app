# sample-tauri-app
Tauri practice project

## create rust project
```
cargo new <project_name>
```

## run
```
cargo run
```

## manage package : cargo-edit
1. install cargo-edit
```
cargo install cargo-edit
```

```
# add package
cargo add <package_name>
cargo add <package_name>@<version>

# add package (only dev)
cargo add <package_name> --dev

# upgrade package
cargo upgrade <package_name>

# delete package
cargo rm <package_name>
```

## file change detection : cargo-watch
1. install cargo-watch
```
cargo install cargo-watch
```

2. command
```
# auto check
cargo watch -x check

# auto test
cargo watch -x test

# auto run
cargo watch -x run

# auto check, test and run
cargo watch -x check -x test -x run

# auto custom command
cargo watch -- echo Hello
```