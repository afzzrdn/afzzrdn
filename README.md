```rust
fn main() {
    let name: String = String::from("Rosselvert");
    let languages: Vec<&str> = vec!["rust", "python", "c++"];
    let interest: Vec<&str> = vec!["Distributed System", "System Programming", "AI/ML"];

    println!("hi, i'm {}", name);
    println!("i'm working with: {}", languages.join(", "));
    println!("i have an interest in: {}", interest.join(", ");
}
```

<!--START_SECTION:waka-->

```txt
Total Time: 348 hrs

TypeScript       145 hrs 13 mins       ██████████_______________   41.73 %
Rust             42 hrs 15 mins        ███______________________   12.14 %
C++              25 hrs 54 mins        ██_______________________   07.44 %
Python           14 hrs 19 mins        █________________________   04.11 %
```

<!--END_SECTION:waka-->

