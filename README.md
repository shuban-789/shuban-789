```rust
fn readme(n: i32) -> &'static str {
  match n {
    1 => { "CS @ Georgia Tech" }
    2 => { 
        "
        He was coding up amazing software in his editor.
        Like actual happiness.
        Actual happiness??
        Actual happiness. And joy.
        He was coding happiness????
        "
    }
    _ => { ":)" }
  }
}
```
