Rusty Line Follower 🦀
======================
Line follower robot built with Rust, utilising the [avr-hal](https://github.com/Rahix/avr-hal-template) project. For now it only supports the Arduino Uno board, but the code can easily be adapted for other boards with the help of the [avr-hal examples](https://github.com/Rahix/avr-hal/tree/main/examples).
## Prerequisites
You need to have the following installed on your system:
### Rust
Install the Rust compiler, this this curl command:
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
### Avrdude
The installation process for `avrdude` will depend on your OS.
#### Windows
You can download `avr-gcc`, which includes `avrdude`.
#### MacOS
`avrdude` is packaged in a homebrew formula and can be installed with
```
brew install avrdude
```
#### Linux
There should be a `avrdude` package in your distro package manager, for instance for Ubuntu you can use:
```bash
sudo apt-get install avrdude
```
## Usage
Clone this repo:
```
git clone git@github.com:axiomatic-aardvark/rusty-line-follower.git
```
And just run the project:
```bash
cargo run
```
## License
Licensed under either of
 - Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
 - MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)
at your option.
## Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
