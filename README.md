```rust
fn readme(n: i32) -> &'static str {
  match n {
    1 => { "CS @ Georgia Tech" }
    2 => { "-----------------" }
    3 => { "He was coding up amazing programs in his editor. Like making happiness" }
    4 => { "Actual happiness???" }
    5 => { "Actual happiness. And joy." }
    6 => { "He was coding happiness???" }
    _ => { ":)" }
  }
}
```
