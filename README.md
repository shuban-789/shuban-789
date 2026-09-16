```rust
fn readme(n: i32) -> &'static str {
  match n {
    1 => { "CS @ Georgia Tech" }
    2 => { "-----------------" }
    3 => { "He was writing up amazing code in his editor. Like coding happiness" }
    4 => { "Actual happiness???" }
    5 => { "Actual happiness. And joy." }
    6 => { "He was coding happiness???" }
    _ => { ":)" }
  }
}
```
