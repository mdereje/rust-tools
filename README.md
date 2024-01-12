# RUST goofing

Installation: 
https://www.rust-lang.org/tools/install

- Compile with the command below to create a file called hello
```shell
rustc hello.rs
```
- Run the compiled file with 
```shell
./hello
```

For docs on how to do basic program functional stuff
https://doc.rust-lang.org/rust-by-example/conversion/from_into.html
### Types
**Tuples**
- A tuple is a collection of values of different types.
```RUST
let long_tuple = (1u8, 2u16, 3u32, 4u64,
-1i8, -2i16, -3i32, -4i64,
0.1f32, 0.2f64,
'a', true);
```


### Creating a library
```bash
#creating library
$ rustc --crate-type=lib rary.rs $ ls lib* library.rlib
#using library
$ rustc hello.rs --extern rary=library.rlib && ./hello
```


Where to go from: 
https://doc.rust-lang.org/rust-by-example/cargo/deps.html
