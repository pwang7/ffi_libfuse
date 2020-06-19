# Rust FFI with libfuse

* first, build libfuse:
    * go to `src/libfuse/` directory;
    * `$ mkdir build; cd build`
    * `$ meson ..`
    * `$ ninja`
* then, go back to `ffi_libfuse` directory to cargo build and run.
