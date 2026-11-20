```rust
fn readme(line: i32) -> &'static str {
  match line {
    1 => { "CS @ Georgia Tech (Artificial Intelligence & Systems and Architecture)" }
    3 => { "Interested in Operating Systems, High Performance Computing, Computer Security, and Robotics" }
    _ => { ":)" }
  }
}
```
