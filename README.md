# Rust

Rust Source files have `.rs` extension.

Cargo: Is a colletion of package manager, build system, documentation generator and test runner

toml files: Tom's Obvious Minimal Language, contains meta information about the projects such as name, version, authors and edition. Also contains depedencies. Fetches the email from global git configuration if there is any!

`rustc` is the rust compiler bundled into `cargo`

Few basic cargo commands:

# `cargo new <Project_Name>` will create a project named '<Project_Name>'
# `cargo run` will build and run the project (From target/debug/<Project_Name>
# `cargo run --release` will build and run the release version of the <Project_Name>, the execution is faster as compated to debug version and compilation process is slower than debug version.

A few things to know before-hand:

# Scope rules with `{` and `}` are similar to C/C++
# `let` is used to declare a variable
# Rust is a strongly type-annotated language, however, you can leave the type-annotation aside if Rust can determine the correct daya type for the variable
# `let` statement can destructure the data on RHS and use it to initialize the patterns on the LHS
# All variable by-default are immutable. This is for speed optimization, safety and concurrency.
# `let mut` syntax is used to override the immutability.
# `const` provide further immutability within the module, making it global immutable variable in the module.


# Primitive data types:

