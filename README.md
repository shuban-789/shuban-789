```rust
fn readme(line: i32) -> &'static str {
  match line {
    1 => { "CS @ Georgia Tech" }
    2 => { "Operating Systems, Embedded Systems Software, High Performance Computing, Robotics" }
    _ => { ":)" }
  }
}
```
