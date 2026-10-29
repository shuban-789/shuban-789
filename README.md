```rust
fn readme(line: i32) -> &'static str {
  match line {
    1 => { "CS @ Georgia Tech" }
    2 => { 
        "
        He was coding up amazing software. Like actual happiness.
        Actual happiness??
        Actual happiness. And joy.
        He was coding happiness????
        "
    }
    _ => { ":)" }
  }
}
```
