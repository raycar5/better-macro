# Hi
![Have I been pwned](https://first-response.co.uk/wp-content/uploads/2017/11/pwned-1024x585.png)

No, not really, but you could have, if you are here it means you have built a Rust crate that uses this crate as a dependency and I wanted to showcase that any [proc macro](https://doc.rust-lang.org/reference/procedural-macros.html) can run arbitrary code in your machine simply by building a crate that depends on it or even just opening it on your editor (because of [rust-analyzer](https://github.com/rust-analyzer/rust-analyzer)), depending on your threat model you might not care much about this, or you might care a lot, it's up to you to take steps, if you feel like this is a credible attack vector.

You may also want to know that this "exploit" won't work upon opening the file in your editor if you are using [rls](https://github.com/rust-lang/rls).

If you were linked here, you can clone this repo and open it in your editor to see if you are vulnerable.

(You should probably look at the code first, don't take my word for it, I could have sold all the files in your hard drive by now)
