```rust
fn readme(line: i32) -> &'static str {
  match line {
    1 => { "CS @ Georgia Tech" }
    3 => { "Interested in Operating Systems, High Performance Computing, and Robotics" }
    _ => { ":)" }
  }
}
```
