
---
```rs
use std::io::{self, stdout, Write};

fn main() -> Result<(), io::Error> {
    let mut stdout = stdout();
    stdout.write(b"Hello, there!")?;
    stdout.write(b"\n")?;
    stdout.write(b"Welcome to my GitHub profile.")?;
    stdout.flush()?;
    Ok(())
}
```
---
