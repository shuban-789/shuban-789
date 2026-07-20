```rust
fn readme(n: i32) -> &'static str {
  match n {
    1 => { "CS @ Georgia Tech" }
    2 => { "robotics & OS software" }
    _ => { ":)" }
  }
}
```
