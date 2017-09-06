---
layout: post
title:  "cargo expand your mind"
date:   2017-09-06
categories: 
 - rust
---
[cargo expand] has been an invaluable tool for me the past week.
I am still a beginner rustacean and was trying to write documentation about
Diesel's derivable model traits.
Trying to read the generic definitions from the [API Docs]() and implment the traits by hand
proved to be a difficult task. 

[cargo expand]: https://github.com/dtolnay/cargo-expand

`cargo expand` takes the source code of your project and expands out what your macro code looks like.
I was able to follow along with the generated code while comapring to the trait definitions to learn
some of the more complex aspects of rust's type system.

// TODO: 
- Write some code with a procedural macro
- Show example in a use case
- Show how cargo expand works (write out bash prompts)
- Implement same code with expanded macro
- Link to relevant docs
