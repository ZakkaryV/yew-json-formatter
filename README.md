# What is this
A JSON viewer / formatter with collapsible nesting. 

# Goals
1. Explore the recreation of classic UI component with novel technologies and measure their viability for production scenarios
2. Draw comparisons to app development with more popular, accessible technologies (react, typescript etc)
  a. Development speed
  b. Technical complexity
  c. Necessity to rely on open-source modules (as opposed to built-in abstractions)
  d. App performance: WASM DOM interop VS Native JS

# ~~Conclusion~~

# Technologies employed
* Rust
  * [rustup](https://rustup.rs/)
  * [cargo](https://doc.rust-lang.org/cargo/getting-started/installation.html)
* [Yew](https://yew.rs/docs/en/)
  * "Yew is a modern Rust framework for creating multi-threaded front-end web apps with WebAssembly"
* [wasm-pack](https://rustwasm.github.io/wasm-pack/book/)
* [Parcel](https://parceljs.org/getting_started.html)
  * javascript bundler

# Build this app from scratch
1. Update to latest rust toolchain
  `rustup toolchain install stable`
2. Install "wasm-pack" binary [globally]
  `curl https://rustwasm.github.io/wasm-pack/installer/init.sh -sSf | sh`
3. Initialize [this] repo
  `npm init yew-parcel <repo-name>`
4. Install deps
  `cd <repo-name> && npm i`
5. Run dev server
  `npm start`
6. Navigate to http://localhost:1234

# Reference materials
1. https://habd.as/post/getting-started-yew-rust/
2. https://jsonformatter.org/
