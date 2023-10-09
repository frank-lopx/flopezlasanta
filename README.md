### Hi there 👋

```rust
impl Flopezlasanta {
    pub fn about() -> Self {
        Self {
            name: "Francisco Lopez",
            planet_of_birth: "Earth",
            email: "flopezlasanta@gmail.com",
        }
    }
}

impl Programmer for Flopezlasanta {
    fn topics(&self) -> Vec<&'static str> {
        vec!["Trading", "Crypto", "24x7", "Low Latency", "Micro Services", "Machine Learning", "Big Data"]
    }

    fn major_languages(&self) -> Vec<&'static str> {
        vec!["Rust", "Java", "Scala", "Python"]
    }
}
```
