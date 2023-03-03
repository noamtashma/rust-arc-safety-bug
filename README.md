# A demo for [Unsoundness in Arc](https://github.com/rust-lang/rust/issues/108706)

This is a fork of `rust` which modifies `Arc` to use a 32-bit counter, to demonstrate the issue.

run with
```
> ./x.py --stage 0 test library/alloc --test-args "exploit --nocapture"
```