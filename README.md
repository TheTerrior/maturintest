# maturintest
To test for yourself, edit the file "test" to work with your system. Install Rust, Python, and cargo and/or maturin. Run these two commands:<br>
```
cargo build
./test
```
Note: you may have to change that second command to run on your system as well. The two files of interest are src/lib.rs and py_tester/main.py, good luck<br>
Another note: for a Python wheel file, use maturin build instead of cargo, you'll need to install that.