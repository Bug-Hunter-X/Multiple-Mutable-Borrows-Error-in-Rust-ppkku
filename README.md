# Multiple Mutable Borrows in Rust

This repository demonstrates a common error in Rust programming: attempting to have multiple mutable borrows of the same data. Rust's borrow checker prevents this to ensure data integrity and prevent data races.  The `bug.rs` file contains code that causes this error, while `bugSolution.rs` shows how to fix it.