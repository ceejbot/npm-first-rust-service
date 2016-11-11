# npm's first rust service

Here's a cleaned-up version of the presentation I gave to my team today (Nov 10 2016) about our first service in Rust.

* [slides in markdown format](slides.md)
* [rendered slides in PDF](slides.pdf)

What these slides are missing is the discussion we had about Rust-specific concepts like lifetimes and borrowing. They also make no attempt to introduce you to the language, but instead show you the kinds of things I had to learn how to do to make an operationalized microservice, that is, something for the real world.

## Rust web pages I learned from

* [the official docs](https://doc.rust-lang.org/book/)
* [Rust by Example](http://rustbyexample.com)
* [the faq](https://www.rust-lang.org/en-US/faq.html)
* the source code of every module from cargo that I used

If you can stomach the attitude of The Question Police on Stack Overflow, there are some useful questions asked there.

Links my team shared with me afterward:

* [Rust means never having to close a socket](http://blog.skylight.io/rust-means-never-having-to-close-a-socket/) -- all about lifetimes.
